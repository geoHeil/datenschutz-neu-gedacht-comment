# Datenschutz neu gedacht - Kommentar


## prerequisites

- pixi https://pixi.sh/latest/ install via:
  - linux/mac: `curl -fsSL https://pixi.sh/install.sh | sh`
  - win: `powershell -ExecutionPolicy ByPass -c "irm -useb https://pixi.sh/install.ps1 | iex"`
- git https://git-scm.com/
- a text editor (for example) https://code.visualstudio.com/


```bash
git clone https://github.com/geoHeil/datenschutz-neu-gedacht-comment

cd datenschutz-neu-gedacht-comment

# directly run the preview
pixi run setup
pixi run preview
```

write the texts

## publishing

Multiple formats are possible

```bash
pixi run render
# observe all the generated pdf, html, word documents
# there is the possibility to fine-tune word https://quarto.org/docs/output-formats/ms-word-templates.html

pixi shell -e dev
```

## writing guidelines

- 1 sentence = 1 line so we can easily version control via git

## knowhow

```bash
# set up the project
quarto create project


```

## status


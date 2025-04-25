# DRAFT stuff
## draft thoughts and link material below

 Disproportionate Burden on SMEs:

     Current regulatory demands and lack of standard tools create significant overhead, potentially favouring large, established (often non-EU) companies 

.
 Difficulty for SMEs to implement sophisticated features like granular consent, timed expiry, or easy revocation, potentially hindering compliance and innovation 
.
 Risk of overly complex configuration management even for simple processes.

### structure outline

- challenges
  - lack of standard: missing protocol/interface
  - flexibility vs. enforcable - the trust challenge when working with data
  - adavantages for big (US) companies
  - ever more important relevancy in the age of MCP and AI
- suggestion: SPRIND like open innovation

### challenges

Challenges

    - interface/Protocol for data exchange with permissions missing especiall with good UX

    Lack of Universal Standards: There is no single, widely adopted standard or platform for granular, possibly even retractable data sharing.

    Contractual Complexity: Effective data sharing with retractable consent often relies on clear, enforceable contracts and robust technical infrastructure. working with data requires flexibility (CSVs) [@comande_differential_2022]

User Experience: Ensuring that users can easily understand, manage, and retract consent for individual data points remains a challenge for many platforms 
[@comande_differential_2022]

- advantageous for the big and established companies
  - repeated config management may lead to overboarding complexity (for simple processes)
  - data sharing may enable new intermediaries (but these do not come from the big i.e. like log in with apple, google, facebook)
- missing established technical implementation. Complexity in tracking databreaches
    - currently only focus on cookies
    - and droppox style sharing
    - further technical limitations (legal, technical vetting process)

what is mcp: [@noauthor_model_nodate]

relevancy to  MCP OAUTh [@peterson_oauths_2024]

fix oauth in mcp [@noauthor_lets_2025]

xss for mcp [@cross_s_2025]

#### implementation managable for small-medium sized companies

- european sized (small-medium) companies often do not benefit from the regulation
- we want to improve the state for society but not overburden the majority of european companies

#### missing established technical implementation

- no established large-scale implemenation (world wide, but also not in europe)
- some first moving applications

notable examples
- FHIR https://grants.nih.gov/grants/guide/notice-files/NOT-OD-19-122.html
- https://www.capminds.com/blog/the-mystery-behind-fhir-in-healthcare-data-sharing/

fhir [@noauthor_overview_nodate] [@noauthor_not-od-19-122_nodate, @admin_mystery_2020]

b2c

- https://mydatamyconsent.com/en-us

b2b

- https://nexyo.io/

Here is a footnote reference,[^1].

[^1]: Here is the footnote.

overview

- Personal Data Management Platforms
- Consent Management Tools (to manage all the cookie consents in a single place)
- Data Breach detection and handling

### suggestions

self create with public interest in mind

openly

#### SPRIND

[@noauthor_sprind_nodate]
example: https://www.sprind.org/en/actions/challenges/eudi-wallet-prototypes

- open innovation
- but on the european level for a souvereign Europe

### notes


makes personal data available, directly or indirectly>> da sollte klarer sein ob auch Model weights damit gemeint sind (nicht zu generisch)
    consent expiry für was genau? Für Marketing Consent? Für Basis Consent der Dienst Erbringung?
        Apple & Google zeigen ja wie es geht: Die Nutzer nicken bei JEDEM OS Upgrade was zumeist öfters als quartalsweise stattfindet neue AGB ab. Es ist also nicht undenkbar
        ABER: für die meisten kleinen / europäischen Firmen so extrem schwer verwaltbar / der Aufwand ist massiv. Viele haben noch nicht mal die Verwaltung von zeitlosen Consents (bis auf Widerruf) richtig gut abgebildet
    durable medium: Heißt das ausgedruckt? Falls ja - das wäre ökologisch nicht unbedingt zielführend
    Intermediaries: Es ist schon länger der Traum sowas zu haben (Herr seiner Daten zu sein und sie flexibel überall zu haben bzw. ggf. monetarisieren zu können)
        Aktuell ist mir kein ausgereifter bzw. auch verbreiteter Ansatz bekannt. Das heißt nicht, dass so etwas entwickelt werden kann. Ich bin mir aber nicht sicher, ob den Personen klar ist, was da für ein Aufwand dahinter steht. (plus auch Marktmacht notwendig ist)
        Am ehesten kommen hier wieder die großen amerikanischen Player (log-in-with---XXXX) bzw. Freigabe gewisser (Teil-) Aspekte der Daten

- https://www.permissionslipcr.com/


TODOS:

- NEED for DMA for MCP https://iamcharliegraham.substack.com/p/mcps-gatekeepers-and-the-future-of graham_mcps_2025

There is a deliberate lack of implementation experience with large-scale, user-facing digital wallets in Germany and much of the EU. SPRIND’s competition is designed to foster innovation, compare multiple approaches, and gather empirical data on usability, security, and interoperability before making a national decision
https://cms.system.sprind.org/uploads/EUDI_Wallet_Overview_20240709_EN_ffaec3139d.pdf
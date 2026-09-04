# 📖 Start here: the Civic Atlas Yellow Book — datasets, APIs, MCPs & communities, by country and subject

Welcome to the Civic Atlas! Here you will find a directory of various civic data sources.

Please keep in mind that these simply describe the platform, not the data's license. Website access, API costs, publishing eligibility, and data rights are their own individual things that you would need to do research on.

- 🟢 **Free** — no account, or a free key
- 🟡 **Freemium** — usable free tier, paid tiers above it
- 🔴 **Paywall / mixed** — payment, contract, or sponsor usually required

*This directory is maintained with AI assistance, and every entry is checked against its official source. The full source lives on GitHub — if anything is wrong or out of date, [open a pull request](https://github.com/anitacigawet/civic-atlas) or leave a comment. No moderator status needed.*

## 🤖 MCP & AI-agent access

What an AI agent — or you — can query or host data through.

| Service | What agents get | Access |
|---|---|---|
| [Civic Tech Field Guide](https://civictech.guide/build) | Civic-tech directory; no-key API + hosted MCP | 🟢 No account |
| [Google Data Commons](https://docs.datacommons.org/mcp/) | Statistical knowledge graph; MCP, REST/Python/Pandas, CSV, BigQuery | 🟢 Free key |
| [Hugging Face Hub](https://huggingface.co/docs/hub/datasets-adding) | Dataset hosting + APIs; [official MCP](https://huggingface.co/docs/hub/en/agents-mcp) | 🟢 Free account to publish |
| [Kaggle](https://www.kaggle.com/docs/datasets) | Dataset hosting + CLI/API; [official MCP](https://www.kaggle.com/docs/mcp) | 🟢 Free account |
| [GitHub](https://github.com/) | Repo hosting + APIs; [official MCP server](https://github.com/github/github-mcp-server) (OAuth/token) | 🟢 Free account |
| [Katzilla](https://katzilla.dev/docs) | Live government-data layer; REST, SDKs, MCP, A2A | 🟡 1,000 calls/mo free, then $49+/mo |

*A listing here doesn't mean any AI model trained on the data — hosting, indexing, and training are three different things.*

## 📊 Datasets & data portals

### 🟢 Free — no account (or free key)

| Source | What it is |
|---|---|
| [Wikidata](https://www.wikidata.org/wiki/Help:Data_access) | CC0 knowledge graph; SPARQL, REST, bulk dumps |
| [OpenStreetMap](https://www.openstreetmap.org/) | ODbL global geo database; planet files, extracts, Overpass |
| [data.europa.eu](https://data.europa.eu/) | EU institutions + harvested national catalogs; API, SPARQL |
| [World Bank Data Catalog](https://datacatalog.worldbank.org/) · [Open Data](https://data.worldbank.org/) | Global development datasets + APIs |
| [OECD Data Explorer](https://data-explorer.oecd.org/) | Economic/social/environmental statistics; SDMX |
| [IMF Data](https://data.imf.org/en) | Macro & financial statistics; SDMX |
| [Humanitarian Data Exchange](https://data.humdata.org/) | Humanitarian datasets; CKAN API (vetted orgs contribute) |
| [WHO World Health Data Hub](https://data.who.int/) | Global health indicators & downloads (API in transition) |
| [FAOSTAT](https://www.fao.org/faostat/) | Food & agriculture for countries/territories; API, bulk |
| [UNdata](https://data.un.org/) | Aggregated official statistics (partly legacy) |

### 🟡 Freemium — free tier with paid tiers above

| Source | Free tier | Paid |
|---|---|---|
| [data.world](https://data.world/product/community/) | 3 private datasets, 100 MB each, 1 GB total | Enterprise governance & limits |
| [OpenAlex](https://openalex.org/) | $1/day of API usage free | Pay-as-you-go, annual plans |
| [OpenCorporates](https://opencorporates.com/) | Free web use for personal/public-benefit work | API & commercial licenses |

### 🔴 Paywall / mixed — payment, contract, or sponsor usually required

| System | Reading | Publishing |
|---|---|---|
| [Socrata](https://dev.socrata.com/consumers/getting-started) | Usually free, SODA/SoQL | Contracted portal only |
| [ArcGIS Hub](https://doc.arcgis.com/en/hub/get-started/introduction-to-hub.htm) | Free for public hubs | Eligible org + permissions |
| [Opendatasoft](https://help.opendatasoft.com/apis/ods-explore-v2/) | Free public APIs | Authorized paid workspace |
| [BigQuery sharing](https://docs.cloud.google.com/bigquery/docs/analytics-hub-introduction) | Varies by listing | Storage/query charges can apply |
| [Dryad](https://datadryad.org/) | Free to read | Publishing charges unless waived/sponsored |

## 🌍 Find data by country

Each link goes to the country's main official open-data portal. Bosnia & Herzegovina is the one gap — no national portal could be verified — and Kenya, Nigeria, South Africa, China, and Russia haven't been verified yet. Per-country detail (APIs, caveats) will live in the subreddit wiki.

### Europe

| Country | Portal |
|---|---|
| Albania | [opendata.gov.al](https://opendata.gov.al/en) |
| Austria | [data.gv.at](https://www.data.gv.at/home?locale=en) |
| Belgium | [data.gov.be](https://data.gov.be/en) |
| Bosnia & Herzegovina | **no verified national portal** |
| Bulgaria | [data.egov.bg](https://data.egov.bg/) |
| Croatia | [data.gov.hr](https://data.gov.hr/) |
| Cyprus | [data.gov.cy](https://www.data.gov.cy/) |
| Czechia | [data.gov.cz](https://data.gov.cz/english) |
| Denmark | [datavejviser.dk](https://www.datavejviser.dk/) |
| Estonia | [andmed.eesti.ee](https://andmed.eesti.ee/) |
| Finland | [avoindata.fi](https://www.avoindata.fi/en) |
| France | [data.gouv.fr](https://www.data.gouv.fr/) |
| Germany | [govdata.de](https://www.govdata.de/) |
| Greece | [data.gov.gr](https://data.gov.gr/) |
| Hungary | [kozadatportal.hu](https://kozadatportal.hu/) |
| Iceland | [island.is (open data)](https://island.is/en/o/digital-iceland/open-data/open-data) |
| Ireland | [data.gov.ie](https://data.gov.ie/) |
| Italy | [dati.gov.it](https://dati.gov.it/) |
| Latvia | [data.gov.lv](https://data.gov.lv/eng) |
| Lithuania | [data.gov.lt](https://data.gov.lt/?lang=en) |
| Luxembourg | [data.public.lu](https://data.public.lu/en/) |
| Malta | [open.data.gov.mt](https://open.data.gov.mt/) |
| Montenegro | [data.gov.me](https://data.gov.me/) |
| Netherlands | [data.overheid.nl](https://data.overheid.nl/en) |
| North Macedonia | [data.gov.mk](https://data.gov.mk/) |
| Norway | [data.norge.no](https://data.norge.no/) |
| Poland | [dane.gov.pl](https://dane.gov.pl/) |
| Portugal | [dados.gov.pt](https://dados.gov.pt/) |
| Romania | [data.gov.ro](https://data.gov.ro/en) |
| Serbia | [data.gov.rs](https://data.gov.rs/) |
| Slovakia | [data.gov.sk](https://data.gov.sk/en) |
| Slovenia | [podatki.gov.si](https://podatki.gov.si/) |
| Spain | [datos.gob.es](https://datos.gob.es/en) |
| Sweden | [dataportal.se](https://www.dataportal.se/en) |
| Switzerland | [opendata.swiss](https://opendata.swiss/en/) |
| Ukraine | [data.gov.ua](https://data.gov.ua/en) |
| United Kingdom | [data.gov.uk](https://www.data.gov.uk/) |

### Americas

| Country | Portal |
|---|---|
| Argentina | [datos.gob.ar](https://datos.gob.ar/) |
| Brazil | [dados.gov.br](https://dados.gov.br/) |
| Canada | [open.canada.ca](https://open.canada.ca/) |
| Chile | [datos.gob.cl](https://datos.gob.cl/) |
| Colombia | [datos.gov.co](https://www.datos.gov.co/) |
| Dominican Republic | [datos.gob.do](https://datos.gob.do/) |
| Ecuador | [datosabiertos.gob.ec](https://www.datosabiertos.gob.ec/) |
| Mexico | [datos.gob.mx](https://datos.gob.mx/es/) |
| Peru | [datosabiertos.gob.pe](https://www.datosabiertos.gob.pe/) |
| United States | [data.gov](https://data.gov/) |
| Uruguay | [catalogodatos.gub.uy](https://catalogodatos.gub.uy/) |

### Asia-Pacific

| Country / jurisdiction | Portal |
|---|---|
| Australia | [data.gov.au](https://data.gov.au/) |
| Hong Kong | [data.gov.hk](https://data.gov.hk/en/) |
| India | [data.gov.in](https://data.gov.in/) |
| Indonesia | [data.go.id](https://data.go.id/) |
| Japan | [data.e-gov.go.jp](https://data.e-gov.go.jp/) |
| Kazakhstan | [data.egov.kz](https://data.egov.kz/) |
| Malaysia | [data.gov.my](https://data.gov.my/) |
| New Zealand | [data.govt.nz](https://data.govt.nz/) |
| Philippines | [data.gov.ph](https://data.gov.ph/) |
| Singapore | [data.gov.sg](https://data.gov.sg/) |
| South Korea | [data.go.kr](https://www.data.go.kr/) |
| Taiwan | [data.gov.tw](https://data.gov.tw/en) |
| Thailand | [data.go.th](https://data.go.th/en/) |
| Uzbekistan | [data.egov.uz](https://data.egov.uz/eng) |

### Middle East & North Africa

| Country | Portal |
|---|---|
| Bahrain | [data.gov.bh](https://www.data.gov.bh/) |
| Israel | [data.gov.il](https://data.gov.il/he) |
| Morocco | [data.gov.ma](https://data.gov.ma/) |
| Qatar | [data.gov.qa](https://www.data.gov.qa/) |
| Saudi Arabia | [open.data.gov.sa](https://open.data.gov.sa/) |
| Tunisia | [data.gov.tn](https://data.gov.tn/) |
| United Arab Emirates | [opendata.fcsc.gov.ae](https://opendata.fcsc.gov.ae/) |

### Sub-Saharan Africa

| Country | Portal |
|---|---|
| Ghana | [data.gov.gh](https://data.gov.gh/) |
| Mauritius | [data.govmu.org](https://data.govmu.org/en/) |

### Broader discovery

[Data Portals](https://www.dataportals.org/) · [Open Data Inception](https://opendatainception.io/) · [Open Data Inventory](https://odin.opendatawatch.com/) · [re3data](https://www.re3data.org/about) · [Google Dataset Search](https://datasetsearch.research.google.com/) · [DataCite Commons](https://commons.datacite.org/) · [OpenAIRE Graph](https://graph.openaire.eu/) — treat directory entries as leads, not proof a portal is official or current.

## 🗂️ Find data by subject

| Subject | Start with |
|---|---|
| Demographics | [World Development Indicators](https://datacatalog.worldbank.org/search/dataset/0037712/world-development-indicators) |
| Boundaries & maps | [geoBoundaries](https://www.geoboundaries.org/) · [OpenStreetMap](https://www.openstreetmap.org/) |
| Elections & law | [IDEA Voter Turnout DB](https://www.idea.int/data-tools/data/voter-turnout-database) · [WorldLII](https://www.worldlii.org/) |
| Procurement & budgets | [OCDS Registry](https://data.open-contracting.org/) · [BOOST](https://www.worldbank.org/en/programs/boost-portal/country-data) |
| Aid & development | [IATI Datastore](https://iatistandard.org/en/iati-tools-and-resources/iati-datastore/) |
| Health | [WHO World Health Data Hub](https://data.who.int/) |
| Climate & environment | [Copernicus CDS](https://cds.climate.copernicus.eu/) |
| Public transport | [Mobility Database](https://mobilitydatabase.org/) |
| Companies & ownership | [OpenCorporates](https://opencorporates.com/) · [Open Ownership datasets](https://www.openownership.org/en/publications/beneficial-ownership-data-analysis-tools/user-guides/) |
| Research & media | [OpenAlex](https://openalex.org/) · [GDELT](https://gdeltproject.org/data.html) |

*No service covers official election results or legislation for every country — confirm with the relevant authority.*

## 👥 Communities

**On Reddit:** [r/CivicAtlas](https://www.reddit.com/r/CivicAtlas/) · [r/opendata](https://www.reddit.com/r/opendata/) · [r/datasets](https://www.reddit.com/r/datasets/)

### Networks & local groups

| Where | Group |
|---|---|
| United States | [Alliance of Civic Technologists](https://www.civictechnologists.org/) — BetaNYC, Chi Hack Night, Civic Tech DC, Code for Boston, Open Austin + more |
| Global | [Code for All](https://codeforall.org/our-global-network) · [Open Knowledge Network](https://okfn.org/network/) |
| Canada · Mexico · LatAm | [Code for Canada](https://codefor.ca/volunteer-2/) · [Codeando México](https://codeandomexico.org/comunidad) · [SocialTIC](https://socialtic.org/quienes-somos/) |
| Taiwan · Japan | [g0v](https://g0v.tw/intl/en/manifesto/en/) · [Code for Japan](https://www.code4japan.org/en/activity/community) |
| Africa | [Civic Tech Innovation Network](https://civictech.africa/bienvenue/) · [openAFRICA](https://www.open.africa/en/about) · [OpenUp](https://openup.org.za/about) |
| UK · Australia | [mySociety](https://www.mysociety.org/about/) · [OpenAustralia Foundation](https://oaf.org.au/about/) |

## 🛠️ What people build from this data

| Kind | Examples |
|---|---|
| Data products | [Open States](https://docs.openstates.org/) · [Council Data Project](https://councildataproject.org/) · [TheyWorkForYou](https://data.mysociety.org/datasets/theyworkforyou-api/) |
| Reusable platforms | [Decidim](https://decidim.org/) · [Polis](https://compdemocracy.org/) · [Alaveteli](https://www.alaveteli.org/about/) · [FixMyStreet](https://fixmystreet.org/) |
| Programs | [Documenters Network](https://www.documenters.org/about/) · [Chi Hack Night projects](https://chihacknight.org/projects) |

## 📤 Where to publish a dataset

| You want… | Use |
|---|---|
| Canonical source + public corrections | [GitHub](https://github.com/) (license, schema, data dictionary, validator, checksums) |
| Archival release + DOI | [Zenodo](https://help.zenodo.org/docs/deposit/); Dataverse / Figshare / OSF if their workflows fit |
| AI & data-tool discovery | [Hugging Face](https://huggingface.co/docs/hub/datasets-adding); add [Kaggle](https://www.kaggle.com/docs/datasets) for notebooks/community |
| Domain repository | Find one via [re3data](https://www.re3data.org/about) before defaulting to a general repo |
| Humanitarian use | [HDX](https://data.humdata.org/) (scope + sensitivity requirements apply) |
| Very large cloud-native data | [AWS Registry of Open Data](https://registry.opendata.aws/) (already hosted on AWS; costs can exist) |
| Official publication | The agency/portal's own publisher process — most don't take public uploads |
| Web discovery | Canonical landing page + [Schema.org Dataset metadata](https://developers.google.com/search/docs/appearance/structured-data/dataset) |
| Live agent access | Stable API or MCP — add it after rights, versioning, and provenance are settled |

## ✏️ Submit or correct a resource

Choose **Resource submission** or **Correction / broken link** flair. Start the title with a code like `[US]`, `[US-AZ]`, `[CA]`, or `[GLOBAL]` / `[MULTI]` / `[EU]`. Then include:

- the operator's official URL + jurisdiction
- what it is: portal, index, repository, API/agent layer, community, or project
- human access, machine/API cost, publishing eligibility, data rights — separately
- API/MCP/bulk docs + how you authenticate
- pricing, license/terms, contribution path
- status, update cadence, and the date you checked it
- your affiliation, if any

Prefer GitHub? You can also open a pull request directly on [yellow-book.md](https://github.com/anitacigawet/civic-atlas/blob/master/yellow-book.md), the markdown source behind this post — no moderator status needed.

---

Maintained with AI assistance · source on [GitHub](https://github.com/anitacigawet/civic-atlas) · links and access details last verified 2026-09-01 · prices and plan limits rechecked 2026-09-03 · spot an error? open a pull request or comment · r/CivicAtlas

# Leabharlann

> *Irish for **library**.*
> A personal, open-source digital library of study materials,
> research reports, language resources, and reference works —
> offered as a resource for students, teachers, researchers, and
> curious readers, and particularly for anyone working in or
> studying the **Goidelic and Brythonic language traditions of
> the British Isles**.
>
> *Fíor-úsáideach don taighdeoir, don mhúinteoir, agus don
> scoláire — ach amháin i gcomhair léamh agus staidéar pearsanta,
> gan aon úsáid tráchtála.*

This repository collects the books, papers, course materials,
and AI-generated research reports that have shaped my own learning
across **mathematics**, **computing**, **education**, the **Irish
language**, and **public-policy analysis**. It exists as a
working-archive behind the
[`cianfhoghlaim`](https://github.com/cianfhoghlaim/cianfhoghlaim)
monorepo — every PDF here can in principle be ingested by a DLT
filesystem source into the per-subject pipeline.

---

## Repository layout

The library is organised into **six top-level directories**, each
scoped to a single domain. Some directories have their own detailed
`README.md` for finer-grained listings.

| Directory | Domain | Contents |
|:--|:--|:--|
| `gaeilge/` | Irish language & Celtic studies | Curated Celtic-studies, Belfast heritage, and Gaelic-culture documents. Has its own detailed README. |
| `aigne/` | Mind, mental health, and reflection | Books and PDFs on trauma, iatrogenic harm, critical reflection, neurogenesis, Buddhism, and digital cognition. |
| `mata/` | Mathematics | Foundational and advanced mathematics textbooks (linear algebra, discrete maths, statistics, ML, etc.). |
| `ollscoil_na_gaillimhe/` | University of Galway coursework | Coursework, assignments, lecture notes, and project work from undergraduate and postgraduate study at Ollscoil na Gaillimhe / University of Galway. |
| `zotero/` | Research papers & reading list | Academic papers — primarily on NLP, OCR, federated learning, and low-resource / Celtic-language technology. |
| `gemini_deep_research/` | AI-assisted research archive | Long-form research reports generated via Gemini Deep Research, organised by topic. Has its own README. |

---

## The six domains

### `gaeilge/` — Irish language & Celtic studies

The flagship subdirectory. Curated PDFs covering:

- **Language learning** — beginner phrasebooks, the *Fáinne*
  proficiency programme (*Silver Fáinne*, *Ór Fháinne*),
  verb-conjugation charts, and phonetics textbooks such as
  *Fuaimeanna na Gaeilge*.
- **Cultural & heritage publications** — West Belfast heritage
  guides, the *Cultúrlann McAdam Ó Fiaich* leaflet and phrasebook,
  the *Gaelic Placenames of Belfast*, and *The Languages of
  Ulster*.
- **Academic research** — Proinsias Mac Cana's *Collège des
  Irlandais Paris*, *Gaeilgeoirí of the Great War*, and *A Gaelic
  History of East Belfast* by Gordon McCoy.
- **Community initiatives** — East Belfast Mission's *Turas*
  materials, *Scoil na Seolta* integrated primary school, and
  Conradh na Gaeilge multilingual booklets.

> See [`gaeilge/README.md`](gaeilge/README.md) for the full catalogue
> with preview thumbnails, organisations referenced, and the
> moral-usage licensing notice.

---

### `aigne/` — Mind, Mental Health & Reflection

A reading collection on the workings of the mind, the harms it can
suffer, and how it recovers. Topics include:

- **Trauma & iatrogenic harm** — *Rebuilding Shattered Lives*,
  *Models of Madness*, and an iatrogenic-trauma reading list.
- **Reflection & professional practice** — *Introduction to
  Critical Reflection and Action for Teacher Researchers*.
- **Cognitive science & digital life** — *The Shallows* (Carr)
  on what the internet is doing to our brains, *Procrastination,
  Health, and Well-Being* (Fuscia, 2016).
- **Philosophy & contemplative practice** — *Buddhism without
  Beliefs* (Batchelor).
- **Neurogenesis & recovery** — a subdirectory of papers and book
  excerpts on adult neurogenesis, peptide therapeutics,
  transcranial stimulation, and adjunctive recovery compounds.

---

### `mata/` — Mathematics

Foundational and reference texts used throughout undergraduate and
postgraduate mathematical study:

- **Linear algebra** — *Linear Algebra Done Right*, *Linear
  Algebra Done Wrong*, *Linear Algebra for Everyone*, and
  Strang's *Introduction to Linear Algebra* (6th ed.).
- **Discrete mathematics** — Epp's *Discrete Mathematics with
  Applications* and the *Applied Discrete Mathematics* text used
  at NUI Galway.
- **Algorithms & data structures** — *The Algorithm Design
  Manual* (Skiena).
- **Statistics & machine learning** — *An Introduction to
  Statistical Learning in Python*, *Probabilistic Machine
  Learning* (Murphy), and *AIAMA*.
- **Computer-science mathematics** — *Mathematics for Machine
  Learning* (mml-book), *Napkin* (Evan Chen), and *Designing
  Data-Intensive Applications* (Kleppmann).
- **Programming & data tooling** — *Fluent Python* (Ramalho)
  and *DuckDB in Action*.

---

### `ollscoil_na_gaillimhe/` — University of Galway coursework

A historical archive of assessed and supporting work from study at
Ollscoil na Gaillimhe (NUI Galway / University of Galway). Organised
by school / programme:

#### `education/` — PME (Professional Master of Education)
- **PGCE / PME materials** — personal statement, CS test, Scratch
  and GeoGebra lesson resources, safeguarding documentation.
- **School placements** — `3bme1_placement/` and
  `4bme1_placement_balefired/` contain teaching-practice records,
  lesson plans, critical-incident reports, opening/closing
  statements, and student-work samples.
- **Action-research project** — `research_project/` holds the
  ED411 literature review, methodology synopsis, results,
  appendices, and the final paper.
- **Stand-alone assignments** — educational autobiography,
  psychology assignments, opening/closing statements,
  critical-incident reflection, problem-based learning, and
  Plickers / Hour-of-Code session plans.

#### `irish/` — Diploma & BA sa Ghaeilge
- **Module folders** — `ga101_ceart_na_gaeilge_1`,
  `ga114_saíocht_na_gaeilge`, `ga201_ceart_na_gaeilge_2`,
  `ga81010_éisteach_agus_labhairt_c1`, `g100_cruinneas_na_gaeilge`,
  `gf101_an_prós_comhaimseartha`, `gf107_an_scríbhneoireacht_acadúil`.
  Each contains the course handbook, unit materials, assessed
  essays, and oral/written exam prep.
- **Top-level assignments** — aistí saíochta, léirmheasanna,
  aistriúcháin, and the C1 syllabus handbook (*Lámhleabhar C1*).

#### `mata/` — BSc Mathematical Science
- **Statistics** — `applied_statistics_1/` and
  `applied_statistics_2/` with R-projects, lecture notes, exam
  papers, and the ST311/ST312 certificates of achievement.
- **Cryptography** — `cs402_cryptography/` contains Koblitz's
  *A Course in Number Theory and Cryptography*, Smart's
  *Cryptography Made Simple*, past exam papers, and coursework
  assignments including the `cs402.py` reference implementation.
- **Other modules** — `ISLP_labs/`, `maple/`, `modelling_2/`,
  `networks/`, `non_linear_systems/`, `numerical_analysis_2/`,
  plus the Stokes Workshop *Game Physics* notes.

#### `software_development/` — Higher Diploma in Software Development
- Module folders for `ct511_databases`, `ct545_enterprise_java_programming`,
  `ct853_algorithmics`, `ct861_computer_architecture_and_operating_systems`,
  `ct870_internet_programming`, `ct874_programming_1`, and
  `software_engineering_1` — each containing assignments, lab work,
  and past exam papers.

#### `past/` — Pre-Galway studies
Earlier undergraduate work (economics, business law, applied
econometrics, constitutional studies) predating transfer to
NUI Galway.

---

### `zotero/` — Research papers & reading list

An export of academic papers organised in a Zotero library. The
collection skews heavily toward:

- **Low-resource & Celtic-language NLP** — gaBERT, UCCIX,
  *Gaeilge Bhriste ó Shamhlacha Cliste*, *Staid Reatha an
  Mheaisínaistriúcháin Gaeilge*, *Adapting Language-Specific
  LLMs to a Reasoning Model in One Day*, and the *Celtic
  Language Technology Workshop (CLTW)* proceedings.
- **OCR & handwritten-text recognition** — Nougat, eScriptorium,
  DANIEL, CogVLM, Vintern, and *Handwritten Text Recognition
  (HTR) for Irish-Language Folklore*.
- **Federated & split learning** — Flower, SplitFed, and
  surveys on security/privacy in federated settings.
- **Multilingual LLMs** — DeepSeekMath, YaRN, multilingual
  pretraining via machine-translated data, and *Beyond
  Vanilla Fine-Tuning* for low-resource MT.
- **Irish-language education & policy** — *The Creation and
  Complexity Analysis of EduGA*, *Irish-BLiMP*, and the
  *Using GenAI in Teaching, Learning and Assessment in Irish
  Universities* report.
- **Other** — feature selection for spam/phishing detection,
  *Gramadóir* documentation, and several conference proceedings
  (LREC, *Computational Approaches to Celtic Languages*).

A `MANIFEST.tsv` accompanies the directory with metadata.

---

### `gemini_deep_research/` — AI-assisted research archive

Long-form research reports generated through
[Gemini Deep Research](https://gemini.google.com), organised
topically:

| Subdirectory | Focus |
|:--|:--|
| `culture/` | Celtic digital revitalisation, shared British-Isles culture, heritage and genealogy. |
| `law/` | Cross-border civil cases, discrimination claims, medical malpractice, dual-citizenship jurisprudence, GDPR / Subject Access Requests. |
| `medical/` | TBI / c-PTSD recovery, medical-cannabis access across the CTA, sodium-valproate inquiry, disability-allowance processes. |
| `politics/` | Irish & UK electoral analysis, Brexit, political accountability inquiries, consociationalism. |
| `technology/` | AI regulation, big-tech oversight, federated learning for project optimisation, UK intelligence careers. |
| `other/` | British-Isles tech/culture strategy, surrogacy, urban-services investigations. |

> See [`gemini_deep_research/README.md`](gemini_deep_research/README.md)
> for the methodology behind these reports and the official
> Gemini documentation references.

---

## How this corpus feeds the monorepo

Every PDF in `leabharlann/` can in principle be ingested by a DLT
`filesystem_source` in
[`cianfhoghlaim/dlt/filesystem/`](https://github.com/cianfhoghlaim/cianfhoghlaim/tree/main/cianfhoghlaim/dlt/filesystem)
and routed into the per-subject Dagster pipeline via the
`DLT_LOAD_PATH` env var. The convention is:

- A DLT filesystem source can pin to a specific domain subdirectory
  (`gaeilge/`, `mata/`, `zotero/`, …) via the `DLT_PATH_FILTER` env
- The pipeline then runs the corpus through the canonical
  `pdf_processing_*` asset (BAML extraction → CocoIndex embedding
  → Cognee cognify → marimo dashboard)
- The embeddings land in the per-subject LanceDB table
  (`oideachais.<subject>.embeddings`)

The `gaeilge/` corpus is the priority target — it's what powers the
Gaeilge-side quest-pack generation for `qpack_gaeilge.baml`.

---

## Conventions

- **File names** generally preserve the original title, with some
  folders using Irish-language titles where appropriate (e.g.
  `gaeilge/a_gaelic_history_of_east_belfast_mccoy.pdf`).
- **Each top-level directory** that has its own detailed catalogue
  (`gaeilge/`, `gemini_deep_research/`) contains a dedicated
  `README.md` — start there for finer-grained listings.
- **Moral-usage licensing** — all resources are intended for
  **research, educational, and personal-study use only**. See
  `gaeilge/README.md` for the moral-usage licensing notice that
  applies to those Celtic-studies materials.
- **No re-distribution** — the materials here are a personal
  collection; please respect the original publishers' terms.

---

## About the maintainer

I am a registered politician with [Fine Gael](https://www.finegael.ie)
and [Alliance Party](https://www.allianceparty.org), a Newly
Qualified Teacher (Mathematics / Applied Mathematics) on the
[Teaching Council of Ireland](https://my-tc.teachingcouncil.ie)
register, and a dual Irish-British citizen. This library is the
working collection behind my teaching, research, and policy work
— and is shared in the hope that it might be useful to others
walking similar paths.

Sláinte, agus leabharlann mhaith duit.

---

## Related repos

- [**cianfhoghlaim/cianfhoghlaim**](https://github.com/cianfhoghlaim/cianfhoghlaim)
  — the application monorepo that consumes this corpus
  (per-subject DLT pipelines + BAML quest packs + 8 NCCA subject
  agents + the Cianfhoghlaim Educational MMO)
- [**cianfhoghlaim/bonneagar**](https://github.com/cianfhoghlaim/bonneagar)
  — the infrastructure GitOps layer (90+ Compose stacks, Komodo
  procedures, Pangolin routes, the Locket secrets sidecar)

---

## License

BUSL-1.1 — see [`LICENSE`](../LICENSE).

Source-available; not an Open Source licence. The corpus is for
**personal study and research use only**. Moral-usage applies to
the Celtic-studies materials in particular. Re-distribution is
not authorised without written consent of the original
publishers.

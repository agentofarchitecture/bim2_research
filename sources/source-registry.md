# Source Registry

Last updated: 2026-05-26.

## Promoted sources

### buildingSMART IDS GitHub repository

- url: https://github.com/buildingSMART/IDS
- type: repo / standard implementation
- platform: GitHub
- entities: [buildingSMART, IDS, IFC, openBIM]
- topics: [Information Delivery Specification, BIM requirements, validation, XML]
- first_seen: 2026-05-23
- last_checked: 2026-05-23
- last_useful_signal: 2026-05-23
- score: 91
- status: promoted
- why_it_matters: Computer-interpretable IDS is becoming the contract/test layer for BIM deliverables; repo has active updates and identifiable contributors.
- best_use: Track IDS schema changes, examples, implementers, and people graph.
- links_out_to: [https://www.buildingsmart.org/standards/bsi-standards/information-delivery-specification-ids/]
- linked_from: [daily/2026-05-23.md]
- notes: GitHub API snapshot: 297 stars, updated 2026-05-22; top contributors include Claudio Benghi, Léon van Berlo, Artur Tomczak, Dion Moult.

### IfcOpenShell repository

- url: https://github.com/IfcOpenShell/IfcOpenShell
- type: repo / open-source library
- platform: GitHub
- entities: [IfcOpenShell, Bonsai, IFC, openBIM]
- topics: [IFC, geometry engine, BlenderBIM/Bonsai, open-source BIM]
- first_seen: 2026-05-23
- last_checked: 2026-05-23
- last_useful_signal: 2026-05-23
- score: 93
- status: promoted
- why_it_matters: Probably the most important inspectable open-source implementation layer for IFC-based BIM.
- best_use: Implementation patterns for IFC parsing, checking, geometry, and non-Revit workflows.
- links_out_to: [https://github.com/Moult, https://github.com/aothms]
- linked_from: [daily/2026-05-23.md]
- notes: GitHub API snapshot: 2,531 stars, updated 2026-05-22; top contributors include Dion Moult, Andrej730, Thomas Krijnen.

### Speckle Server

- url: https://github.com/specklesystems/speckle-server
- type: repo / product infrastructure
- platform: GitHub
- entities: [Speckle]
- topics: [AEC data platform, web viewer, connectors, project data]
- first_seen: 2026-05-23
- last_checked: 2026-05-23
- last_useful_signal: 2026-05-23
- score: 86
- status: promoted
- why_it_matters: Speckle is a leading data bridge between authoring tools and web/project data surfaces; server changes indicate AI-ready data direction.
- best_use: Track project memory/data layer and people around Speckle.
- links_out_to: [https://speckle.systems/blog/, https://github.com/didimitrie]
- linked_from: [daily/2026-05-23.md]
- notes: GitHub API snapshot: 813 stars, updated 2026-05-22.

### speckle-sharp

- url: https://github.com/specklesystems/speckle-sharp
- type: repo / connectors SDK
- platform: GitHub
- entities: [Speckle, Rhino, Grasshopper, Revit]
- topics: [connectors, Revit, Rhino, Grasshopper, Dynamo, interoperability]
- first_seen: 2026-05-23
- last_checked: 2026-05-23
- last_useful_signal: 2026-05-23
- score: 84
- status: promoted
- why_it_matters: Directly overlaps with Rhino/Grasshopper/Revit connector workflows relevant to Rhino Mind.
- best_use: Connector architecture and property-transfer patterns.
- links_out_to: [https://github.com/teocomi, https://github.com/AlanRynne]
- linked_from: [daily/2026-05-23.md]
- notes: GitHub API snapshot: 424 stars, updated 2026-05-15.

### COMPAS

- url: https://github.com/compas-dev/compas
- type: repo / computational design framework
- platform: GitHub
- entities: [COMPAS, Rhino, Grasshopper, Blender]
- topics: [computational design, geometry, CAD integrations]
- first_seen: 2026-05-23
- last_checked: 2026-05-23
- last_useful_signal: 2026-05-23
- score: 78
- status: promoted
- why_it_matters: Mature open computational design infrastructure with Rhino/GH integration.
- best_use: Rhino Mind geometry/tooling patterns.
- links_out_to: [https://github.com/tomvanmele]
- linked_from: [daily/2026-05-23.md]
- notes: GitHub API snapshot: 365 stars, updated 2026-05-18.

### That Open engine components

- url: https://github.com/ThatOpen/engine_components
- type: repo / open AEC web components
- platform: GitHub
- entities: [That Open Company, openBIM]
- topics: [web BIM, components, viewers, open AEC tooling]
- first_seen: 2026-05-23
- last_checked: 2026-05-23
- last_useful_signal: 2026-05-23
- score: 80
- status: promoted
- why_it_matters: Active open tooling from architect-developers; useful for web/openBIM interaction surfaces.
- best_use: Web component UX and openBIM developer ecosystem tracking.
- links_out_to: [https://github.com/agviegas]
- linked_from: [daily/2026-05-23.md]
- notes: GitHub API snapshot: 654 stars, updated 2026-05-19.

## Candidate sources

### Ishigaki-IDS-Bench paper

- url: https://arxiv.org/abs/2605.22079v1
- type: paper / benchmark
- platform: arXiv
- entities: [IDS, LLM, BIM requirements]
- topics: [IDS generation, benchmark, XML, BIM information requirements]
- first_seen: 2026-05-23
- last_checked: 2026-05-23
- score: 74
- status: candidate
- why_it_matters: Fresh evidence that IDS is an LLM target format.
- best_use: Design IDS-lite benchmark/task for Rhino Mind.
- notes: Need full paper/code/dataset check.

### IFC Whisperer paper

- url: DOI 10.1088/1742-6596/3140/16/162007
- type: paper
- platform: Semantic Scholar / conference journal
- entities: [IFC, knowledge graphs, LLM]
- topics: [BIM querying, IFC-based knowledge graphs, natural language]
- first_seen: 2026-05-23
- last_checked: 2026-05-23
- score: 70
- status: candidate
- why_it_matters: Directly matches the semantic project memory thesis.
- best_use: Investigate graph schema/query patterns.
- notes: Semantic Scholar citation count was 0 at query time; verify full text.

### Modular Reference Architecture for MCP-Servers Enabling Agentic BIM Interaction

- url: https://arxiv.org/abs/2601.00809
- type: paper / agent architecture
- platform: arXiv / Semantic Scholar
- entities: [MCP, BIM agents, IFC, LLM, tool adapters]
- topics: [agentic BIM interaction, MCP servers, reusable BIM adapters, evaluation]
- first_seen: 2026-05-23
- last_checked: 2026-05-23
- score: 82
- status: promoted
- why_it_matters: Directly relevant to Rhino Mind architecture because it separates MCP/tool-calling interfaces from authoring-tool-specific BIM APIs.
- best_use: Blueprint for a Rhino/Speckle/IFC adapter contract and benchmark.
- notes: arXiv `2601.00809v2`; authors Tobias Heimig-Elschner, Changyu Du, Anna Scheuvens, André Borrmann, Jakob Beetz. Semantic Scholar query returned 0 citations and 15 references at check time.

### BIM Information Extraction Through LLM-based Adaptive Exploration

- url: https://arxiv.org/abs/2605.01698
- type: paper / agentic extraction method
- platform: arXiv
- entities: [IFC, BIM, LLM, adaptive exploration, ifc-bench]
- topics: [information extraction, heterogeneous BIM, runtime structure discovery]
- first_seen: 2026-05-23
- last_checked: 2026-05-23
- score: 79
- status: promoted
- why_it_matters: Strong pattern for messy real models: agents should discover local structure before answering or checking.
- best_use: Design the Rhino Mind “inspect-before-answer” / model dialect mapper.
- notes: arXiv `2605.01698v1`; lead author Sylvain Hellin; co-author André Borrmann.

### buildingSMART bSDD repository

- url: https://github.com/buildingSMART/bSDD
- type: repo / standard implementation
- platform: GitHub
- entities: [buildingSMART, bSDD, classification, openBIM]
- topics: [buildingSMART Data Dictionary, shared vocabulary, classifications, property semantics]
- first_seen: 2026-05-23
- last_checked: 2026-05-23
- score: 84
- status: promoted
- why_it_matters: bSDD is the vocabulary layer that can make IDS/checks and model properties less office-specific.
- best_use: Track people and examples around semantic classification for Rhino/Speckle metadata.
- notes: GitHub API snapshot: top contributors include Artur Tomczak, Baars-IT/Erik, Klaus Aengenvoort, Léon van Berlo.

### buildingSMART ifcJSON repository

- url: https://github.com/buildingSMART/ifcJSON
- type: repo / standard-adjacent implementation
- platform: GitHub
- entities: [buildingSMART, IFC, JSON, linked building data]
- topics: [IFC serialization, web data, BIM exchange]
- first_seen: 2026-05-23
- last_checked: 2026-05-23
- score: 72
- status: candidate
- why_it_matters: Possible bridge between IFC schemas and web/agent-readable data formats.
- best_use: Track Jan Brouwer and Pieter Pauwels connection to graph/web-readable BIM.
- notes: GitHub API snapshot: top contributors include Jan Brouwer and Pieter Pauwels.

### McNeel RhinoMCP

- url: https://github.com/mcneel/RhinoMCP
- type: repo / Rhino agent interface
- platform: GitHub
- entities: [McNeel, Rhino, MCP, agentic CAD]
- topics: [Model Context Protocol, Rhino automation, agent tool use, CAD editing]
- first_seen: 2026-05-24
- last_checked: 2026-05-24
- last_useful_signal: 2026-05-24
- score: 86
- status: promoted
- why_it_matters: Official McNeel-hosted MCP server/package path for agents to create and edit Rhino; closest current public substrate for Rhino Mind execution primitives.
- best_use: Track Rhino-side primitive design and benchmark against Rhino Mind semantic-check workflows.
- links_out_to: [https://github.com/clicky, https://github.com/stevefuchs]
- linked_from: [daily/2026-05-24.md]
- notes: GitHub API snapshot: 83 stars, updated 2026-05-22, MIT license; top contributors Callum Sykes/clicky and Steve Fuchs.

### MCP4IFC paper and repo

- url: https://arxiv.org/abs/2511.05533v1 ; https://github.com/Show2Instruct/mcp4ifc
- type: paper / repo / IFC agent framework
- platform: arXiv + GitHub
- entities: [MCP4IFC, IFC, MCP, LLM, University of Rostock]
- topics: [IFC manipulation, scene querying, RAG code generation, agentic BIM]
- first_seen: 2026-05-24
- last_checked: 2026-05-24
- last_useful_signal: 2026-05-24
- score: 80
- status: promoted
- why_it_matters: Connects Model Context Protocol with open IFC data manipulation, giving a schema-first counterpart to RhinoMCP environment control.
- best_use: Compare geometry-first and IFC-first agent workflows on the same tiny BIM task.
- links_out_to: [https://github.com/nbharathik, https://github.com/ashwin-ned]
- linked_from: [daily/2026-05-24.md]
- notes: arXiv authors include Bharathi Kannan Nithyanantham, Tobias Sesterhenn, Ashwin Nedungadi, Sergio Peral Garijo, Janis Zenkner, Christian Bartelt, Stefan Lüdtke. Repo has low stars, so treat as early implementation probe.

### buildingSMART BCF-API

- url: https://github.com/buildingSMART/BCF-API
- type: repo / standard implementation
- platform: GitHub
- entities: [buildingSMART, BCF, OpenCDE]
- topics: [BIM Collaboration Format, issue exchange, model coordination API]
- first_seen: 2026-05-24
- last_checked: 2026-05-24
- last_useful_signal: 2026-05-24
- score: 78
- status: promoted
- why_it_matters: Active web service specification for BIM issue/context exchange; Rhino Mind check findings should eventually become reviewable coordination issues.
- best_use: Design BCF-lite output objects for QA/compliance findings.
- links_out_to: [https://github.com/GeorgDangl]
- linked_from: [daily/2026-05-24.md]
- notes: GitHub API snapshot: 230 stars, updated 2026-05-15; top contributors Georg Dangl and `linhard`.

### bSDD MCP server

- url: https://github.com/JardiMargalefAgusti/bSDD-mcp
- type: repo / vocabulary MCP server
- platform: GitHub
- entities: [bSDD, buildingSMART Data Dictionary, MCP]
- topics: [classification lookup, property lookup, BIM enrichment]
- first_seen: 2026-05-24
- last_checked: 2026-05-24
- score: 65
- status: candidate
- why_it_matters: Tiny but strategically clear example of exposing bSDD as an AI-agent tool.
- best_use: Pattern for a Rhino/Speckle classification assistant.
- notes: Low stars; promote only if adoption or stronger implementation details appear.

### bSDD-Toolkit

- url: https://github.com/c-mellueh/bSDD-Toolkit
- type: repo / bSDD editor and Python toolkit
- platform: GitHub
- entities: [bSDD, buildingSMART Data Dictionary]
- topics: [dictionary authoring, validation, Pydantic, PySide6 GUI]
- first_seen: 2026-05-24
- last_checked: 2026-05-24
- score: 68
- status: candidate
- why_it_matters: Makes vocabulary/dictionary work concrete and editable, which is necessary if office/project semantics are to be maintained.
- best_use: Study UI/data-model ideas for small project vocabularies.
- notes: Updated 2026-05-21; MIT license; one-person implementation.

## Blocked / weak sources

- Generic vendor “AI designs whole buildings” pages without API, examples, implementation detail, or human-checkable outputs are not promoted.

### IfcLLM / Hybrid IFC Querying paper

- url: https://arxiv.org/abs/2605.13236
- type: paper / IFC querying framework
- platform: arXiv / Semantic Scholar
- entities: [IFC, IfcLLM, knowledge graph, relational representation, LLM]
- topics: [natural language BIM querying, IFC, graph representation, relational data, retry-and-refine reasoning]
- first_seen: 2026-05-24
- last_checked: 2026-05-24
- last_useful_signal: 2026-05-24
- score: 80
- status: promoted
- why_it_matters: Strong source for project-memory architecture because it avoids forcing IFC into a single representation; graph handles topology, relational data handles properties/geometry.
- best_use: Blueprint for Rhino/Speckle memory indexes and question routing.
- links_out_to: [https://arxiv.org/abs/2605.13236]
- linked_from: [daily/2026-05-24.md]
- notes: Authors Rabindra Lamsal, Sisi Zlatanova, Haowen Xu, Yafei Sun, Johnson Xuesong Shen. Semantic Scholar check on 2026-05-24 showed 0 citations; abstract reports 93.3–100% first-attempt accuracy on 30 scenarios / three IFC models.

### Ishigaki-IDS-Bench repository

- url: https://github.com/onestruction/Ishigaki-IDS-Bench
- type: repo / benchmark dataset
- platform: GitHub
- entities: [IDS, buildingSMART, LLM, BIM requirements]
- topics: [IDS XML generation, BIM information requirements, benchmarks]
- first_seen: 2026-05-24
- last_checked: 2026-05-24
- last_useful_signal: 2026-05-24
- score: 76
- status: promoted
- why_it_matters: Converts the earlier Ishigaki-IDS-Bench paper from a paper-only lead into an inspectable artifact for testing brief/requirements → IDS generation.
- best_use: Seed a Rhino Mind IDS-lite benchmark and compare generated check packs against buildingSMART IDS XML.
- links_out_to: [https://arxiv.org/abs/2605.22079v1]
- linked_from: [daily/2026-05-24.md]
- notes: GitHub API snapshot: `onestruction/Ishigaki-IDS-Bench`, 1 star, updated 2026-05-24, default branch `main`.


### ArchiTech Network / ATN YouTube channel

- url: https://www.youtube.com/channel/UCrLHBCOz211YirQRg2QVJvA
- type: YouTube channel / interview graph
- platform: YouTube
- entities: [ArchiTech Network, ATN, Oliver Thomas, Olly Thomas, BIM 2.0, architecture technology]
- topics: [BIM 2.0 companies, architecture technology, practice workflows, founder interviews, workshops]
- first_seen: 2026-05-24
- last_checked: 2026-05-24
- last_useful_signal: 2026-05-24
- score: 88
- status: promoted
- why_it_matters: Dense public source graph for BIM 2.0 companies and people; Luke specifically flagged ATN/Oliver as a required grounding source.
- best_use: Start every company/person landscape pass by checking ATN interviews and workshops, then verify claims against company primary sources.
- links_out_to: [https://www.youtube.com/watch?v=dturff3XgSk, https://www.youtube.com/watch?v=pwXN4CZ_nR8]
- linked_from: [sources/youtube-atn-grounding.md, daily/2026-05-24.md]
- notes: Transcript extraction was blocked by YouTube cloud-IP protections during 2026-05-24 pass; use metadata plus follow-on primary-source verification until transcript access is solved.


### BIM 2.0 company source cluster — ATN + AEC Magazine + primary product pages

- url: sources/bim2-company-sources-2026-05-24.md
- type: source cluster / company landscape evidence map
- platform: repo synthesis + web sources
- entities: [BIM 2.0, ATN, AEC Magazine, Snaptrude, Arcol, Motif, Qonic, Hypar, Skema, Speckle]
- topics: [BIM 2.0 companies, Rebuilding BIM, agentic BIM, next-generation AEC software]
- first_seen: 2026-05-24
- last_checked: 2026-05-24
- last_useful_signal: 2026-05-24
- score: 87
- status: promoted
- why_it_matters: Consolidates the strongest public company list sources into one reusable evidence map: ATN's BIM 2.0 overview/interview graph, AEC Magazine's independent BIM 2.0/Rebuilding BIM coverage, and primary company pages/docs/GitHub.
- best_use: Start company landscape updates here before broad search; separate core BIM 2.0 authoring companies from adjacent AI/design/data/infrastructure companies.
- links_out_to: [https://www.youtube.com/watch?v=dturff3XgSk, https://aecmag.com/bim/defining-bim-2-0/, https://aecmag.com/bim/the-agentic-future-of-bim/]
- linked_from: [maps/company-landscape.md, daily/2026-05-24.md]
- notes: Strongest direct BIM 2.0 authoring companies identified in this pass are Snaptrude, Arcol, Motif, and Qonic. Broader relevant set includes Hypar, Skema, Finch, Speckle, That Open Company, RunChat, Giraffe, TestFit, Augmenta, SWAPP, Higharc, Illoca, Codesign, qbiq, Pirros and others.

### RunChat Rhino / Grasshopper docs

- url: https://docs.runchat.com/plugins/rhino
- type: product docs / Rhino-GH AI workflow source
- platform: web docs
- entities: [RunChat, Rhino, Grasshopper, McNeel, AI agents]
- topics: [Rhino scripting, Grasshopper agents, design agents, visual AI canvas, in-authoring automation]
- first_seen: 2026-05-24
- last_checked: 2026-05-24
- last_useful_signal: 2026-05-24
- score: 82
- status: promoted
- why_it_matters: Direct primary-source comparator for Rhino Mind; documents an AI workflow canvas and agent surface inside Rhino/GH, including screenshots/geometry transfer, Rhino Python generation, and Grasshopper canvas actions.
- best_use: Feature-diff against Rhino Mind and identify where semantic project memory/checking can differentiate.
- links_out_to: [https://docs.runchat.com/llms.txt, https://blog.rhino3d.com/2026/03/runchat-online-workshop-april-21-23.html, https://gwyllim.substack.com/p/runchat-in-rhino, https://www.youtube.com/watch?v=PPqDz4H2bmg]
- linked_from: [sources/youtube-atn-grounding.md, maps/company-landscape.md, daily/2026-05-24.md]
- notes: YouTube transcript for ATN RunChat episode was blocked from VPS, but product docs and McNeel Europe post were reachable.

### Hypar Elements

- url: https://github.com/hypar-io/Elements
- type: repo / computational BIM library
- platform: GitHub
- entities: [Hypar, Elements, Ian Keough, Andrew Heumann, BIM automation]
- topics: [smallest useful BIM, computational design, building elements, Revit-compatible automation]
- first_seen: 2026-05-25
- last_checked: 2026-05-25
- last_useful_signal: 2026-05-25
- score: 83
- status: promoted
- why_it_matters: Primary implementation artifact for Hypar’s “smallest useful BIM” thesis; active repo with top contributors Ian Keough and Andrew Heumann.
- best_use: Study how building automation can be packaged as composable elements/functions rather than a full authoring platform.
- links_out_to: [https://hypar.io/, https://github.com/ikeough, https://github.com/andrewheumann]
- linked_from: [daily/2026-05-25.md, people/top-100.md]
- notes: GitHub API snapshot: 398 stars, 79 forks, pushed 2026-05-25; description “The smallest useful BIM.”

### Raven primary-source cluster

- url: https://www.raven.build/ ; https://discourse.mcneel.com/t/raven-can-now-use-plugins-grasshopper-ai-interface/208628 ; https://www.youtube.com/watch?v=n8j1abP6CV8
- type: product site / forum / YouTube episode
- platform: web + McNeel Discourse + YouTube
- entities: [Raven, Rhino, Grasshopper, ArchiTech Network, ATN]
- topics: [Grasshopper AI, intent-to-definition, CAD intelligence layer, native editable parametric graphs]
- first_seen: 2026-05-25
- last_checked: 2026-05-25
- last_useful_signal: 2026-05-25
- score: 76
- status: promoted as comparator source; people node remains candidate until identity is verified
- why_it_matters: Direct Rhino/GH AI comparator that claims to turn natural-language intent into precise editable Grasshopper definitions; sharpens the tooling-on-demand map.
- best_use: Compare with RunChat, RhinoMCP, and Rhino Mind’s semantic sidecar thesis.
- links_out_to: [https://www.raven.build/, https://discourse.mcneel.com/t/raven-can-now-use-plugins-grasshopper-ai-interface/208628]
- linked_from: [sources/youtube-atn-grounding.md, daily/2026-05-25.md]
- notes: ATN video transcript blocked by YouTube cloud-IP protections; Food4Rhino page appeared in search but returned HTTP 405 from this VPS.

### ATN x AECTech x Heatherwick Hackathon

- url: https://www.youtube.com/watch?v=C22ZP9XfwiM
- type: YouTube / event metadata / prototype graph
- platform: YouTube Atom RSS + ATN
- entities: [ArchiTech Network, AECTech, Heatherwick Studio, Motif, ShapeDiver, BIM 2.0, computational design]
- topics: [hackathon, prototypes, AI for AEC, BIM 2.0, automation, future of practice]
- first_seen: 2026-05-25
- last_checked: 2026-05-26
- last_useful_signal: 2026-05-26
- score: 78
- status: promoted as source-discovery node
- why_it_matters: ATN’s newest feed item is a dense event/prototype source: 26-hour hackathon hosted at Heatherwick with AECTech and Motif, explicitly around AI, BIM 2.0, computational design and automation.
- best_use: Mine for people, teams, prototype names and practical workflow pain; do not treat as proof of product maturity until artifacts are found.
- links_out_to: [https://www.youtube.com/channel/UCrLHBCOz211YirQRg2QVJvA, https://www.shapediver.com]
- linked_from: [sources/youtube-atn-grounding.md, daily/2026-05-26.md]
- notes: Transcript extraction blocked by YouTube cloud-IP protections; feed description was available and is enough to promote as a source-discovery node.

### Spacio.ai primary source cluster

- url: https://www.spacio.ai ; https://www.spacio.ai/about
- type: product site / company grounding
- platform: web
- entities: [Spacio.ai, André Agi, Franz Forsberg, Stian Haugrim, Rhino, IFC]
- topics: [early-phase design, compliance, BIM export, Rhino interoperability, feasibility]
- first_seen: 2026-05-24
- last_checked: 2026-05-26
- last_useful_signal: 2026-05-26
- score: 76
- status: candidate / strengthened verification
- why_it_matters: Moves Spacio from ATN-listed name to verified product/company node with specific claims: real-time compliance, simulations, automatic drawings, BIM export, Rhino/IFC interoperability and named founding team.
- best_use: Comparator for early design compliance + BIM-ready handoff workflows.
- linked_from: [maps/company-landscape.md, daily/2026-05-26.md]
- notes: Still verify export quality, supported jurisdictions, and technical docs before treating as implementation-equivalent to repo-backed sources.

### Qonic primary site

- url: https://qonic.com
- type: product site / cloud BIM platform
- platform: web
- entities: [Qonic, cloud BIM, Revit]
- topics: [cloud BIM modelling, data fields, collaboration, construction BIM, information management]
- first_seen: 2026-05-24
- last_checked: 2026-05-26
- last_useful_signal: 2026-05-26
- score: 74
- status: candidate / strengthened verification
- why_it_matters: Primary site grounds Qonic as a cloud-based BIM modelling platform with designer/constructor/information-manager workflows, Revit downloads, developer hub, release notes and model data-field regulation messaging.
- best_use: Handoff/platform benchmark for Rhino Mind structured export packages.
- linked_from: [maps/company-landscape.md, daily/2026-05-26.md]
- notes: Needs deeper docs/developer hub inspection and independent user/practice evidence.

### NonicaTab / Nonica primary site

- url: https://nonica.io
- type: product site / Revit AI connector
- platform: web
- entities: [Nonica, NonicaTab, Jaime Alonso, Blanca Serrano, Revit, Claude, Anthropic]
- topics: [Revit AI connector, Revit API, model modification, parameter editing, documentation]
- first_seen: 2026-05-24
- last_checked: 2026-05-26
- last_useful_signal: 2026-05-26
- score: 75
- status: candidate / strengthened verification
- why_it_matters: Concrete Revit-side comparator for authoring-app AI actions: read, report, edit parameters and document the live model through a plugin layer.
- best_use: Study guardrails, permissions, and UX patterns for Rhino Mind’s own in-authoring actions.
- linked_from: [maps/company-landscape.md, daily/2026-05-26.md]
- notes: Needs deeper docs/examples to assess reliability and provenance.

# Source Registry

Last updated: 2026-05-23.

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

## Blocked / weak sources

- Generic vendor “AI designs whole buildings” pages without API, examples, implementation detail, or human-checkable outputs are not promoted.

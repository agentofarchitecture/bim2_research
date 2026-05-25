# Mental Model Notes for Top BIM 2.0 People

Status: rough extraction layer. Last updated: 2026-05-25.

Use this file to add idea/mental-model notes before rewriting the formal Top 100 ranking. These notes are intentionally sharper than normal bios.

## Current extracted models

### Dion Moult — OpenBIM as civic/inspectable infrastructure

- **Core model:** BIM should be open, inspectable, scriptable, auditable, and usable without proprietary lock-in.
- **Artifact trail:** IfcOpenShell, Bonsai, ThinkMoult writing, open-source IFC practice.
- **Why important:** This is the strongest antidote to treating BIM as a sealed vendor file. It makes BIM data agent-readable and hacker-friendly.
- **Limit / blind spot:** Open tooling can still be hard for ordinary architectural offices unless wrapped in workflows and interfaces.
- **Rhino Mind implication:** Build on inspectable project data and expose tools as understandable actions, not black-box magic.
- **New model seed:** *Open BIM as agent substrate* — agents need open data surfaces before they can reason reliably.

### Claudio Benghi — Requirements as checkable contracts

- **Core model:** BIM requirements should be formal enough to be exchanged, tested, and automated.
- **Artifact trail:** buildingSMART IDS contributions and related openBIM work.
- **Why important:** IDS shifts BIM from “please model this properly” to machine-checkable delivery requirements.
- **Limit / blind spot:** Formal requirements can become bureaucratic if not connected to real design tasks.
- **Rhino Mind implication:** Convert briefs and practice standards into small, phase-specific check packs.
- **New model seed:** *Brief-to-check loop* — transform design intent into checkable semantic requirements.

### Léon van Berlo — OpenBIM governance as ecosystem alignment

- **Core model:** BIM 2.0 needs shared standards and coordination mechanisms, not just better apps.
- **Artifact trail:** buildingSMART and IDS ecosystem work.
- **Why important:** Shared standards are the social contract that let many tools interoperate.
- **Limit / blind spot:** Governance can move slower than product/practice pain.
- **Rhino Mind implication:** Track standards as future affordances, but prototype faster around practical workflows.
- **New model seed:** *Standards as latent APIs* — standards become useful when agents can read/write/check them in context.

### Thomas Krijnen — Geometry and IFC as computable reality

- **Core model:** BIM interoperability depends on precise geometry/data implementation, not slogans.
- **Artifact trail:** IfcOpenShell and IFC/geometry implementation work.
- **Why important:** Agentic BIM fails if the geometry/data layer is unreliable.
- **Limit / blind spot:** Deep implementation detail needs product translation for architects.
- **Rhino Mind implication:** Treat geometry operations and IFC parsing as infrastructure beneath higher-level project intelligence.
- **New model seed:** *Reasoning needs geometry truth* — semantic AI has to stay grounded in model geometry.

### Dimitrie Stefanescu — AEC models as web-native data streams

- **Core model:** Design data should move between tools and the web as live, queryable, collaborative streams.
- **Artifact trail:** Speckle.
- **Why important:** Speckle points toward BIM as data infrastructure, not just authoring software.
- **Limit / blind spot:** Data movement alone does not create meaning; the next layer is semantic/contextual intelligence.
- **Rhino Mind implication:** Use connectors/data streams as the substrate for contextual memory and tool recall.
- **New model seed:** *Streams plus semantics* — project data becomes useful when connected to decisions, requirements, and tools.

### Matteo Cominetti — Connector-first BIM interoperability

- **Core model:** Practical BIM 2.0 happens at connector boundaries between tools architects already use.
- **Artifact trail:** Speckle connector work, speckle-sharp.
- **Why important:** Connectors are where adoption friction is won or lost.
- **Limit / blind spot:** Connectors can move data without solving “what should I do now?”
- **Rhino Mind implication:** Rhino Mind should live close to Rhino/Grasshopper/Speckle context rather than as a detached chat UI.
- **New model seed:** *Context travels through connectors* — connectors should carry semantic intent, not just geometry.

### Antonio González Viegas — Open web components for BIM interfaces

- **Core model:** BIM interfaces can be assembled from open, web-native components.
- **Artifact trail:** That Open Company / That Open Engine components.
- **Why important:** Web-based components make BIM data more accessible for custom tools and lightweight workflows.
- **Limit / blind spot:** Components need strong workflow opinions to become product value.
- **Rhino Mind implication:** Rhino Mind could surface BIM/project intelligence through small custom UI components rather than monolithic apps.
- **New model seed:** *BIM UI as composable components*.

### Tom Van Mele — Computational design as reusable research infrastructure

- **Core model:** Advanced design computation needs shared, reusable, language-neutral infrastructure.
- **Artifact trail:** COMPAS.
- **Why important:** Rhino/Grasshopper-adjacent computational tools show how research-grade geometry can reach practice.
- **Limit / blind spot:** Frameworks can be powerful but require expertise.
- **Rhino Mind implication:** Package computational patterns into tool-on-demand actions for architects.
- **New model seed:** *Research frameworks become situated tools*.

### Chris Mackey — Analysis tools embedded in design habits

- **Core model:** Environmental analysis succeeds when embedded directly in Rhino/Grasshopper design workflows.
- **Artifact trail:** Ladybug Tools.
- **Why important:** Shows how non-BIM specialist tools can become practice-grade by fitting existing habits.
- **Limit / blind spot:** Analysis workflows still require interpretation and responsibility.
- **Rhino Mind implication:** Build BIM 2.0 intelligence into the places architects already think and model.
- **New model seed:** *Adoption follows habitat* — tools win by living where design already happens.

### Ryan Schultz — Open-source BIM through practice reality

- **Core model:** Open BIM must survive actual architectural delivery constraints, not only technical purity.
- **Artifact trail:** OpeningDesign, IfcOpenShell contribution/practice links.
- **Why important:** Provides a practitioner reality check for open-source BIM.
- **Limit / blind spot:** Practice-specific lessons may not generalize to every office.
- **Rhino Mind implication:** Test every “BIM 2.0” idea against small-office friction: liability, deadlines, coordination, documentation.
- **New model seed:** *Practice friction as product compass*.

### André Borrmann — Agentic BIM as reproducible research infrastructure

- **Core model:** BIM agents should be evaluated through explicit architectures, benchmarks, and repeatable interaction patterns, not one-off demos.
- **Artifact trail:** `2601.00809` MCP-server reference architecture; `2605.01698` adaptive BIM information extraction; `2506.07217` BIMgent; `2505.07396` TUM2TWIN.
- **Why important:** This cluster turns “AI for BIM” into testable infrastructure: adapters, datasets, benchmarks, and bounded tasks.
- **Limit / blind spot:** Academic architectures can underweight messy office constraints, legacy CAD habits, and commercial deployment friction.
- **Rhino Mind implication:** Define a small reproducible benchmark for Rhino/Speckle agents: inspect model, extract facts, run checks, patch metadata, report uncertainty.
- **New model seed:** *Benchmark-first agentic BIM* — before selling a copilot, define the repeatable tasks and evidence traces that prove it works.

### Jakob Beetz — Semantic BIM as linked, computable knowledge

- **Core model:** BIM becomes more powerful when it is connected to semantic web / linked data structures rather than trapped inside authoring files.
- **Artifact trail:** High-citation semantic BIM publication footprint; co-author on `2601.00809`; Semantic Scholar author search returned a strong J. Beetz profile with 115 papers, 2,933 citations, h-index 25.
- **Why important:** Provides the deeper intellectual lineage behind project knowledge graphs and agent-readable building data.
- **Limit / blind spot:** Linked-data approaches can become too abstract unless wrapped in immediate practice workflows.
- **Rhino Mind implication:** Use graph thinking selectively: connect Rhino objects to decisions, requirements, and previous details only where it produces immediate retrieval/checking value.
- **New model seed:** *Local linked data* — build tiny project graphs around live tasks before attempting a whole-building ontology.

### Pieter Pauwels — Linked Building Data as BIM’s web layer

- **Core model:** Building information should be graph-readable and web-addressable so it can interoperate beyond a single model file or vendor platform.
- **Artifact trail:** Semantic Scholar author search returned a high-impact P. Pauwels profile with 209 papers, 5,979 citations, h-index 39; GitHub profile lists Eindhoven University of Technology; contributor to buildingSMART/ifcJSON.
- **Why important:** Strong source for the “project memory as knowledge graph” family and for understanding where IFC/JSON/RDF/linked-data ideas meet practice.
- **Limit / blind spot:** Semantic richness can overshoot what small architectural teams will maintain manually.
- **Rhino Mind implication:** Generate and maintain semantics as a side effect of useful actions, not as a separate data-management chore.
- **New model seed:** *Semantics by doing* — Rhino Mind should add graph metadata when architects ask questions, run checks, or reuse details.

### Tobias Heimig-Elschner — Adapter contracts for BIM agents

- **Core model:** MCP can become the stable tool-calling boundary, but BIM needs API-agnostic adapter contracts beneath it.
- **Artifact trail:** Lead author on `2601.00809`, “A Modular Reference Architecture for MCP-Servers Enabling Agentic BIM Interaction.”
- **Why important:** Directly informs how Rhino Mind should avoid hard-coding every workflow into a single Rhino plugin or a single model server.
- **Limit / blind spot:** Fresh paper; implementation maturity and code availability still need verification.
- **Rhino Mind implication:** Sketch a `rhino_mcp_adapter` contract with primitives such as list objects, inspect properties, select context, run check, create geometry, patch metadata, export evidence.
- **New model seed:** *One agent, many adapters* — the agent should reason over stable task primitives while adapters translate into Rhino, Speckle, IFC, or Revit.

### Sylvain Hellin — Adaptive exploration of heterogeneous BIM data

- **Core model:** Because BIM models are heterogeneous, agents should explore the actual structure of a model at runtime instead of assuming a fixed schema.
- **Artifact trail:** Lead author on `2605.01698`, “BIM Information Extraction Through LLM-based Adaptive Exploration.”
- **Why important:** This is a practical antidote to brittle natural-language-to-query demos that fail as soon as office/model conventions differ.
- **Limit / blind spot:** Agentic code execution must be sandboxed and auditable; exploration can be slow or nondeterministic.
- **Rhino Mind implication:** Add an “inspect before answer” step for Rhino Mind: map layers, blocks, object names, user text, Speckle properties, then answer with provenance.
- **New model seed:** *Explore-then-check* — every model QA agent first learns the local project dialect before applying rules.

### Callum Sykes — Rhino as an agent-operable design environment

- **Core model:** Rhino can become a live endpoint for AI agents through explicit MCP tools, not only a human-operated modelling UI.
- **Artifact trail:** Primary contributor to `mcneel/RhinoMCP`; GitHub API snapshot showed 226 contributions; profile lists McNeel affiliation.
- **Why important:** This is the closest current public artifact to Rhino Mind’s execution surface. It makes agent primitives concrete: start/connect to Rhino, create/edit objects, and expose a package-manager installation path.
- **Limit / blind spot:** Raw control of Rhino can produce impressive demos without solving semantic intent, project memory, compliance, liability, or office-standard issues.
- **Rhino Mind implication:** Treat RhinoMCP as a possible substrate/benchmark, then build the differentiated semantic sidecar: inspect, classify, check, explain, and create evidence.
- **New model seed:** *Environment control is necessary but not sufficient* — Rhino Mind should not compete on “agent can make a box”; it should compete on “agent knows what this object means and what must be checked next.”

### Bharathi Kannan Nithyanantham — IFC manipulation through agent tool protocols

- **Core model:** LLMs can operate on standardized IFC data through MCP tools that query scenes, create/modify common elements, and use RAG/code generation for task-specific operations.
- **Artifact trail:** Lead author of arXiv `2511.05533v1`, “MCP4IFC: IFC-Based Building Design Using Large Language Models”; contributor to `Show2Instruct/mcp4ifc`.
- **Why important:** This is the IFC-side mirror of RhinoMCP. It asks whether agents should manipulate the semantic exchange model rather than only an authoring UI.
- **Limit / blind spot:** Fresh paper/repo with low visible adoption; robustness on messy practice models needs testing.
- **Rhino Mind implication:** Run the same benchmark through RhinoMCP and MCP4IFC: inspect model, classify object, patch a property, export evidence. Learn which layer is best for each task.
- **New model seed:** *Geometry-first vs schema-first agents* — the best Rhino Mind workflow may use Rhino for situated design actions and IFC/Speckle for semantic validation.

### Georg Dangl — BIM collaboration as structured issue/context exchange

- **Core model:** Collaboration around BIM needs web-service specifications and structured issue/context objects, not just model file exchange.
- **Artifact trail:** Top contributor to `buildingSMART/BCF-API`; profile links to Dangl IT.
- **Why important:** If Rhino Mind checks find problems, the output needs to enter a coordination workflow. BCF/OpenCDE-style APIs are a path from “AI finding” to assignable review item.
- **Limit / blind spot:** BCF/OpenCDE infrastructure can be too heavy for small Rhino-led practices unless wrapped as a simple “issue card” workflow.
- **Rhino Mind implication:** Define BCF-lite output now: finding title, element reference, viewpoint, rule, severity, suggested fix, status, provenance.
- **New model seed:** *Checks become conversations* — model QA is useful when each finding becomes a shareable, trackable, evidence-backed coordination object.

### Ian Keough — Smallest useful BIM as productized functions

- **Core model:** BIM can be decomposed into reusable software elements/functions rather than delivered only through monolithic authoring tools.
- **Artifact trail:** Hypar; `hypar-io/Elements` (“The smallest useful BIM”); ATN EP64 with Andrew Heumann.
- **Why important:** Gives Rhino Mind a product architecture precedent: small, composable BIM atoms can create value around existing workflows.
- **Limit / blind spot:** Developer-friendly function platforms still need practice-friendly interfaces and trust/evidence layers.
- **Rhino Mind implication:** Build semantic actions as tiny functions/check packs that can be invoked in context inside Rhino/GH.
- **New model seed:** *Composable BIM atoms*.

### Andrew Heumann — Computational design patterns as reusable product workflows

- **Core model:** Advanced computational design should become repeatable workflows that ordinary teams can run, inspect, and adapt.
- **Artifact trail:** Hypar; `hypar-io/Elements`; public computational design work; ATN EP64.
- **Why important:** Bridges Grasshopper-style design computation with deployable building automation.
- **Limit / blind spot:** Productizing computation can lose the situated judgement and craft of a specific studio unless outputs stay editable and explainable.
- **Rhino Mind implication:** Translate office scripts/components into context-aware tools with provenance rather than one-off generated code.
- **New model seed:** *From GH craft to reusable semantic tools*.

### Moritz / Raven — Intent becomes an editable Grasshopper graph

- **Core model:** AI should generate native parametric components/definitions from intent, keeping outputs inside Grasshopper instead of burying logic in opaque code.
- **Artifact trail:** Raven website; McNeel Discourse Raven plugin post; ATN E11 `n8j1abP6CV8`.
- **Why important:** Directly validates the “tooling-on-demand in Rhino/GH” habitat.
- **Limit / blind spot:** Raven’s visible claim stops at CAD/GH intelligence; BIM 2.0 needs semantics, requirements, collaboration, and audit trails.
- **Rhino Mind implication:** Treat editable GH generation as table stakes and add semantic sidecar responsibilities: classify, check, remember, explain, export evidence.
- **New model seed:** *Editable automation + semantic contract*.

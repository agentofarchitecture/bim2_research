# BIM 2.0 Meta Map

This file should be updated by the daily loop as patterns emerge.

## 1. From model files to semantic project memory

BIM 1.x centred on coordinated model authoring and deliverable production. BIM 2.0 likely centres on the project as a living, queryable memory graph:

- geometry
- elements/systems
- constraints
- decisions
- drawings
- specs
- costs
- carbon
- regulations
- construction feedback
- precedents and reusable details

## 2. From tools you open to tools that appear

Authoring tools become environments where contextual tools surface or are generated based on what the user is doing.

This directly overlaps with Rhino Mind:

- detect current modelling/documentation intent
- retrieve relevant scripts/components/details/checkers
- spawn an agent to adapt or build a tool
- return a small UI action, not a general chatbot answer

## 3. From coordination checking to continuous reasoning

Clash detection is a narrow version of the future pattern: continuous project reasoning.

Future checks:

- compliance
- planning constraints
- fire/accessibility
- embodied carbon
- cost deltas
- fabrication feasibility
- scope gaps
- drawing/model divergence
- design intent drift

## 4. From generic AI chat to domain agents

The useful agent is not “ChatGPT for architecture” but a domain-bound worker with:

- project context
- tool permissions
- CAD/BIM API access
- firm standards
- precedent memory
- bounded tasks
- verifiable output

## 5. From BIM schemas to deliverable contracts

IFC describes exchangeable building information, but BIM 2.0 needs a sharper contract layer: what information is required, when, by whom, using which vocabulary, and how it is checked.

Emerging stack:

- **IFC** as interoperable object/system data
- **IDS** as machine-checkable information delivery requirements
- **bSDD** as shared vocabulary / classification semantics
- **project memory / GraphRAG** as the evidence and decision layer around the model

Strategic implication: agents should not free-form “do BIM”. They should generate, interpret, and execute small requirement/check packs with audit trails.

## 6. People graph as strategic infrastructure

The BIM 2.0 field is not organised around one dominant software vendor. The useful map is a graph of standards authors, open-source implementers, connector builders, research benchmark authors, and practice critics.

Current high-signal clusters:

- **IDS / buildingSMART contributors**: define the requirement/check contract layer.
- **IfcOpenShell / Bonsai implementers**: show how IFC can be made inspectable and scriptable outside closed BIM stacks.
- **Speckle connector/server builders**: bridge authoring tools into project data surfaces.
- **Rhino/Grasshopper analysis/tool builders**: prove adoption happens when tools sit inside existing design habits.
- **LLM + BIM researchers**: provide benchmarks, but need filtering for real implementability.

Strategic implication: Rhino Mind should learn from people who have made structured building data usable in hostile real-world authoring environments, not only from AI product demos.

## 7. From people lists to mental-model maps

The Top 100 people project is not about influence for its own sake. People are source nodes for ways of thinking:

- what they think BIM is becoming;
- what artifacts prove or operationalize that belief;
- what assumptions or blind spots their model contains;
- what can be borrowed, challenged, or recombined for Rhino Mind.

The research loop should convert people into models, and models into experiments.

Emerging synthesis:

- **People graph as model graph:** map people by the ideas they carry, not just by company or follower count.
- **Artifact-backed thinking:** only trust a model when it leaves traces in papers, repos, standards, tools, talks, or practice workflows.
- **New model generation:** each daily pass should ask what new mental model Luke can use that did not exist before the research.

## 8. Open questions

- What is the smallest useful BIM 2.0 wedge for Rhino users?
- Where are architects currently wasting time because project context is not machine-readable?
- Which checks/tools can be built without needing full Revit/BIM adoption?
- What can be done with Rhino + Grasshopper + Speckle + LLM agents now?
- What should remain human and craft-led?

## 9. Agentic BIM needs adapters, benchmarks, and local dialect discovery

Today’s strongest new cluster is around agentic BIM research: MCP-server reference architecture, adaptive BIM information extraction, BIM computer-use agents, and digital-twin benchmarks. The useful meta-shift is from “chatbot talks to BIM” toward a stack:

- stable task primitives / MCP-like interface;
- tool-specific adapters for Rhino, Speckle, IFC, Revit, Bonsai, and web viewers;
- local model-dialect discovery before checks are applied;
- repeatable benchmark tasks and evidence traces.

Strategic implication: Rhino Mind should not begin as a general architectural copilot. It should begin as a reproducible agent harness for a few small tasks: inspect context, discover metadata conventions, run a check pack, patch a small piece of model data, and produce an auditable report.

## 10. MCP is the socket; semantics are the product

The 2026-05-24 run connected four implementation channels: McNeel `RhinoMCP`, MCP4IFC, bSDD MCP/toolkits, and buildingSMART BCF-API. This suggests a stack for Rhino Mind:

- **Environment adapter:** RhinoMCP-style control of Rhino objects, layers, commands, viewport, and user text.
- **Semantic adapter:** IFC/Speckle/bSDD/IDS-lite interpretation of what objects mean and which properties/checks apply.
- **Collaboration adapter:** BCF/OpenCDE-style issue/context exchange for turning findings into reviewable coordination tasks.
- **Evidence adapter:** provenance over every action/check so agents remain auditable.

Strategic implication: do not build Rhino Mind as a raw “AI controls Rhino” demo. Use MCP as the socket and differentiate with semantic project intelligence: classify, check, explain, and produce shareable evidence.

## 10. Two-lens project memory

The IfcLLM / hybrid IFC querying signal strengthens the idea that BIM 2.0 project memory should not force all information into one representation. A useful stack may need at least two synchronized lenses:

- **relational lens:** objects, properties, quantities, layers, materials, geometry summaries;
- **graph lens:** containment, adjacency, systems, dependencies, provenance, requirement links.

Strategic implication: Rhino Mind’s first memory prototype should avoid “just vectorize the model.” Start with an object/property table plus a relationship graph, then expose which lens produced an answer.

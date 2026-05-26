# BIM 2.0 Mental Models and Idea Sources

Status: living synthesis. Last updated: 2026-05-26.

This file is the real reason the people map exists.

The goal is not simply to rank famous BIM people. The goal is to use people as **source nodes for ideas**: who has a distinct way of seeing the future of BIM, what mental model they are working from, why that model matters, and what new models Luke / Agents of Architecture / Rhino Mind can synthesize from the research.

## How to read people as idea sources

For each important person, extract:

1. **Core lens** — what do they seem to believe BIM/AEC software is becoming?
2. **Operating model** — how do they turn that belief into tools, standards, research, or practice?
3. **Artifact trail** — what papers, repos, specs, talks, products, or posts embody the model?
4. **Contradictions / limits** — where might their model fail in real architectural practice?
5. **Transferable pattern** — what can Rhino Mind borrow or adapt?
6. **New model seed** — what new way of thinking emerges when this person is connected to others?

## Candidate mental-model schema

```yaml
person:
role_or_org:
model_name:
one_sentence_model:
source_evidence:
  - url / paper / repo / talk
key_concepts:
  - concept
important_because:
limits_or_blind_spots:
connections:
  people:
  tools:
  standards:
  ideas:
what_rhino_mind_can_do_with_it:
new_model_seed:
confidence: low | medium | high
```

## Initial model families to look for

### 1. OpenBIM as inspectable infrastructure

The model is not a proprietary authoring file; it is an inspectable, scriptable, testable information substrate.

Signals:
- IfcOpenShell / Bonsai / That Open Company / buildingSMART implementation work.
- People who make IFC, IDS, bSDD, and geometry operations practical for developers.

Rhino Mind implication:
- Treat project information as a substrate that agents can query, patch, validate, and explain, not as a sealed BIM database.

### 2. BIM requirements as executable contracts

The future of BIM coordination is not just richer models but machine-checkable requirements and delivery contracts.

Signals:
- IDS, bSDD, model validation, automated compliance, brief-to-requirement generation.

Rhino Mind implication:
- Agents should generate and run small “requirement/check packs” tied to project phase, not offer vague BIM advice.

### 3. Project memory as a knowledge graph

A project is a living memory: geometry plus decisions, constraints, precedents, specs, costs, risks, and unresolved questions.

Signals:
- Semantic BIM, IFC knowledge graphs, GraphRAG, LLM querying over project data.

Rhino Mind implication:
- Build a memory layer that lets architects ask: “where did we solve this before?”, “what changed?”, “what does this element know?”, and “what tool should appear now?”

### 4. Tooling-on-demand

Software stops being a fixed menu of commands. Tools appear, adapt, or are generated when the user’s intent/context is recognized.

Signals:
- Speckle connectors, Grasshopper/Rhino automation, agentic CAD/BIM workflows, computational design practitioners.

Rhino Mind implication:
- Detect the live design/documentation task, retrieve a reusable tool/script/detail/checker, then let an agent adapt it.

### 5. BIM without monolithic BIM adoption

Small practices may get BIM 2.0 benefits without fully adopting heavy enterprise BIM authoring workflows.

Signals:
- Lightweight model QA, open-source BIM, Rhino/Grasshopper/Speckle pipelines, practical critiques of Revit-heavy workflows.

Rhino Mind implication:
- Make semantic/project-intelligence tools that work with messy partial models, Rhino geometry, notes, drawings, and precedents.

### 6. Verification-first AI for AEC

AEC AI must produce verifiable, bounded, auditable outputs rather than magical end-to-end design claims.

Signals:
- compliance checking, code checking, IDS generation, geometry validation, traceable agent actions.

Rhino Mind implication:
- Prefer bounded assistants with evidence trails: “I checked these objects against this rule and here is the uncertainty,” not “AI designed a building.”

## New mental models synthesized by this research

### Contextual tool ecology

Instead of imagining Rhino Mind as one assistant, imagine it as an ecology of small tools, checks, scripts, details, and memories that become visible when context makes them relevant.

### Semantic minimum viable BIM

For small practices, BIM 2.0 may start with the smallest useful semantic layer around existing workflows: named elements, project decisions, reusable details, phase requirements, and checkable constraints — not a perfect all-discipline model.

### People graph as model graph

A person matters when they carry a useful model of the future. The Top 100 should therefore track not only influence, but the **distinct mental model** each person contributes.

### Benchmark-first agentic BIM

The Borrmann/TUM cluster suggests a useful discipline: define repeatable BIM-agent tasks, datasets, adapters, and evidence traces before making broad copilot claims. For Rhino Mind this means a small benchmark could matter more than a flashy demo: given a messy Rhino/Speckle model, inspect it, extract facts, run an IDS-lite check, patch metadata, and produce a provenance report.

### One agent, many BIM adapters

The MCP-server reference-architecture paper points to a separation Luke should preserve: the agent reasons over stable task primitives, while adapters translate those primitives into Rhino, Speckle, IFC, Revit, or web BIM tools. This keeps Rhino Mind from becoming a bundle of brittle one-off automations.

### Explore-then-check

The adaptive BIM extraction paper suggests that model QA agents should first learn the local project dialect — layers, blocks, names, user text, Speckle fields, IFC property sets — before applying requirements. This is especially relevant for small practices with inconsistent, partial, or Rhino-heavy models.



### MCP is the socket; semantics are the product

The 2026-05-24 pass connected McNeel `RhinoMCP`, MCP4IFC, bSDD-MCP, and BCF-API. The synthesis: MCP gives agents a standard way to call tools, but the product value is the AEC-specific semantic layer above those calls.

Rhino Mind implication:

- Let environment adapters handle raw control: create geometry, select objects, read user text, capture viewport.
- Add semantic adapters: classify elements, map to bSDD/office vocabularies, generate IDS-lite checks, inspect Speckle/IFC properties.
- Add collaboration/evidence adapters: turn findings into reviewable BCF-lite issues with provenance.

New model seed: *Agent socket + semantic sidecar* — use MCP as the transport layer, but differentiate through checkable project intelligence.

## Daily loop requirements

Every people-hunt pass should add or update:

- at least one person → mental model mapping;
- at least one evidence artifact for that model;
- one limitation/blind spot;
- one implication for Rhino Mind / AoA;
- one possible new synthesized model, even if rough.

### Hybrid representation project memory

IfcLLM adds a useful model family: do not search for a single perfect BIM representation. Convert the same model into multiple complementary views and let the agent pick or combine them.

- **Person/source:** Rabindra Lamsal et al., “A Hybrid Framework for Natural Language Querying of IFC Models with Relational and Graph Representations.”
- **Core lens:** BIM querying improves when properties/geometry live in a relational view and topology/relationships live in a graph view.
- **Why it matters:** Rhino/Speckle project memory has the same problem as IFC: objects have table-like attributes and graph-like relationships. One vector store or one database will probably be brittle.
- **Limit/blind spot:** The paper is fresh and needs code/dataset verification; IFC models may be cleaner than messy Rhino practice models.
- **Rhino Mind implication:** Build memory indexes in pairs: object/property table + relationship graph + retrieval trace. Make the “which view answered this?” explicit in the UI.
- **New model seed:** **Two-lens project memory** — every answer should say whether it came from object facts, relationship topology, precedent memory, or a combination.


### Canvas agent inside the design environment

RunChat’s Rhino/GH docs and McNeel Europe workshop signal a practical adoption pattern: architects may accept AI sooner when it appears as a **canvas/workflow agent inside tools they already use**, not as a separate BIM platform.

- **Person/source:** Gwyllim Jahn / James Pazzi / RunChat docs and McNeel Europe workshop.
- **Core lens:** AI can act on screenshots, geometry, scripts, and Grasshopper canvases from inside the live design environment.
- **Why it matters:** This is close to Rhino Mind’s territory. It validates that Rhino/GH users want AI help at the scripting/component/workflow level.
- **Limit/blind spot:** Canvas agents can become clever automation surfaces without understanding project semantics, office standards, requirement intent, or evidence/provenance.
- **Rhino Mind implication:** Rhino Mind should borrow the in-environment adoption pattern but add the missing semantic sidecar: project memory, local dialect discovery, IDS-lite checks, and auditable findings.
- **New model seed:** **Canvas + semantic sidecar** — let the canvas/agent operate tools, but let the sidecar decide what the model means, what standards apply, and what evidence should be recorded.

### Smallest useful BIM / composable building functions

Hypar’s ATN interview node plus the live `hypar-io/Elements` repo sharpen a model that is highly relevant to Rhino Mind: BIM value can be decomposed into reusable building elements/functions, rather than requiring users to enter a monolithic authoring system.

- **People/source:** Ian Keough and Andrew Heumann / Hypar / `hypar-io/Elements`.
- **Core lens:** Building design automation should be made of composable, code-backed elements and workflows — “the smallest useful BIM” — rather than one all-encompassing BIM application.
- **Why it matters:** This matches small-practice/Rhino reality better than full-platform replacement. It suggests Rhino Mind can create value through small semantic/tooling units that sit on top of existing work.
- **Limit/blind spot:** Function platforms can still feel developer-led; architects need situated UI, examples, and trust that outputs match project intent.
- **Rhino Mind implication:** Package semantic actions as small tools/checks: classify selected elements, attach required properties, generate one Grasshopper definition, run one IDS-lite check, export one issue card.
- **New model seed:** **Composable BIM atoms** — build BIM 2.0 as many small verified atoms of meaning/action, not as one giant model migration.

### Intent-to-definition as tooling-on-demand

Raven adds a narrower but important mental model to the RunChat/RhinoMCP cluster.

- **Person/source:** Moritz / Raven, pending full-name verification; Raven website and McNeel Discourse.
- **Core lens:** A useful AI design assistant should turn natural-language intent into native, editable Grasshopper definitions/components rather than black-box code.
- **Why it matters:** This is close to Rhino Mind’s “tools appear when needed” thesis, because the output lives in the designer’s existing parametric habitat.
- **Limit/blind spot:** Intent-to-definition does not yet equal BIM 2.0; it needs project semantics, office standards, requirements, provenance, and handoff intelligence.
- **Rhino Mind implication:** Treat editable GH generation as a baseline capability; differentiate by using the generated definition as part of an auditable semantic workflow.
- **New model seed:** **Editable automation + semantic contract** — the graph/tool must remain editable, while Rhino Mind maintains the meaning, constraints, and evidence around it.

### Event graph as prototype radar

ATN’s newest hackathon signal suggests another way to read the BIM 2.0 people map: events are not merely marketing moments; they are compressed evidence environments where builders reveal what they can prototype quickly and what workflow pains generate energy.

- **Person/source:** Oliver / Olly Thomas and ArchiTech Network, especially `C22ZP9XfwiM` ATN x AECTech x Heatherwick Hackathon.
- **Core lens:** BIM 2.0 is shaped through a community/event graph as much as through papers and product pages.
- **Evidence:** ATN hackathon description names architects, designers, developers, engineers and technologists building prototypes in 26 hours around AI, BIM 2.0, computational design, automation, visualisation and future practice; collaboration with AECTech and Motif; ShapeDiver tag.
- **Why important:** This can surface high-agency practitioners and prototype ideas before they become startups, repos, or polished product pages.
- **Limits/blind spots:** Hackathons over-reward demos and under-test reliability, liability, data maintenance, and office adoption.
- **Rhino Mind action seed:** create a “prototype radar” pass: for every ATN/AECTech/hackathon event, extract teams, prototype names, tools used, problem statements, and follow-up artifacts; classify which could become Rhino Mind atoms.

### Early design compliance handoff

Spacio adds a product mental model: early design tools should validate feasibility/compliance while preserving a path into BIM and existing authoring tools.

- **People/source:** André Agi, Franz Forsberg, Stian Haugrim / Spacio.ai.
- **Core lens:** architects need fast early-phase design feedback across code, daylight, unit mix, KPIs, and site constraints before moving into detailed BIM.
- **Evidence:** Spacio primary site claims real-time compliance, automatic drawing generation, BIM export, and interoperability with Rhino/IFC/DXF/OBJ/Excel plus downstream Revit/ArchiCAD.
- **Why important:** This is exactly where Rhino-heavy practices lose information: early design decisions are made before the model has enough structure for later BIM/compliance workflows.
- **Limits/blind spots:** jurisdiction-specific code packs and export fidelity are hard; “BIM-ready” needs downstream verification.
- **Rhino Mind action seed:** build a Rhino/GH “pre-BIM handoff report” that extracts model assumptions, zoning/compliance unknowns, metadata gaps, and export readiness before a model goes to Speckle/Revit/Qonic/Snaptrude.

### Authoring-app AI connector with guardrails

NonicaTab strengthens the model that natural language can become bounded tool actions inside a heavyweight BIM app.

- **Person/source:** Jaime Alonso / NonicaTab.
- **Core lens:** the immediate user value of AEC AI is not a standalone chatbot; it is a controlled connector that can read, report, edit parameters, and document the live model.
- **Evidence:** Nonica primary site claims Claude can read, report, modify parameters, and document Revit models through NonicaTab PRO / AI Connector.
- **Why important:** This is the Revit analogue to RhinoMCP/RunChat/Rhino Mind and shows where user trust questions will appear first: what can the agent change, how is it checked, and what evidence remains?
- **Limits/blind spots:** Revit-only and tool/plugin centric; visible site evidence does not yet show the depth of provenance or semantic validation.
- **Rhino Mind action seed:** define a permission model for Rhino Mind actions: inspect-only, suggest script, edit metadata, edit geometry, generate documentation, with an evidence card for each action.

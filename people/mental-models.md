# BIM 2.0 Mental Models and Idea Sources

Status: living synthesis. Last updated: 2026-05-24.

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

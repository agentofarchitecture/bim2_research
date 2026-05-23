# BIM 2.0 Mental Models and Idea Sources

Status: living synthesis. Last updated: 2026-05-23.

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

## Daily loop requirements

Every people-hunt pass should add or update:

- at least one person → mental model mapping;
- at least one evidence artifact for that model;
- one limitation/blind spot;
- one implication for Rhino Mind / AoA;
- one possible new synthesized model, even if rough.

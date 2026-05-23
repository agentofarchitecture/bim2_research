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

## 6. Open questions

- What is the smallest useful BIM 2.0 wedge for Rhino users?
- Where are architects currently wasting time because project context is not machine-readable?
- Which checks/tools can be built without needing full Revit/BIM adoption?
- What can be done with Rhino + Grasshopper + Speckle + LLM agents now?
- What should remain human and craft-led?

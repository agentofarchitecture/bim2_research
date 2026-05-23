# Mental Model Notes for Top BIM 2.0 People

Status: rough extraction layer. Last updated: 2026-05-23.

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

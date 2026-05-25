# BIM 2.0 Player Differentiation Map

Last updated: 2026-05-24.

Purpose: answer Luke's question: **where is BIM 2 going, and what sets each major player apart?**

This map separates companies by the workflow they are trying to own. BIM 2.0 is not a single replacement for Revit; it is fragmenting into layers: web authoring, AI feasibility, workflow compression, data infrastructure, compliance/knowledge, and authoring-tool agents.

## Executive thesis: where BIM 2 is going

BIM 2.0 is moving from **model-authoring software** toward **project intelligence systems**:

1. **From files to live data graphs** — models become queryable object/property/relationship databases, not just RVT/IFC files.
2. **From manual modelling to agent-assisted workflows** — AI agents generate options, modify models, check requirements, and retrieve firm knowledge.
3. **From one monolithic BIM tool to workflow layers** — feasibility, authoring, review, detailing, compliance, data exchange, and construction intelligence split into specialized tools.
4. **From geometry to semantics** — the winners will not merely draw faster; they will know what objects mean, what rules apply, and what evidence proves compliance.
5. **From deliverables to continuous checking** — IDS, bSDD, IFC, BCF, Speckle-like streams, and project memory make BIM a continuous reasoning/checking system.
6. **From generic AI chat to tool-operating agents** — chat is the interface; the value is adapters, permissions, schemas, benchmarks, and auditable outputs.

For Rhino Mind, the signal is clear: do not compete as “another BIM platform.” The stronger wedge is **semantic sidecar for Rhino/Grasshopper + open BIM**: understand messy design context, retrieve firm tools/standards, enrich geometry, run checks, and publish evidence into Speckle/IFC/Revit/BIM2 platforms.

## Core BIM 2.0 authoring competitors

### Snaptrude

- **Wedge:** AI-powered browser/cloud BIM for concept-to-schematic design.
- **What sets it apart:** strongest explicit AI-native BIM positioning among the core authoring challengers; moving from brief/RFP/site into program, massing, floor plans and schematic BIM in one live model.
- **Workflow it wants to own:** brief/site/program → options → schematic BIM → Revit/Rhino/export handoff.
- **Evidence:** https://www.snaptrude.com/ ; https://help.snaptrude.com/en/ ; https://aecmag.com/bim/rebuilding-bim-snaptrude/ ; https://aecmag.com/bim/snaptrude-ai-conceptual-design-and-beyond/
- **Integrations:** Revit import/export; Rhino import/export; Archicad/CAD/PDF/SketchUp workflows in help docs.
- **Adoption friction:** downstream trust: Revit fidelity, firm data permissions, schematic-model reliability, and whether architects will shift early design out of Rhino/SketchUp.
- **Rhino Mind implication:** Snaptrude threatens generic “AI early design.” Rhino Mind should instead own Rhino-side model cleanup, semantic enrichment, firm-specific workflows, and handoff into Snaptrude/Revit/IFC.

### Arcol

- **Wedge:** web-native collaborative architectural design, “Figma for AEC” evolving toward constructible design intelligence.
- **What sets it apart:** collaboration-first philosophy; browser-native multiplayer authoring, feasibility, boards, metrics and presentation in one environment.
- **Workflow it wants to own:** collaborative concept/massing/feasibility → design metrics → boards/presentation → downstream export.
- **Evidence:** https://arcol.io/ ; https://help.arcol.io/ ; https://aecmag.com/bim/arcol-unleashed-bim-2-0/ ; https://aecmag.com/bim/rebuilding-bim-arcol/
- **Integrations:** import image/3D/DWG/DXF; export Revit/SketchUp/Excel; Rhino integration appears in help docs.
- **Adoption friction:** crowded early design category; must prove constructibility and data depth beyond nice multiplayer UX.
- **Rhino Mind implication:** do not out-Figma Arcol. Rhino Mind can prepare/generate/audit Rhino/GH options before they enter collaborative BIM environments.

### Motif

- **Wedge:** intelligent browser workspace for design review, live model streaming, sheets, comments, AI visualisation.
- **What sets it apart:** strongest founder/team credibility from former Autodesk/Revit/AutoCAD leadership; V1 is not full authoring but a serious review/collaboration layer.
- **Workflow it wants to own:** review and alignment around live design content: Revit/Rhino/Grasshopper/Dynamo/Enscape assets, comments, markups, AI visuals.
- **Evidence:** https://www.motif.io/ ; https://help.motif.io/ ; https://aecmag.com/bim/rebuilding-bim-motif/ ; https://aecmag.com/bim/motif-v1-our-first-thoughts/
- **Integrations:** Revit, Rhino, Grasshopper, Dynamo, Enscape plugins/integrations.
- **Adoption friction:** broad remit; must replace or beat Miro + Bluebeam + Revizto + ACC + Enscape workflows.
- **Rhino Mind implication:** Motif validates cross-tool design workspaces. Rhino Mind should be the action/authoring intelligence that executes fixes and generates options inside Rhino/GH, then publishes to Motif-like review layers.

### Qonic

- **Wedge:** cloud BIM modelling and model-data enrichment with construction/detail/lifecycle orientation.
- **What sets it apart:** most explicit database/component/model-data thesis among the core group; focuses on solid modelling, model enrichment, quantity takeoff, APIs and lifecycle data.
- **Workflow it wants to own:** enrich/correct/coordinate BIM models → QTO/reporting/data governance → construction and owner workflows.
- **Evidence:** https://www.qonic.com/ ; https://help.qonic.com/ ; https://api-docs.qonic.com/ ; https://aecmag.com/bim/rebuilding-bim-qonic/
- **Integrations:** Revit export add-in; desktop/mobile/web clients; API reads/writes model data; AEC coverage notes Rhino/SketchUp import, Revit import/export and IFC support.
- **Adoption friction:** heavier data-platform trust problem; round-trip fidelity, versioning, permissions and BIM-manager acceptance matter.
- **Rhino Mind implication:** Qonic shows BIM2 may be won by data granularity and APIs. Rhino Mind can prepare Rhino geometry as structured categories, assemblies, materials, quantities and IFC/Qonic-ready metadata.

## Automation / AI-to-BIM / workflow-compression players

### Hypar

- **Wedge:** computational building design automation, functions and Revit-compatible generative workflows.
- **What sets it apart:** API/function-driven design automation rather than “new Revit UI”; strongest platform logic for reusable building-design functions.
- **Evidence:** https://hypar.io/ ; https://docs.hypar.io/ ; https://github.com/hypar-io ; https://aecmag.com/ai/hypar-text-to-bim-and-beyond/
- **Adoption friction:** requires teams to trust packaged functions and encode design logic; may feel abstract compared with direct modelling.
- **Rhino Mind implication:** Hypar is closest philosophically to tooling-on-demand. Rhino Mind should learn from function libraries, but make them contextual to live Rhino/GH practice.

### Skema

- **Wedge:** schematic-to-BIM workflow compression and reuse of firm knowledge.
- **What sets it apart:** practical promise: move faster from schematic concepts into coordinated BIM/Revit using past-project knowledge and repeatable building logic.
- **Evidence:** https://www.skema.ai/ ; https://aecmag.com/bim/bim-workflow-compression-with-skema/ ; https://aecmag.com/bim/skema-ai-conceptual-design-and-re-use-engine-for-revit-launches/
- **Adoption friction:** depends on high-quality firm standards and repeatable project types; may be less useful for bespoke design unless knowledge ingestion is strong.
- **Rhino Mind implication:** very important precedent for “firm memory becomes design automation.” Rhino Mind should make Rhino/GH scripts, details, precedents and project conventions reusable.

### Finch / Finch3D

- **Wedge:** AI/graph-based early design optimisation and floor-plan intelligence.
- **What sets it apart:** fast feedback loops for early layouts, constraints and design performance rather than full BIM production.
- **Evidence:** https://www.finch3d.com/ ; https://docs.finch3d.com/ ; https://aecmag.com/ai/finch-enhances-ai-design-tool/
- **Adoption friction:** strong for early planning, weaker as full documentation/semantic BIM replacement.
- **Rhino Mind implication:** Rhino Mind should support option generation and explainable tradeoffs inside Rhino/GH, not just object creation.

### Augmenta

- **Wedge:** autonomous building systems design, especially MEP/electrical.
- **What sets it apart:** narrower but deeper: discipline-specific automation with spatial AI and constructible system routing.
- **Evidence:** https://www.augmenta.ai/ ; https://docs.augmenta.ai/ ; https://aecmag.com/mep/augmentas-productivity-promise/
- **Adoption friction:** discipline-specific; must satisfy engineers, codes, contractors and liability constraints.
- **Rhino Mind implication:** discipline-specific agents may beat generic design agents. Rhino Mind can start with bounded check/tool packs rather than universal BIM intelligence.

### SWAPP

- **Wedge:** automated BIM / construction documentation production.
- **What sets it apart:** targets the expensive documentation labor layer rather than sexy concept design.
- **Evidence:** https://aecmag.com/ai/swapp-the-algorithmic-assistant/ ; official site was Cloudflare-blocked in this environment.
- **Adoption friction:** must prove deliverable quality, office standards, liability and change management.
- **Rhino Mind implication:** documentation automation is a high-value wedge; Rhino Mind should eventually connect Rhino models to drawing/model QA and evidence packs.

### Higharc

- **Wedge:** cloud-native homebuilding platform with AI-to-3D BIM signals.
- **What sets it apart:** vertical focus on homebuilding; combines design, options, sales/operations and BIM-like data.
- **Evidence:** https://aecmag.com/ai/higharc-ai-delivers-3d-bim-model-from-2d-sketch/ ; https://www.prnewswire.com/news-releases/higharc-announces-53m-series-b-for-its-connected-homebuilding-cloud-302062557.html
- **Adoption friction:** strongest in production/residential/homebuilder workflows, not broad architecture.
- **Rhino Mind implication:** vertical workflows with money attached can beat general tools. Rhino Mind should identify a narrow vertical wedge for early testers.

### Illoca

- **Wedge:** AI-native architectural design: sketch/image/text to BIM-compatible massing and agentic layout editing.
- **What sets it apart:** early but strongly aligned with agentic design creation.
- **Evidence:** https://www.illoca.com/
- **Adoption friction:** early-stage proof and BIM fidelity need verification.
- **Rhino Mind implication:** prompt-to-building will commoditize. Rhino Mind needs defensibility through project memory, tool use and verification.

### Codesign

- **Wedge:** concept-stage design with BIM integration, carbon and generative AI.
- **What sets it apart:** planning/concept workflow rather than full BIM; integrates design decisions with analysis.
- **Evidence:** https://aecmag.com/concept-design/codesign-announces-bim-integration-tools/ ; https://aecmag.com/concept-design/codesign-adds-carbon-calculator-and-generative-ai/
- **Adoption friction:** must bridge into real downstream authoring.
- **Rhino Mind implication:** analysis and carbon should be part of design intelligence, not after-the-fact reports.

### qbiq

- **Wedge:** AI space planning for commercial real estate, with floor plans, tours and BIM model claims.
- **What sets it apart:** targets commercial real-estate speed and automation rather than architect-led authoring.
- **Evidence:** https://www.qbiq.ai/
- **Adoption friction:** bounded typologies; model quality and design nuance must be checked.
- **Rhino Mind implication:** productized planning can bypass architects in some workflows; Rhino Mind should help architects respond with faster, evidence-rich studies.

### EvolveLAB

- **Wedge:** AEC AI plugins/tools such as Veras, Glyph and Morphis; acquired by Chaos.
- **What sets it apart:** tool/plugin layer inside existing AEC workflows rather than replacing authoring software.
- **Evidence:** https://www.chaos.com/press/chaos-acquires-evolvelab-and-its-aec-ai-tools ; https://aecmag.com/visualisation/chaos-acquires-ai-software-firm-evolvelab/
- **Adoption friction:** plugins can become feature-level commodities unless deeply integrated with firm/project data.
- **Rhino Mind implication:** validates plugin/inside-the-tool distribution. Rhino Mind needs more than “AI plugin”; it needs memory, checkability and workflow orchestration.

## Data / interoperability / open BIM infrastructure

### Speckle

- **Wedge:** open AEC data hub connecting fragmented tools and turning model data into streams/objects.
- **What sets it apart:** strongest real-world Rhino/Grasshopper/Revit/web data bridge; developer ecosystem, connectors, server, SDKs and APIs.
- **Evidence:** https://speckle.systems/ ; https://docs.speckle.systems/ ; https://github.com/specklesystems/speckle-server ; https://github.com/specklesystems/speckle-sharp
- **Adoption friction:** teams must shift from file thinking to data streams; schema fidelity varies by connector.
- **Rhino Mind implication:** likely the most important integration target. Use Speckle as live project data bus and cross-tool memory substrate.

### That Open Company

- **Wedge:** open-source browser BIM engine/toolkit: IFC/web components/viewers/fragments.
- **What sets it apart:** developer-first web BIM stack for building custom BIM apps; Fragments format and web-ifc lower the barrier to browser BIM.
- **Evidence:** https://thatopen.com/ ; https://docs.thatopen.com/ ; https://github.com/ThatOpen/engine_components ; https://github.com/ThatOpen/engine_web-ifc
- **Adoption friction:** more toolkit than turnkey workflow; requires developers and productization.
- **Rhino Mind implication:** do not reinvent web BIM viewing/querying; use tools like That Open for browser-side model inspection and agent interfaces.

### IfcOpenShell / Bonsai

- **Wedge:** open-source IFC implementation and native OpenBIM authoring in Blender/Bonsai.
- **What sets it apart:** deepest open IFC tooling: parse/write/validate/convert/query/patch IFC; supports IDS, BCF, bSDD workflows.
- **Evidence:** https://ifcopenshell.org/ ; https://docs.ifcopenshell.org/ ; https://github.com/IfcOpenShell/IfcOpenShell ; https://bonsaibim.org/
- **Adoption friction:** IFC is complex; Blender/Bonsai is culturally far from mainstream Revit production.
- **Rhino Mind implication:** essential infrastructure for serious semantic BIM. Rhino Mind should use IfcOpenShell/IDS/BCF for checks and evidence.

## Feasibility / planning / real-estate intelligence

### Giraffe

- **Wedge:** orchestration layer for AI-driven real estate: feasibility, planning, design, finance and portfolio workflows.
- **What sets it apart:** enterprise real-estate decision system rather than just a design modeller; encodes standards and workflows.
- **Evidence:** https://www.giraffe.build/ ; https://www.giraffe.build/use-cases/ ; https://www.giraffe.build/enterprise/
- **Adoption friction:** enterprise workflow setup; less open/hackable than Rhino/GH/Speckle.
- **Rhino Mind implication:** BIM2 goes upstream into business decisions. Rhino Mind should connect design geometry to feasibility, quantities, constraints and decision evidence.

### TestFit

- **Wedge:** real-estate feasibility and site planning AI.
- **What sets it apart:** fast, productized feasibility for deal teams and specific typologies; strong downstream exports.
- **Evidence:** https://www.testfit.io/ ; https://www.testfit.io/product/integrations ; https://www.testfit.io/product/site-planning-ai
- **Integrations:** Revit add-in, DXF, SketchUp, Excel/PDF, Zoneomics.
- **Adoption friction:** bounded typologies and solver assumptions; less flexible than Rhino/GH for bespoke work.
- **Rhino Mind implication:** benchmark against TestFit speed. Rhino Mind must offer flexibility, explainability and integration with existing custom GH logic.

### Spacio.ai

- **Wedge:** AI early building design and code-aware feasibility for architects.
- **What sets it apart:** code-aware massing/drawings/analytics with Nordic code focus and Rhino/IFC interoperability claims.
- **Evidence:** https://www.spacio.ai/
- **Adoption friction:** geography/code coverage and depth of BIM export need verification.
- **Rhino Mind implication:** code-aware early design is becoming a product category. Rhino Mind should expose constraints/checks inside Rhino instead of leaving them for later.

### Autodesk Forma

- **Wedge:** incumbent cloud early-stage planning/design and analysis platform within Autodesk ecosystem.
- **What sets it apart:** distribution, Revit/ACC/APS ecosystem, enterprise trust and APIs.
- **Evidence:** https://www.autodesk.com/products/forma/overview ; https://aps.autodesk.com/en/docs/forma/v1/overview/
- **Adoption friction:** Autodesk lock-in; weaker appeal for Rhino/GH/openBIM-first firms.
- **Rhino Mind implication:** Autodesk is the incumbent platform pressure. Rhino Mind should integrate where necessary but stay nimble/open around Rhino, Speckle and IFC.

## Knowledge, compliance, documentation and adjacent agents

### Pirros

- **Wedge:** detail/content management and firm knowledge intelligence; Mira agent for Revit.
- **What sets it apart:** indexes firm details/families/standards; solves buried knowledge rather than model authoring.
- **Evidence:** https://www.pirros.com/ ; https://www.pirros.com/features ; https://www.pirros.com/case-studies
- **Adoption friction:** firm content ingestion and Revit-centric workflows.
- **Rhino Mind implication:** validates firm memory as a BIM2 wedge. Rhino Mind should index Rhino/GH scripts, details, precedents and project standards.

### UpCodes

- **Wedge:** building code platform and AI compliance research assistant.
- **What sets it apart:** regulatory knowledge/data moat rather than geometry/model moat.
- **Evidence:** https://up.codes/ ; https://up.codes/ai ; https://up.codes/codes
- **Adoption friction:** liability, jurisdiction-specific interpretation, and lack of direct model integration.
- **Rhino Mind implication:** compliance intelligence becomes valuable when connected to model facts. Rhino Mind should translate model properties into checkable regulatory questions/evidence.

### RunChat

- **Wedge:** Rhino/Grasshopper agentic scripting/workflow canvas, based on `docs.runchat.com` and ATN/McNeel Europe sources.
- **What sets it apart:** direct in-authoring AI habitat: screenshots/geometry to agent, Rhino Python generation, Grasshopper canvas reading/editing.
- **Evidence:** https://docs.runchat.com/plugins/rhino ; https://docs.runchat.com/llms.txt ; https://blog.rhino3d.com/2026/03/runchat-online-workshop-april-21-23.html
- **Caveat:** unrelated `runchat.ai` appears to be a social-media chatbot product. Use the docs.runchat.com / McNeel Europe source path for AEC RunChat.
- **Adoption friction:** script/canvas automation can commoditize; BIM semantics, requirements, provenance and office memory are not yet the visible moat.
- **Rhino Mind implication:** validates the Rhino/GH AI habitat. Differentiate with semantic sidecar: project memory, check packs, classifications, evidence and office tooling.

## Directional synthesis: the six futures of BIM 2.0

### 1. Web-native BIM authoring

- Led by Snaptrude, Arcol, Qonic and eventually Motif if it moves from workspace to authoring.
- Promise: multiplayer, browser, AI-assisted, always-live model.
- Risk: downstream fidelity and Revit/IFC/documentation trust.

### 2. AI feasibility and planning engines

- Led by Giraffe, TestFit, Spacio, Finch, qbiq, Codesign, Autodesk Forma.
- Promise: compress weeks of massing/pro-forma/code/site analysis into minutes.
- Risk: bounded typologies, black-box assumptions, design nuance.

### 3. Workflow compression into BIM

- Led by Skema, Higharc, Hypar, SWAPP, Snaptrude.
- Promise: jump from brief/sketch/schematic to coordinated BIM/deliverables.
- Risk: firm standards and downstream quality are hard.

### 4. Open data and interoperability substrate

- Led by Speckle, IfcOpenShell/Bonsai, That Open Company, IFC/IDS/bSDD/BCF.
- Promise: model data becomes inspectable, queryable, checkable and agent-operable across tools.
- Risk: schemas are hard, and most architects hate schema work unless hidden behind useful workflows.

### 5. Firm memory and compliance intelligence

- Led by Pirros, UpCodes, Skema, maybe Motif and Snaptrude knowledge modules.
- Promise: reuse details, standards, code knowledge and past decisions.
- Risk: ingestion/permissions/liability and messy office data.

### 6. Authoring-tool agents

- Led by RunChat, McNeel RhinoMCP, Pirros/Mira, EvolveLAB-style plugins, and emerging Revit/Rhino/GH agents.
- Promise: AI works inside the tools people already use.
- Risk: raw chat/script generation becomes a commodity unless connected to semantics, standards and evidence.

## What this means for Rhino Mind

The highest-value position is:

> **Rhino Mind = semantic sidecar + agentic tooling layer for Rhino/Grasshopper and open BIM.**

It should focus on:

1. **Live Rhino/GH context understanding** — selection, layers, blocks, object names, user text, Grasshopper graph structure, units, views.
2. **Project/office memory** — prior details, scripts, standards, specs, decisions, reusable components.
3. **Semantic enrichment** — map Rhino geometry into spaces, systems, categories, quantities, materials, IFC/Speckle objects.
4. **Check packs** — IDS-lite, layer/model hygiene, code/zoning/planning prompts, BCF-lite issue output.
5. **Tooling on demand** — retrieve/build/adapt Grasshopper/Rhino scripts for the current task.
6. **Interoperability handoff** — publish clean evidence-rich data to Speckle, IFC, Revit, Snaptrude, Arcol, Motif, Qonic or Forma.

The first five testers should not be sold “AI BIM.” They should be sold: **Steve/Rhino Mind watches what you are doing in Rhino, understands the project, finds or builds the right tool, checks the model, and gives you evidence you can trust.**

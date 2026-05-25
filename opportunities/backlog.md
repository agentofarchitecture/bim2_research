# Opportunity Backlog

## Near-term Rhino Mind wedges

1. **Contextual tool recall**
   - Detect what the architect is doing in Rhino/Grasshopper.
   - Surface relevant existing scripts/components/details.
   - Useful before full autonomous tool building.

2. **Project memory search**
   - Search across notes, scripts, details, specs, previous projects, and decisions.
   - Return references tied to the current model task.

3. **Drawing/model QA assistant**
   - Lightweight checks for naming, layers, blocks, missing annotations, duplicated geometry, model hygiene.
   - Start with Rhino-specific practical pain.

4. **Reusable detail/tool extraction**
   - Watch repeated operations and suggest turning them into reusable tools.

5. **Semantic material/system library**
   - Materials/details become queryable by use, cost, carbon, supplier, previous project, and construction method.

6. **IDS-lite checker for Rhino/Speckle**
   - Define a tiny YAML/JSON requirement schema for layers, object names, user text, blocks, and Speckle properties.
   - Run pass/fail/warn checks and produce an auditable model preflight report.
   - Later map the schema to buildingSMART IDS XML.

7. **Brief/spec to model preflight checklist**
   - Extract requirements from a client brief, planning note, or office standard.
   - Convert them into human-reviewable checks before claiming any automated compliance.

8. **Broken Rhino model triage**
   - Scan for duplicated geometry, bad blocks, nonstandard layers, missing metadata, oversized assets, and unresolved references.
   - Return ranked fixes plus optional Rhino Python/Grasshopper helper scripts.

9. **Top-100 people graph → interview map**
   - Build a lightweight graph of standards contributors, open-source implementers, product builders, and practice critics.
   - Use it to choose 5–10 short interviews that answer: what can be checked in Rhino/Speckle today without pretending to be full BIM?

10. **IDS examples → Rhino check-pack converter**
   - Pull public buildingSMART IDS examples and manually map 3–5 requirements into a YAML check pack for Rhino object names, layers, user text, and Speckle properties.
   - Test whether architects understand and trust the report.

11. **Rhino MCP adapter micro-benchmark**
   - Define 6–8 stable task primitives: inspect selection, list layers, read object metadata, run QA check, create simple geometry, patch user text, export evidence.
   - Build a tiny benchmark from 2–3 messy Rhino/Speckle project snapshots.
   - Measure whether an agent can complete tasks reproducibly with provenance instead of relying on chat answers.

12. **Explore-then-check model dialect mapper**
   - Before any QA/compliance answer, have Rhino Mind map the project’s local dialect: layer conventions, block names, object names, user text keys, Speckle properties, units, and missing metadata.
   - Output a “model dictionary” and use it to translate IDS-lite checks into the project’s actual conventions.



13. **RhinoMCP semantic sidecar**
   - Use McNeel RhinoMCP for raw environment control, but add Rhino Mind’s own semantic layer: selected-object classifier, bSDD/office-vocabulary suggestion, IDS-lite check runner, and evidence report.
   - Success test: agent can explain not just what it created/edited, but what the object means and what requirement it satisfies or violates.

14. **BCF-lite issue exporter**
   - Convert QA/check failures into lightweight issue cards: element reference, screenshot/viewpoint, rule, severity, suggested fix, assignee/status, provenance.
   - Later map this to BCF/OpenCDE when collaboration integrations matter.

15. **Geometry-first vs IFC-first MCP benchmark**
   - Run one task through RhinoMCP and MCP4IFC: create/find a wall-like element, classify it, attach required properties, run a check, and export evidence.
   - Use results to decide which tasks belong in Rhino, Speckle, IFC, or a hybrid adapter.

## Bigger strategic bets

- Open project knowledge graph for small architecture practices
- Agent-readable office standards
- AI-native BIM QA and compliance checking
- “Tooling on demand” marketplace for computational design micro-tools
- BIM-light workflows for firms that prefer Rhino but need structured intelligence

## Daily loop instruction

Add new opportunities here only when they are specific enough to test or discuss.

13. **Two-lens Rhino/Speckle memory prototype**
   - Export a small Rhino/Speckle model into two synchronized indexes: object/property table and relationship graph.
   - Ask 10 natural-language questions and record whether each is best answered by table, graph, or both.
   - Use this as a product demo for “project memory you can inspect,” not black-box chat.


14. **RunChat comparator teardown for Rhino Mind**
   - Reproduce RunChat’s visible Rhino/GH task categories from docs: screenshot-to-workflow, geometry transfer, Rhino Python generation, Grasshopper canvas explanation/component wiring.
   - For each task, add the Rhino Mind semantic sidecar version: identify object meaning, attach office vocabulary, run a check, retrieve prior detail/tool, and export evidence.
   - Output a feature matrix: “RunChat-like automation” vs “Rhino Mind semantic project intelligence.”

15. **Rhino-to-BIM2 handoff agent**
   - Pick 3 target platforms from the player map: Speckle, Snaptrude, Qonic/Motif.
   - For a messy Rhino/GH model, produce a handoff package: cleaned layers, named objects, spaces/zones, materials, quantities, preview screenshots, assumptions, missing metadata, and export instructions.
   - Success test: the receiving platform gets more structured, less ambiguous data than a normal manual export.

16. **Six-layer BIM2 positioning deck**
   - Turn the player differentiation map into a short founder/user deck: web authoring, feasibility engines, workflow compression, open data, firm memory/compliance, authoring-tool agents.
   - End with Rhino Mind’s wedge: semantic sidecar for Rhino/GH + open BIM.
   - Use this to explain Rhino Mind to first-five testers without sounding like “another BIM platform.”

17. **Composable BIM atoms prototype**
   - Build 5 tiny Rhino/GH semantic actions inspired by Hypar Elements + Raven: classify selected objects, add user text/property pack, generate one editable GH helper, run one IDS-lite check, export one BCF-lite issue.
   - Each atom must be editable, inspectable, and evidence-backed.
   - Success test: an architect can run/use one atom without migrating to a new BIM platform, and the atom leaves better project memory behind.

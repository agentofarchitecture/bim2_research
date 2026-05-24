# BIM 2.0 Company Landscape

Last updated: 2026-05-24.

Purpose: maintain a grounded company/product map for BIM 2.0 so the people map is not floating in abstract research. This starts with Luke’s instruction to mine YouTube/ATN, especially Oliver/Olly Thomas and ArchiTech Network interviews.

## Working clusters

### 1. Web-native / collaborative BIM authoring

- **Arcol** — collaborative web-native BIM; ATN video `DY7AP1rj0PQ` frames it as “the Figma of the AEC industry”. Key person to research: Paul O’Carroll.
- **Snaptrude** — web BIM / design-to-BIM workflow; ATN video `k298u6ejRFw` with Altaf Ganihar; also `t9pc5TPIsco` on AI-driven design.
- **Qonic** — BIM collaboration / model workflow; ATN Qonic x Giraffe workshop `-soSNdoWojA`.
- **Motif** — BIM 2.0 / documentation disruption; ATN video `3bI-fXW74rY` with Jens Majdal Kaarsholm, explicitly “Why I Left BIG and Joined Motif to Disrupt BIM”.
- **Rayon** — collaborative browser CAD/planning; needs primary-source verification in future pass.

### 2. Site feasibility / city-building / early design intelligence

- **Giraffe** — citybuilder / site feasibility for architects and developers; ATN videos `TiYFZjIHEcg` and `5HvYeBNere0`; key person: Rob Asher.
- **TestFit** — feasibility/test-fitting automation; adjacent comparison node, not yet ATN-confirmed in this pass.
- **Finch / Finch3D** — architects + AI designing together; ATN video `OqyUj-Lfy6g`; key people: Jesper Wallgren and Pamela Wallgren.
- **Spacio.ai** — included in ATN “9 startups” BIM 2.0 overview (`dturff3XgSk`); needs verification.
- **Forma** — Autodesk Forma / planning and early-stage design; included as a strategic incumbent comparison.

### 3. Computational automation / design systems

- **Hypar** — building design automation with AI/automation; ATN video `nmOa70lOnv0`; key people: Ian Keough and Andrew Heumann.
- **Augmenta** — automated building design/systems; verify with primary sources.
- **SWAPP** — automated documentation/BIM production; verify with primary sources.
- **Skema** — schematic-to-BIM and reuse of BIM knowledge; surfaced in AEC tech search results and should be added to the watchlist.

### 4. Data platforms / interoperability / open tooling

- **Speckle** — connector/data platform and open AEC data layer; ATN video `67aBKPTREo0` with Dimitrie Stefanescu and Matteo Cominetti; workshops with HENN/X-Figura (`gqkffbFHrk8`).
- **That Open Company / That Open Engine** — web openBIM components/developer tooling; already represented in Top 100 through Antonio González Viegas.
- **RunChat** — Rhino/Grasshopper-oriented design-agent and visual-canvas interface; ATN video `PPqDz4H2bmg`; direct Rhino Mind comparator. Primary docs verified 2026-05-24: `docs.runchat.com/plugins/rhino` describes sending screenshots/geometry to Runchat, generating Rhino Python scripts, importing results back into the viewport, and beta Grasshopper agent actions that read/explain/connect components. McNeel Europe workshop page names Gwyllim Jahn and James Pazzi as tutors.
- **NonicaTab** — Revit + Claude/AI connector; adjacent implementation pattern for authoring-tool AI plugins.

### 5. Product/manufacturer BIM object workflows

- **OLI** — products as BIM objects / product information and rendering workflow; separate from Oliver/Olly Thomas despite name collision. ATN-adjacent search surfaced video `340c6Wi2kT8` from OLI.

## Priority next research passes

1. Watch/transcribe or otherwise extract the ATN anchor overview `dturff3XgSk` and build a company → person → thesis table.
2. Deep-dive ATN Episodes 61–65: Snaptrude, Giraffe, Arcol, Hypar, Motif.
3. Add founder/interviewee candidates with mental models:
   - Oliver / Olly Thomas — ATN graph-maker and Architect 3.0 thesis.
   - Paul O’Carroll — Arcol.
   - Altaf Ganihar — Snaptrude.
   - Rob Asher — Giraffe.
   - Jens Majdal Kaarsholm — Motif.
   - Ian Keough / Andrew Heumann — Hypar.
   - Jesper Wallgren / Pamela Wallgren — Finch.
4. Verify company primary sources: websites, docs, changelogs, APIs, GitHub, customer/practice evidence.
5. Convert the landscape into Rhino Mind implications: which product wedge is closest to contextual tooling/tooling-on-demand for Rhino users?

## Strategic read for Rhino Mind

The ATN/company graph suggests BIM 2.0 is not one category. It is a bundle of competing wedges:

- collaborative authoring;
- test-fit / feasibility intelligence;
- schematic-to-BIM automation;
- open data/interoperability;
- AI-assisted design exploration;
- product/manufacturer data integration;
- agentic tool control inside existing authoring tools.

Rhino Mind’s likely wedge is different: **contextual tooling and project memory inside Rhino/Grasshopper practice**, with enough semantic structure to connect to Speckle/IFC/IDS later.


## 2026-05-24 RunChat comparator note

- **Product wedge:** AI workflow canvas + chat/design agents embedded into Rhino and Grasshopper.
- **Evidence artifacts checked:** ATN oEmbed title for `PPqDz4H2bmg`; Runchat Rhino docs; Runchat `llms.txt`; McNeel Europe workshop post; Gwyllim Jahn Substack post “Runchat in Rhino”.
- **Integration surface:** Rhino PackageManager install, browser/plugin connection to active Rhino document, screenshot/geometry transfer, Rhino Python script generation/execution, Grasshopper canvas reading and component connection.
- **Adoption friction:** immediate for Rhino/GH users, but still primarily a canvas/agent/scripting layer; project semantics, audit trails, requirements, and office/project memory are not the visible differentiator in the checked docs.
- **Rhino Mind implication:** do not compete only on “AI writes Rhino Python.” Compete on semantic sidecar behavior: understand the project dialect, retrieve office tools/details, run check packs, and produce evidence.

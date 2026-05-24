# Source Graph

Last updated: 2026-05-24.

## People → sources / tools

- Dion Moult → core contributor → IfcOpenShell / Bonsai
- Dion Moult → contributor → buildingSMART IDS
- Claudio Benghi → top contributor → buildingSMART IDS
- Léon van Berlo → contributor / buildingSMART International → buildingSMART IDS
- Artur Tomczak → contributor / buildingSMART → buildingSMART IDS
- Thomas Krijnen → core contributor → IfcOpenShell
- Dimitrie Stefanescu → founder / contributor → Speckle Server
- Matteo Cominetti → co-founder / contributor → speckle-sharp
- Alan Rynne → major contributor → speckle-sharp
- Antonio González Viegas → contributor → That Open engine components
- Tom Van Mele → primary contributor → COMPAS
- Chris Mackey → contributor → Ladybug Tools / ladybug-rhino
- Ryan Schultz → practice/open-source voice → OpeningDesign + IfcOpenShell
- André Borrmann → co-author / research-program node → MCP-server architecture, adaptive BIM extraction, BIMgent, TUM2TWIN
- Jakob Beetz → co-author / semantic BIM lineage → MCP-server architecture + linked building data thinking
- Pieter Pauwels → contributor → buildingSMART/ifcJSON; semantic BIM / linked building data source
- Tobias Heimig-Elschner → lead author → MCP-server reference architecture for agentic BIM interaction
- Sylvain Hellin → lead author → LLM-based adaptive BIM information extraction
- Zihan Deng → lead author → BIMgent computer-use agents for BIM authoring
- Klaus Aengenvoort → contributor → buildingSMART/bSDD


- Callum Sykes → primary contributor → McNeel RhinoMCP
- Steve Fuchs → contributor / design technologist → McNeel RhinoMCP
- Bharathi Kannan Nithyanantham → lead author / contributor → MCP4IFC
- Ashwin Nedungadi → co-author / contributor → MCP4IFC
- Georg Dangl → top contributor → buildingSMART BCF-API
- Christoph Mellüh → creator → bSDD-Toolkit
- Jardi Margalef Agusti → creator → bSDD-mcp

## Standards / concepts → implementation sources

- IDS → implemented / evolved in → buildingSMART/IDS GitHub repository
- IDS → possible LLM generation target → Ishigaki-IDS-Bench
- IFC → implementation substrate → IfcOpenShell
- IFC → graph query substrate → IFC Whisperer
- Speckle object/data model → bridge between → Rhino/Grasshopper/Revit and web project data
- COMPAS → computational design infrastructure for → Rhino/Grasshopper and Blender
- Ladybug Tools → practice-grade environmental analysis in → Rhino/Grasshopper
- bSDD → vocabulary / classification layer for → IDS requirements and semantic model properties
- MCP → tool-calling interface for → reusable BIM agent adapters
- Adaptive exploration → runtime discovery of → heterogeneous BIM/Rhino/Speckle model dialects


- Rhino MCP → environment-control substrate for → agentic Rhino workflows
- MCP4IFC → schema-control substrate for → agentic IFC workflows
- BCF/OpenCDE → collaboration issue/context layer for → check findings and coordination tasks
- bSDD MCP/toolkits → vocabulary lookup/authoring layer for → semantic model enrichment

## Product / ecosystem connections

- Speckle Server → AI-ready project data / model validation narrative → Speckle blog
- speckle-sharp → Rhino/Grasshopper/Revit connector layer → Rhino Mind integration path
- That Open Company → open web BIM components → possible viewer/inspection layer
- Arcol → connected constructible design + continuous testing messaging → supports “test while designing” pattern
- Snaptrude AI → massing/programming/site analysis agents → product-market signal, implementation detail to verify

## Research connections

- Ryo Kanazawa et al. → Ishigaki-IDS-Bench → IDS generation from BIM information requirements
- Jia-Rui Lin et al. → Qwen-BIM → BIM domain LLM benchmark/dataset
- Soumya Madireddy et al. → LLM-driven code compliance checking → compliance preflight opportunity
- Yu Hsiu Tung / Sam Rezvani / Fatemeh Asgharzadeh → IFC Whisperer → IFC knowledge graph + LLM querying
- Meng Wang / G. Lilis / K. Katsigarakis → HVAC topology generation → BIM geometry checking + knowledge graphs
- Tobias Heimig-Elschner / Changyu Du / Anna Scheuvens / André Borrmann / Jakob Beetz → MCP server reference architecture → API-agnostic agentic BIM interaction
- Sylvain Hellin / Suhyung Jang / Stefan Fuchs / Stavros Nousias / André Borrmann → adaptive exploration → BIM information extraction from heterogeneous models
- Zihan Deng / Changyu Du / Stavros Nousias / André Borrmann → BIMgent → autonomous building modelling via computer-use agents

- Bharathi Kannan Nithyanantham / Tobias Sesterhenn / Ashwin Nedungadi / Sergio Peral Garijo / Janis Zenkner / Christian Bartelt / Stefan Lüdtke → MCP4IFC → IFC-based building design using LLMs and MCP
- Hanlong Wan / Weili Xu / Michael Rosenberg / Jian Zhang / Aysha Siddika → Automatic Building Code Review case study → BIM extraction + RAG/MCP agent pipelines

## 2026-05-24 graph additions

- Rabindra Lamsal / Sisi Zlatanova / Haowen Xu / Yafei Sun / Johnson Xuesong Shen → IfcLLM → hybrid relational + graph representation for natural-language IFC querying
- IfcLLM → complements / should be compared with → IFC Whisperer, adaptive BIM information extraction, Multi-Agent GraphRAG
- Ryo Kanazawa / Koyo Hidaka / Teppei Miyamoto / Takayuki Kato → Ishigaki-IDS-Bench repo → benchmark for generating buildingSMART IDS XML from BIM information requirements
- Louis True → ids-flow + agentic-bim-team → practical but early signal around visual IDS authoring and agentic BIM workflows; verify before people promotion
- mac999/BIM_LLM_code_agent → Vector + Graph RAG over BIM/IFC → candidate implementation source; inspect code quality before promotion


## 2026-05-24 ATN / YouTube grounding additions

- Oliver / Olly Thomas → hosts / curates → ArchiTech Network / ATN → interview graph for BIM 2.0 company landscape
- ATN BIM 2.0 overview `dturff3XgSk` → names → Snaptrude, Arcol, Giraffe, Motif, Qonic, Spacio.ai, Finch, Hypar, Speckle
- Paul O’Carroll → founder/interviewee → Arcol → collaborative web-native BIM / “Figma for AEC” thesis
- Altaf Ganihar → founder/interviewee → Snaptrude → web design-to-BIM / AI-driven design thesis
- Rob Asher → founder/interviewee → Giraffe → citybuilder / site feasibility thesis
- Jens Majdal Kaarsholm → interviewee → Motif → practice-to-product BIM disruption thesis
- Ian Keough / Andrew Heumann → interviewees → Hypar → computational design automation thesis
- Jesper Wallgren / Pamela Wallgren → interviewees → Finch → AI-assisted early design thesis
- ATN workshops → connect → Qonic + Giraffe, Speckle + HENN/X-Figura, Finch + KPF
- RunChat ATN episode → direct comparator → Rhino Mind contextual tooling / Rhino AI interface


## 2026-05-24 RunChat primary-source additions

- ATN video `PPqDz4H2bmg` → verifies public source node → “Supercharging Rhino with RUNCHAT.APP”.
- RunChat docs → expose → Rhino screenshots/geometry transfer, Rhino Python generation/execution, Grasshopper agent beta.
- RunChat `llms.txt` → exposes → canvas API, workflow run endpoint, job triggers, scheduling, agent capabilities.
- Gwyllim Jahn → writes/teaches → RunChat in Rhino / connecting Runchat workflows to Rhino and Grasshopper.
- James Pazzi → teaches with → Gwyllim Jahn → McNeel Europe RunChat workshop.
- RunChat → competes with / informs → Rhino Mind in-environment AI tooling, but leaves opportunity for → semantic project-memory sidecar and IDS-lite/evidence workflows.

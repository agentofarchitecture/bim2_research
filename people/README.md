# BIM 2.0 People Map

Goal: identify the top 100 people shaping BIM 2.0 and adjacent AI/AEC/digital-building practice.

This is not a popularity list. It is a strategic source graph for Luke / Agents of Architecture / Rhino Mind: who to read, follow, learn from, map, contact, or build around.

## Definition: “top people in BIM 2.0”

BIM 2.0 means the shift from static coordinated BIM files toward live, semantic, agent-readable project systems: openBIM data, project knowledge graphs, AI agents, computational design automation, digital twins, compliance/cost/carbon checking, and tooling-on-demand inside authoring environments.

## Target distribution

The final Top 100 should balance:

- **Standards/openBIM leaders** — IFC, IDS, bSDD, openCDE, buildingSMART, ISO 19650.
- **Researchers** — semantic BIM, knowledge graphs, automated compliance, LLMs for AEC, digital twins.
- **Open-source builders** — Speckle, IfcOpenShell/Bonsai, That Open Engine, Ladybug Tools, COMPAS, open source AEC graphs/tools.
- **Product/startup operators** — AI/BIM/CAD tools, generative building platforms, design automation products.
- **Vendor/platform leaders** — Autodesk Forma/Revit/APS, Rhino/Grasshopper ecosystem, Trimble, Bentley, Nemetschek/Graphisoft where relevant.
- **Computational design practitioners** — people turning advanced tooling into real architectural practice.
- **Critics/adoption voices** — practitioners who understand why BIM/AI fails or succeeds in real offices.
- **Adjacent AI/agent people** — only where their work can materially shift AEC/BIM workflows.

## Candidate schema

Each candidate should be tracked like this:

```yaml
name:
primary_role:
orgs:
category:
country_region:
links:
  website:
  linkedin:
  x:
  github:
  scholar:
  key_work:
why_they_matter:
evidence:
  - source/link
connections:
  people:
  orgs:
  standards/tools:
signal_score:
  relevance: 0-20
  authority: 0-15
  freshness: 0-15
  specificity: 0-15
  interconnectedness: 0-15
  actionability: 0-20
total_score: 0-100
status: candidate | verified | top-100 | rejected
notes:
```

## Selection principles

Promote people who are one or more of:

1. Building the infrastructure of BIM 2.0.
2. Publishing highly relevant technical work.
3. Creating tools practitioners can actually use.
4. Sitting at important graph intersections between standards, software, practice, and research.
5. Explaining the adoption/business/practice reality unusually well.
6. Useful for Rhino Mind: someone whose work suggests a product wedge, architecture workflow, or source of reusable tools.

Reject or demote:

- Generic AI influencers with no AEC/BIM depth.
- Vendor executives with no direct technical/product relevance.
- Dead projects with no current signal unless historically foundational.
- Pure BIM 1.x training voices unless connected to the BIM 2.0 transition.

## Workflow

1. Seed candidates from standards bodies, papers, open-source repos, startup/product ecosystems, and public practitioner discussion.
2. Follow links: co-authors, contributors, conference speakers, repo maintainers, standards working groups, social mentions.
3. Score each candidate with evidence.
4. Keep the live longlist in `people/candidates.md`.
5. Promote verified people into `people/top-100.md`.
6. Add outreach/relationship ideas in `people/outreach-targets.md` only when useful for Luke/Rhino Mind.

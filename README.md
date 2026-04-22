# The Invisible Hand of   Athens, GA

A civic network graph mapping the organizations, mutual aid groups, collectives, and faith communities doing community care work in Athens, Georgia.

You can access the the Network Websit [here](https://mtcates-lab.github.io/invisible-hand-athens).
Or https://mtcates-lab.github.io/invisible-hand-athens if the hyperlink does not work.

---

## What this is

A research and visualization tool that maps how community organizations in Athens connect to each other, such as, who refers to whom, where resources flow, and where the gaps are.

This is not a resource finder. Two good tools already do that for Athens: [Mutual Aid Athens](https://www.facebook.com/groups/MutualAidAthens/) and [Mutual Aid Disaster Relief](https://mutualaiddisasterrelief.org/co-conspirators/athens-mutual-aid-network/). Additionally, I found this Reddit thread to be of some use [Link](https://www.reddit.com/r/Athens/comments/1gl1mtz/mutual_aid/). 

This project is about the relationships between organizations whether they be formal or informal groups

The name is a joke on Adam Smith's "invisible hand" of the free market. This is the other invisible hand. The one that's been feeding, sheltering, and caring for people all along, outside of institutional recognition or market logic.

---

## Inclusion criteria

- **Formal nonprofits** — registered 501c3 organizations
- **Faith communities** — churches and faith-based groups doing resource work
- **Mutual aid networks** — informal collectives operating on solidarity principles
- **Grassroots groups** — people and collectives doing the work without legal status

No 501c3 required to exist in this graph. Community legitimacy is the bar for inclusion.

---

## Exclusion criteria

Individual people offering services. This project is about organizational clusters, not a personal directory. For peer-to-peer mutual aid and skills exchange, connect with local Athens community spaces directly.

---

## How to use it

Open the site. Click any node to see an organization's details and connections. Use the filter buttons to show only certain types of organizations. Drag nodes to rearrange the graph. Scroll to zoom.

---

## Data model

**Nodes** — each dot is one organization. Each node stores:
- Name, type, and formality level
- Services offered
- Area of Athens served
- Contact information
- Notes

**Edges** — each line is a relationship. Relationship types:
- **Referral** — one org regularly sends people to another
- **Partnership** — active collaboration
- **Resource flow** — one org provides material resources to another
- **Shared population** — both serve the same people
- **Overlap** — similar services in the same geography

---

## Current status

Built from initial broad research and my own volunteer relationships in Athens. Data is incomplete by design, as I learn more, I'll add more, trying to keep it alive. 

Known potential gaps are tracked and being filled through direct conversations with organizations.

---

## Adding organizations

This is currently curator maintained to ensure data quality. If you know of an organization that should be in the graph:

- Open an issue on this repository with the org name and what they do
- Or reach out directly via email @ mtcates@uga.edu with the subject line: "Invisible Hand" and:
- **Nodes** — each dot is one organization. Each node stores:
- Name, type, and formality level
- Services offered
- Area of Athens served
- Contact information
- Notes

Submissions are reviewed before being added.

---

## Philosophy

Communities have always taken care of each other. That knowledge of connection used to live in neighborhood memory. This project is an attempted to make it legible for the community.

This tool is:
- Not affiliated with any institution.
- Not for profit.
- Not a data extraction project.
- Not interested in outside interests.
- Governed by the communities it maps.
- Hyperlocalization is the fight against fascism.

Organization data belongs to the organizations. Anyone in the graph can request changes or removal at any time.

---

## Built with

Plain HTML, CSS, and JavaScript. No frameworks, no dependencies, no tracking, no analytics. Should runs anywhere.

---

## License

Code is MIT licensed — So please use it, fork it, build your own version for your city or community.

Data about specific organizations belongs to those organizations and should not be reused without their knowledge.

---

*Athens, GA · Started 2025*

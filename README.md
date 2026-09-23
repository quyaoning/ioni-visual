# ioni-visual

## To Do

### Cathode structure CAD
_References: Gott's thesis, PDR/CDR slides - both available on BOX_

- [ ] CAD modeling — parametric geometry of tube/collar/pin/collector,Prefers using FreeCAD from what I looked into.
- [ ] Materials/BOM — dimensions & materials list matching
- [ ] Cutaway prep — exploded/sectioned view for later rendering

### Rendering environment

- [ ] Redering Environment selection and setup — Requirements:
  - Handles both particle data and CAD geometry together
  - Able to do Field visualization
  - Playback function
  - Embeddable in a website
  - Independent per-client sessions
  - Python-native or Python-scriptable
  - Exports static figures
- [ ] Data pipeline — load last semester's particle dataset into it
- [ ] Web/interactive layer — frontend construction (plugs into the homepage later)

### Paper work (ion kinetics)

- [ ] Literature review — collision cross sections, stepwise ionization papers
- [ ] Physics/model scoping — species, reactions, inputs the rate-equation model needs
- [ ] Writing — problem statement draft

### Club homepage

- [ ] Web dev — pick platform/framework, build the site itself
- [ ] Content/structure — page layout (overview, subteams, gallery)
- [ ] Design assets — logo, photos from Multimedia folder
---
Scientific visualization subteam, Electric Propulsion Initiative (ION-I). Fall 2026: club homepage, CAD/scientific-figure pipeline, and an interactive plasma viewer, building on last semester's particle-visualization prototype ([plasma-visualization](https://github.com/quyaoning/Plasma-Visualization)).

We work closely with the main ION-I club, so this plan will shift with their priorities, timelines, and CAD/analysis deliverables as those land.

**Paper track**: a research-grade paper on this subteam's scientific-visualization work, topic TBD
- [Engineering Open House](https://www.eohillinois.org/), Apr 9-10, 2027 — public exhibit/demo format.
- [Undergraduate Research Symposium](https://undergradresearch.illinois.edu/events/research-week/symposium/), Apr 28-29, 2027 — poster/oral
  
| Semester Plan ||
|---|---|
| Sep 20 - Sep 26 | • Define engineering-geometry/field-data input format.<br>• Paper: scope candidate topics against the visualization/physics workstreams, pick one.<br> Deliverable: Data & geometry inventory and import plan; paper topic selected. |
| Sep 27 - Oct 3 | • Extend particle visualization to engineering geometry and field data.<br>• Stand up PyVista/VTK/Trame rendering environment in this repo.<br>• Paper: literature review / related-work scan.<br> Deliverable: Field-data loader prototype; paper related-work summary. |
| Oct 4 - Oct 10 | • Scaffold club homepage (thruster architecture, research objectives, project status).<br>• Paper: draft outline and methods framing.<br> Deliverable: Homepage skeleton deployed; paper outline. |
| Oct 11 - Oct 17 | • Build subteam-research page templates (hardware, models, analysis).<br>• Add technical-record section (methods, references, links to data/code).<br> Deliverable: Subteam + technical-record page templates. |
| Oct 18 - Oct 24 | • Build simplified microplasma cathode CAD assembly.<br>• Paper: results/figures for the method section, drawn from this repo's outputs.<br> Deliverable: First CAD assembly; paper method-section figures. |
| Oct 25 - Oct 31 | • Cutaway renders and scientific-gallery layout (CAD + renders + interactive views).<br> Deliverable: Cutaway render set. |
| Nov 1 - Nov 7 | • Connect plasma viewer to homepage.<br>• Document data conventions (units, model assumptions) per figure.<br>• Paper: first full draft.<br> Deliverable: Embedded viewer v1; paper first full draft. |
| Nov 8 - Nov 14 | • Publish documented figure examples.<br>• Define reproducible-output workflow (source data, model assumptions, rendering settings).<br> Deliverable: Reproducible figure workflow. |
| Nov 15 - Nov 21 | • First cross-subteam visualization: Discharge Chamber (magnet geometry/field maps) or Ion Optics (grid geometry, ion trajectories).<br>• Paper: revision pass w/ advisor or club feedback.<br> Deliverable: Cross-team visualization panel; paper revised draft. |
| Nov 22 - Nov 28 | • QA across homepage and viewer; close data-provenance gaps.<br>• Thanksgiving break Nov 26 - Nov 27, light-touch week.<br> Deliverable: Pre-break stable build. |
| Nov 29 - Dec 5 | • Finalize scientific figures for papers/technical reviews.<br>• Paper: submission-ready draft.<br> Deliverable: Publication-ready figure set; paper submission-ready draft. |
| Dec 6 - Dec 12 | • Project documentation.<br>• Semester wrap-up and final figure publish.<br>• Paper: submit / prep EOH & URS abstracts for Spring 2027.<br> Deliverable: Semester close-out; paper submitted, EOH & URS abstracts drafted for Spring 2027. |

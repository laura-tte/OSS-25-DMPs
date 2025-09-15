# Research Data Management (RDM) plans 

This repository contains the slides for the **Research Data Management (RDM) plan session** presented during the **[LMU Open Science Summer School 2025](https://lmu-osc.github.io/Open-Science-Summer-School-2025/)**. The slides are built using [Quarto](https://quarto.org/) and are published using [GitHub Pages](https://pages.github.com/).

Author: Laura Meier ([0000-0003-1368-2306](https://orcid.org/0000-0003-1368-2306)), University Library of Ludwig-Maximilians-Universität

---

## Overview

The presentation covers:
- Key components of a Data Management Plan (DMP)
- Motivation to create a Data Management plan
- Tools and resources for creating effective DMPs

It includes interactive elements and is based on the (self-guided) OSC tutorial for [FAIR Research Data Management](https://lmu-osc.github.io/FAIR-Data-Management/).

## Workshop Goals

By the end of this session, participants will:
- Define what a Data Management Plan (DMP) is and explain its purpose
- Identify the key components typically included in a DMP
- Apply funder requirements when considering their own DMP
- Begin drafting their own DMP using RDMO

## Workshop Timeline

**Total Duration**: 1 hour (60 minutes)

| Time | Duration | Section | Content & Activities | Type |
|------|----------|---------|---------------------|------|
| 00:00 | 5 min | **Introduction** | Connection to [FAIR session](https://github.com/ree-gupta/osss-fair-rdm/tree/main): FAIR checklist, today's topics, introduce Particify  | Presentation |
| 00:05 | 10 min | **Part I: How to plan Data Management?** | DMP intro, components of a DMP | Presentation + Group work (https://partici.fi/93557178) |
| 00:15 | 10 min | **Part II: Why bother planning your Data Management?** | Advantages of a DMP, Funder requirements, Improve answer for DFG checklist | Presentation + Group work (https://partici.fi/93557178) |
| 00:25 | 30 min | **Part III: Tools that support you in planning** | DMP tools, Introduce RDMO, Create a DMP with RDMO | Presentation + Live Demo + Time to create a DMP|
| 00:55 | 5 min | **Wrap-Up** | University library: RDM services, recommend self-guided tutorial | Presentation |


## Repository Structure

- slides.qmd # Main Quarto presentation file
- slides.html # HTML presentation of the Quarto file
- style.css # CSS configuration
- images/ # Images
- .github/workflows # CI to update website automatically
- .gitignore 
- LICENSE.md # License information
- CITATION.cff # Citation information
- README.md # This file

## How to View the Slides

The slides are published via **GitHub Pages** and can be accessed here:  

[View Presentation](https://laura-tte.github.io/OSS-25-DMPs/slides.html/)

## How to Build Locally

1. Install [Quarto](https://quarto.org/docs/get-started/) if you haven't already.
2. Clone this repository:

```bash
git clone https://github.com/laura-tte/OSS-25-DMPs.git
cd OSS-25-DMPs
```

3. Render the slides locally:

```bash
quarto render slides.qmd
```

4. Open the generated HTML file in your browser.

## License

The materials can be used, remixed, adapted and shared according to the [CC BY-SA 4.0 Licence](https://creativecommons.org/licenses/by-sa/4.0/). 
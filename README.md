# Description

This repository contains all the materials to reproduce the manuscript.

To render only the manuscript, run:

```bash
quarto render manuscript.qmd
```

# Repository structure

``` text
power_manuscript/
├── _extensions/               # Quarto extensions used by the manuscript
├── _quarto.yml                # Quarto project configuration
├── index.qmd                  # Quarto manuscript source file
|
├── data/                      # Data used in the analyses
│   ├── psychsci.rds           # Articles used to run the Metacheck modules
│   ├── res_power.RData        # Results of the `power` module using the rule-based approach
│   └── res_power_llm.RData    # Results of the `power` module using the LLM-based approach
│
├── docs/                      # Results of rendering
|   ├── index.docx             # Rendered manuscript in docx format
│   ├── index.html             # Rendered manuscript in html format
|   └── session-info.txt       # R session information
|
├── includes/                  # Helper files
│   ├── apa.csl                # APA citation style file
│   ├── package-citations.bib  # Bibliography file containing package refs
|   ├── references.bib         # Bibliography file containing references
│   └── style.css              # Visual styles for html
```


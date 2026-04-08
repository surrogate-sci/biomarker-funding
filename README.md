# Biomarker Research Funding

NIH has spent between **$62B and $175B** on biomarker-related research since 2004. Why then has the throughput and performance characteristics of valuable biomarkers,such as surrogate endpoints and treatment optimization, been so poor? This is the subject of our inquiry.

*Click charts to open the interactive version.*

[![Cumulative NIH Biomarker Research Spending FY2004-2024, nominal](data/fig-1/cumulative_biomarker_funding_nominal.png)](https://datawrapper.dwcdn.net/VydiG/)

[![Cumulative NIH Biomarker Research Spending FY2004-2024, 2024 dollars](data/fig-1/cumulative_biomarker_funding_2024dollars.png)](https://datawrapper.dwcdn.net/pzYSe/)


**Forthcoming:** In the next phase of this project, we will study the landscape of biomarker R&D and how discovery & development (mis)align with intended clinical and regulatory use cases. Here is a quick preview of where all this funding goes in oncology. ![diagnosing diseases, predicting risk and prognosis](https://github.com/surrogate-sci/nih-biomarker-funding/blob/main/visualizations/biomarker_use_distribution.png) Risk and prognosis biomarkers require correlational evidence that generalizes over a representative population. Such biomarker applications are much less epistemically demanding than causal biomarkers to help patients choose the best treatment as individuals, or surrogate biomarkers that effectively forecast eventual patient benefit. These more challenging and more valuable biomarker categories do not get the resources needed to deliver on their promise. ![causal bioamrkers](https://github.com/surrogate-sci/nih-biomarker-funding/blob/main/visualizations/evidence_strength_distribution.png) 

Please get in touch with [manjari@manjarinarayan.com](mailto:manjari@manjarinarayan.com) if you are interested in updates.

## How these numbers were developed

We searched NIH Reporter — the public database of all federally funded NIH grants — for biomarker-relevant research using keyword searches on project titles, terms, and abstracts. Facilities and administrative grants were excluded.

The **core term set ($62B)** counts grants that explicitly name biomarker concepts: *biomarker, clinical marker, surrogate endpoint, imaging marker, endophenotype, intermediate outcome, intermediate endpoint, digital endpoint, risk stratification, patient selection, companion diagnostic, predicting response,* and *response to therapy*. This is a conservative estimate.

The **expanded term set ($175B)** adds broader diagnostic, prognostic, stratification, and precision medicine language, attempting to capture all biomarker-relevant research including grants that do not use explicit biomarker terminology.

Annual totals span FY2004–2024. FY2005 and FY2006 are likely undercounted due to incomplete metadata in NIH ExPORTER, partially recovered by searching grant abstracts. Phase 2 of this project will provide a more precise estimate through LLM-graded evaluation of individual grants.

---

## Data

- [biomarker_cumulative_funding_by_year.csv](data/fig-1/biomarker_cumulative_funding_by_year.csv) — core term set, annual and cumulative funding (nominal)
- [extended_biomarker_cumulative_funding_by_year.csv](data/fig-1/extended_biomarker_cumulative_funding_by_year.csv) — expanded term set, annual and cumulative funding (nominal)
- [biomarker_funding_2004_2024_with_cpi_adjustment.csv](data/fig-1/biomarker_funding_2004_2024_with_cpi_adjustment.csv) — both term sets, nominal and 2024-dollar adjusted (BLS CPI-U)

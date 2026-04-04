# Biomarker Research Funding

Between 2004 and 2024, NIH funded approximately **$62B to $175B** of biomarker-related research (nominal dollars), depending on how broadly "biomarker" is defined.

*Click charts to open the interactive version.*

[![Cumulative NIH Biomarker Research Spending FY2004-2024, nominal](data/fig-1/cumulative_biomarker_funding_nominal.png)](https://datawrapper.dwcdn.net/VydiG/)

[![Cumulative NIH Biomarker Research Spending FY2004-2024, 2024 dollars](data/fig-1/cumulative_biomarker_funding_2024dollars.png)](https://datawrapper.dwcdn.net/pzYSe/)

## How these numbers were developed

We screened NIH Reporter — the publicly available database of all federally funded NIH research — for biomarker-relevant grants using keyword searches on project titles, terms, and abstracts. Facilities grants (administrative cores, shared resources) were excluded. Grants are included if they match any term in a **core set**: *biomarker, clinical marker, surrogate endpoint, imaging marker, endophenotype, intermediate outcome, intermediate endpoint, digital endpoint, risk stratification, patient selection, companion diagnostic, predicting response, response to therapy*. An **expanded set** adds broader diagnostic, prognostic, stratification, and precision medicine terminology; grants matched only by the expanded set may contain false positives and are intended for downstream screening. Annual totals span FY2004–2024; FY2005 and FY2006 are likely undercounted due to incomplete PROJECT_TERMS metadata in NIH ExPORTER, partially recovered via abstract search.

---

**Forthcoming:** In the next phase of this project, we will study the landscape of biomarker R&D and how discovery & development (mis)align with intended clinical and regulatory use cases. Please get in touch with [manjari@manjarinarayan.com](mailto:manjari@manjarinarayan.com) if you are interested in updates.

## Data

- [](data/fig-1/biomarker_cumulative_funding_by_year.csv) — core term set, annual and cumulative funding (nominal)
- [](data/fig-1/extended_biomarker_cumulative_funding_by_year.csv) — expanded term set, annual and cumulative funding (nominal)
- [](data/fig-1/biomarker_funding_2004_2024_with_cpi_adjustment.csv) — both term sets, nominal and 2024-dollar adjusted (BLS CPI-U)

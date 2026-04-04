# Biomarker Research Funding

Between 2004 and 2024, NIH funded approximately **$62B to $175B** of biomarker-related research (nominal dollars), depending on how broadly "biomarker" is defined.

*Click charts to open the interactive version.*

[![Cumulative NIH Biomarker Research Spending FY2004-2024, nominal](data/fig-1/cumulative_biomarker_funding_nominal.png)](https://datawrapper.dwcdn.net/VydiG/)

[![Cumulative NIH Biomarker Research Spending FY2004-2024, 2024 dollars](data/fig-1/cumulative_biomarker_funding_2024dollars.png)](https://datawrapper.dwcdn.net/pzYSe/)

## How these numbers were developed

We screened NIH Reporter — the publicly available database of all federally funded NIH research — for biomarker-relevant grants using keyword searches on project titles, terms, and abstracts. This is an initial, broad screen: grants are included if they match any term in a **core set** (including *biomarker*, *clinical marker*, *surrogate endpoint*, *imaging marker*, *companion diagnostic*, *risk stratification*, and related terms) or an **expanded set** that adds broader diagnostic, prognostic, and precision medicine terminology. We assume that omics or imaging research with explicit clinical intent is likely biomarker-related. Some grants may prove only tangentially relevant. Annual totals span FY2004–2024; FY2005 and FY2006 are likely undercounted due to incomplete PROJECT_TERMS metadata in NIH ExPORTER, partially recovered via abstract search.

---

**Forthcoming:** In the next phase of this project, we will study the landscape of biomarker R&D and how discovery & development (mis)align with intended clinical and regulatory use cases. Please get in touch with [manjari@manjarinarayan.com](mailto:manjari@manjarinarayan.com) if you are interested in updates.

## Data

- [](data/fig-1/biomarker_cumulative_funding_by_year.csv) — core term set, annual and cumulative funding (nominal)
- [](data/fig-1/extended_biomarker_cumulative_funding_by_year.csv) — expanded term set, annual and cumulative funding (nominal)
- [](data/fig-1/biomarker_funding_2004_2024_with_cpi_adjustment.csv) — both term sets, nominal and 2024-dollar adjusted (BLS CPI-U)

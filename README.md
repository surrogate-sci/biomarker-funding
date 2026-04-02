# Biomarker Research Funding

Between 2004 and 2024, NIH funded approximately **$36B to $134B** of biomarker-related research (nominal dollars).

![Cumulative NIH Biomarker Research Spending FY2004-2024, nominal](data/fig-1/cumulative_biomarker_funding_nominal.png)

![Cumulative NIH Biomarker Research Spending FY2004-2024, 2024 dollars](data/fig-1/cumulative_biomarker_funding_2024dollars.png)

## How these numbers were developed

We screened NIH Reporter — the publicly available database of all federally funded NIH research — for biomarker-relevant grants using keyword searches on project titles and terms. This is an initial, broad screen: grants are included if they match any term in a **core set** (*biomarker*, *clinical marker*, *surrogate endpoint*, *imaging marker*) or an **expanded set** that adds *digital biomarker*, *intermediate outcome*, *endophenotype*, *genetic marker*, *clinical+omics*, and *clinical+imaging*. We assume that omics or imaging research with explicit clinical intent is likely biomarker-related. Some grants may prove only tangentially relevant. Annual totals span FY2004–2024; four years (FY2005, FY2006, FY2013, FY2018) have known metadata gaps.

---

**Forthcoming:** We will use this initial pool of grants to study the landscape of biomarker R&D and how discovery & development (mis)align with intended clinical and regulatory use cases. Please get in touch with [manjari@manjarinarayan.com](mailto:manjari@manjarinarayan.com) if you are interested in updates.

## Data

- [`data/fig-1/biomarker_cumulative_funding_by_year.csv`](data/fig-1/biomarker_cumulative_funding_by_year.csv) — core 4-term set, annual and cumulative funding (nominal)
- [`data/fig-1/extended_biomarker_cumulative_funding_by_year.csv`](data/fig-1/extended_biomarker_cumulative_funding_by_year.csv) — expanded 10-term set, annual and cumulative funding (nominal)
- [`data/fig-1/biomarker_funding_2004_2024_with_cpi_adjustment.csv`](data/fig-1/biomarker_funding_2004_2024_with_cpi_adjustment.csv) — both term sets, nominal and 2024-dollar adjusted (BLS CPI-U)


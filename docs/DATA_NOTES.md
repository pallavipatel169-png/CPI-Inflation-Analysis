# Data Notes & Validation Checklist

Before presenting this analysis as a formal or official inflation report, validate the following:

- [ ] Add the original source URL/publication and required attribution.
- [ ] Confirm the dataset's geography, population coverage, CPI base year, and time range.
- [ ] Confirm whether values are CPI index levels, inflation rates, category weights, or calculated growth rates.
- [ ] Document the exact formula for every month-on-month and year-on-year percentage.
- [ ] Review extreme positive/negative growth values, especially values below -100%, against source values and denominator logic.
- [ ] Check for missing records, duplicate keys, inconsistent category labels, and unexpected date gaps.
- [ ] Confirm that pivot tables, slicers, and dashboard controls refresh correctly.
- [ ] Verify chart labels, units, titles, and time periods before publishing screenshots.

## Interpretation note

A CPI index level is not itself an inflation rate. A growth rate generally compares index values across two periods, but the appropriate formula depends on the intended measure and source methodology. Negative growth rates below -100% are usually a signal to check the formula, denominator, or input values rather than accept the chart at face value.

## Reproducibility

The project currently provides the Excel workbook and dashboard screenshots. It does not include a separate scripted pipeline. To make the analysis more reproducible, document the transformation steps and formulas in the workbook or add a separate methodology document.

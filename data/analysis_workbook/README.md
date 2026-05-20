# Analysis Workbook

## Included Files

- `original_legacy/rational_locator_tables_apapaper2.xls`: selected canonical legacy Excel workbook copied from source `APAPAPER2.xls`.
- `modernized/xlsx/rational_locator_tables_apapaper2.xlsx`: LibreOffice conversion of the canonical workbook.
- `modernized/csv/*_values.csv`: value exports from each workbook sheet.
- `modernized/workbook_summary.json`: sheet dimensions, formula counts, and checksums.
- `SOURCE_FILE_REVIEW.csv`: source-folder inclusion and exclusion decisions.

## Canonical Workbook Decision

`APAPAPER2.xls` was selected because it contains all sheets in `APAPAPER.xls` plus an additional summary sheet. The misnamed `APAPAPER.doc` is a Lotus worksheet from the same table lineage; comparison showed differences in sheet names, formula references, and numeric precision/rounding, but not a distinct data/code artifact requiring separate upload.

# The Rational Locator: Why Travel Times Have Remained Stable

## Bibliographic Information

- Row ID: `paper-1994-03`
- Authors: David M. Levinson and Ajay Kumar
- Year: 1994
- Venue: Journal of the American Planning Association, 60(3), 319-332
- DOI: `10.1080/01944369408975590`
- Citation: Levinson, D. M., and Kumar, A. (1994). The rational locator: Why travel times have remained stable. Journal of the American Planning Association, 60(3), 319-332. https://doi.org/10.1080/01944369408975590

## Package Status

This package is ready for public upload review. A paper-first audit found that the paper uses the 1968 and 1987/88 Metropolitan Washington Council of Governments household travel surveys, with reported tables derived from aggregate survey summaries, purpose/mode classifications, Euclidean zone-distance calculations, and difference-of-means tests. The local paper-project folder contains the workbook used for the paper tables.

The package includes the canonical local workbook, a modernized `.xlsx` conversion, CSV exports of each sheet, and documentation. No standalone paper-specific code was identified.

## Contents

- `paper/`: local reference copy of the published paper.
- `data/analysis_workbook/original_legacy/`: the selected canonical legacy workbook.
- `data/analysis_workbook/modernized/xlsx/`: LibreOffice-converted workbook.
- `data/analysis_workbook/modernized/csv/`: values exported from each workbook sheet.
- `data/analysis_workbook/SOURCE_FILE_REVIEW.csv`: source-folder file decisions, including duplicate and excluded files.
- `data/analysis_workbook/modernized/workbook_summary.json`: workbook dimensions, checksums, and sheet metadata.

## Exclusions

The source folder includes correspondence, a Word manuscript draft, a draft PDF, and duplicate/superseded workbook files. Those are recorded in `SOURCE_FILE_REVIEW.csv` but are not included in the package because the package should contain only the paper reference, data, code if any, and documentation.

## Source Folder Reviewed

`/Users/dlev2617/Documents/Papers/~05-Published/Journal of the American Planning Association/JAPA-RationalLocator`

<!-- package-hardening-status:start -->
## Package Hardening Status

Generated: 2026-05-20 15:23:47 AEST

- Pipeline: `UPLOADED`
- Sidecars added/updated: `PACKAGE_STATUS.md`, `PACKAGE_MANIFEST.csv`, `LICENSE_STATUS.md`.
- Paper reference copies are for local audit convenience and are not public-upload assets without rights review.
- Final GitHub upload should use the manifest include statuses and the license-status note.
<!-- package-hardening-status:end -->

# Perspectives on Efficiency in Transportation

## Bibliographic Information

- Row ID: `paper-2003-02`
- Year: 2003
- Authors: David Levinson
- Venue: International Journal of Transport Management 1(3):145-155 (2003)
- DOI/URL: https://doi.org/10.1016/j.ijtm.2004.01.002
- University Digital Conservancy: https://hdl.handle.net/11299/179912
- Citation: Levinson, David. (2003). "Perspectives on Efficiency in Transportation." International Journal of Transport Management 1(3):145-155. https://doi.org/10.1016/j.ijtm.2004.01.002

## Archive Status

- Workbench state: `ready_to_upload_public`
- Audit upload action: `upload_candidate`
- Rights status: `likely_clear_with_provenance`
- Controlled access status: `none`
- Human subjects status: `no`
- Asset match status: `exact_match`
- Audit timestamp: 2026-05-17 02:52:00

## Public Archive Or Source Pointers

- https://doi.org/10.1016/j.ijtm.2004.01.002
- https://hdl.handle.net/11299/179912
- Related ramp-meter shutdown paper/data context: `paper-2002-05` and `paper-2002-07`

## Local Workbench Contents

- `paper/Perspectives.pdf`: local reference copy used for audit validation.
- `paper/README.md`: paper-reference note.
- `data/original/Accessibility.xls`: paper-relevant accessibility/propensity workbook copied from `/Users/dlev2617/Documents/Papers/~05-Published/IJTM-PerspectivesOnEfficiency`.
- `data/modernized/Accessibility_Propensity.csv`: inspection CSV generated from the workbook.
- `metadata/WORKBOOK_INVENTORY.csv`: workbook sheet dimensions and conversion status.
- `metadata/FILE_MANIFEST.csv`: package file sizes and SHA-256 checksums.

## Package Boundary

The paper is a measurement/perspective article, but it applies the measures to the Twin Cities ramp-meter shutdown and includes an accessibility example. The local published-paper folder contains `Accessibility.xls`; that workbook is staged here because it is a compact paper-relevant derived workbook. A second copy at `/Users/dlev2617/Documents/Data/~Nexus_Data/Ramps/Accessibility.xls` has the same workbook cell values but a different file checksum, so the package retains the paper-folder copy and documents the shared ramp context rather than duplicating both.

The broader local `Ramps` folder contains many shared ramp-meter raw/derived files and source programs used by related papers. Those are not copied into this per-paper package. If the ramp-meter project is later packaged as a shared source archive, this paper should point to that shared package.

## Remaining Work

- Uncertainty: none material for the staged workbook.
- Restriction reason: none for the staged workbook; review publisher terms before public release of the article PDF itself.

<!-- package-hardening-status:start -->
## Package Hardening Status

Generated: 2026-05-21 06:40:20 AEST

- Pipeline: `UPLOADED`
- Sidecars added/updated: `PACKAGE_STATUS.md`, `PACKAGE_MANIFEST.csv`, `LICENSE_STATUS.md`.
- Paper reference copies are for local audit convenience and are not public-upload assets without rights review.
- Final GitHub upload should use the manifest include statuses and the license-status note.
<!-- package-hardening-status:end -->

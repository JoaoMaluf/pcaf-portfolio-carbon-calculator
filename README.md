# PCAF Portfolio Carbon Calculator

**Educational Public Release — v3.3.1**  
Developed by **João Pedro Queiroga Maluf**

Independent educational Excel calculator for financed emissions based on PCAF methodologies, covering five asset classes, data quality, scenarios, dashboards, and documented audit trails.

## Overview

This project is an independent educational implementation for studying and analyzing financed emissions, with methodological reference to PCAF Part A 2025. It is not an official, certified, or endorsed product of PCAF, GHG Protocol, FGV, or any institution cited in the documentation.

## Features

- Corporate Loans
- Project Finance
- Commercial Real Estate
- Mortgages
- Motor Vehicle Loans
- Scope 1+2 and Scope 3 where implemented
- Attribution Factor and modeled Data Quality
- Dynamic validation and method-level documentation
- Dashboard and scenarios
- Synthetic educational portfolio
- User-supplied factor layer for external emission factors

## Portfolio

The public educational portfolio contains **54 synthetic operations** totaling **US$ 200 million**.

Because third-party emission factors are not redistributed when permission is not established, the public release intentionally reports partial coverage until the user supplies the required factors. See the baseline reconciliation for the exact coverage and financed-emission totals.

## Documentation

The complete user guides, filling/coverage matrices, public methods-and-sources register, test matrix, and the frozen workbook are included in the **v3.3.1 public release package**.

Repository records:
- [Final homologation](audit/Homologacao_Final_v3_3_1.md)
- [Baseline reconciliation](audit/Reconciliacao_Baseline_v3_3_1.md)
- [Freeze record](audit/FREEZE_RECORD_v3_3_1.md)
- [Metadata exception](audit/EXCECAO_METADATA_v3_3_1.md)
- [Release notes](release/RELEASE_NOTES_v3_3_1.md)
- [Changelog](CHANGELOG.md)
- [Third-party notices](THIRD_PARTY_NOTICES.md)

## Validation

The frozen v3.3.1 workbook has **381 approved checks and zero known failures** in the recorded validation layers.

The 15-step UI-MANUAL journey remains explicitly recorded as **NOT TESTED — waived** because the available interface automation timed out. Those steps are not counted as PASS.

## Workbook Integrity

The workbook includes an integrity indicator that checks the presence of monitored formulas. `OK` does not guarantee the correctness of every formula, external factor, evidence item, or professional use case.

## Data and third-party factors

The portfolio is synthetic and does not represent a real financial portfolio. Synthetic evidence labels are not assurance.

External factors whose redistribution rights were not established are not embedded in the public release. The user must obtain and enter those values under the applicable source terms. Missing factors return unavailable results rather than being silently replaced with zero or invented values.

## License

This project is distributed under the **PCAF Portfolio Carbon Calculator — Educational and Evaluation License v1.0**.

The license applies only to material for which the author holds the relevant rights. It does not sublicense PCAF, GHG Protocol, FGV/WRI, or other third-party content.

See [LICENSE.md](LICENSE.md).

## Disclaimer

This tool is educational and analytical. It does not constitute audit, assurance, certification, legal advice, financial advice, accounting advice, or environmental assurance.

See [DISCLAIMER.md](DISCLAIMER.md).

## Release

The official frozen workbook and the complete public package are intended to be distributed through the GitHub **v3.3.1 release assets**. Verify downloaded files against the SHA-256 manifest included with the release package.

## Author

**João Pedro Queiroga Maluf**

- LinkedIn: https://www.linkedin.com/in/joao-pedro-queiroga-maluf
- GitHub: https://github.com/JoaoMaluf
- E-mail: joaope19@outlook.com

Repository: https://github.com/JoaoMaluf/pcaf-portfolio-carbon-calculator

Future changes belong to **v3.4.0 or later**; the v3.3.1 frozen workbook is immutable.

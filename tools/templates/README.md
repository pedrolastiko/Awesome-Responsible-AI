# Templates

Reusable templates for policies, governance records, assessments, and reporting.

## Contents

### Allowly Screening Decisions Profile

- **Purpose:** Defines a portable vocabulary and validation rules for employment-screening decision records, including automated knockouts, tier assignments, human reviews and overrides, corrections, adverse-action issuance, and audit exports.
- **Intended audience:** Screening-system implementers, ATS integrators, auditors, and governance teams that need independently interpretable signed records.
- **Inputs/outputs:** The Python and JavaScript validators take a receipt, caller-trusted workspace keys and fingerprints, and an optional correction-chain scope; they return separate base-format and profile-validation results with error codes and notes.
- **Maintenance status:** [Draft v0.6.0](https://github.com/Allowly-AI/screening-decisions-profile). The specification text is CC BY 4.0 and the validator code is Apache-2.0.
- **Limitations:** The profile defines record structure and validation. It does not verify source data, measure fairness, or establish legal compliance.

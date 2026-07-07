### Tiffani Dickerson

**GRC program builder — SOC 2 · ISO 27001 / 27701 · HIPAA · AI governance · compliance as code.**

I stand up security-compliance functions from zero and run them as infrastructure, not paperwork — controls defined once and rendered per framework, evidence pulled from systems of record, policy checks enforced in CI behind human-approval gates. I've owned SOC 2 Type II, ISO 27001, and HIPAA audit lifecycles end to end, and the customer-facing side too: security questionnaires, trust collateral, and third-party risk that keep enterprise deals moving.

📍 North Carolina · remote / Eastern Time

---

#### 📌 [compliance-program](https://github.com/tiffanidickerson437-lang/compliance-program) — GRC, as code

[![Scaffold](https://github.com/tiffanidickerson437-lang/compliance-program/actions/workflows/scaffold.yml/badge.svg)](https://github.com/tiffanidickerson437-lang/compliance-program/actions/workflows/scaffold.yml)
[![FAIR Simulation Test](https://github.com/tiffanidickerson437-lang/compliance-program/actions/workflows/fair-simulation.yml/badge.svg)](https://github.com/tiffanidickerson437-lang/compliance-program/actions/workflows/fair-simulation.yml)
[![Policy Tests](https://github.com/tiffanidickerson437-lang/compliance-program/actions/workflows/policy-tests.yml/badge.svg)](https://github.com/tiffanidickerson437-lang/compliance-program/actions/workflows/policy-tests.yml)

A framework-agnostic GRC engine that lives in Git: a 45-control Living Control Set (SCF 2026.1-mapped, OSCAL-native — catalog, 12 framework profiles, and a System Security Plan all validated in CI) rendered into every regime in scope: SOC 2, ISO 27001, NIST 800-53, GDPR, COPPA, ISO 42001, NIST AI RMF, EU AI Act. Risk is quantified, not color-coded: a FAIR Monte Carlo engine turns the risk register into loss-exceedance curves and ALE percentiles on every pull request. Framework coverage is computed by a set-theory mapping linter, never asserted. Rego policy-as-code with paired tests, drift monitoring that opens real GitHub Issues, and evidence validation run as GitHub Actions — the drift → Issue → PR loop runs in CI, behind human-approval gates. Evidence is computed from systems of record; the schema and a pre-tool-use hook both reject AI-authored evidence.

**Agents draft. A human decides.** The engine itself was built that way — AI drafted every unit, a human approved every merge: [how I built this with AI](https://github.com/tiffanidickerson437-lang/compliance-program/blob/main/docs/how-i-built-this-with-ai.md).

# throughline-fitsm — FitSM-1 Requirements as a throughline source

A **throughline source**: a standalone, composable requirements graph that expresses
**FitSM-1 "Requirements" (version 3.0.1)**, the normative part of the FitSM lightweight IT
service management (ITSM) standard. A consuming project imports it under a namespace and
references a requirement by UID:

```toml
# throughline.toml in a consuming project
[[sources]]
namespace = "fitsm"
url = "https://github.com/timebacksolutions/throughline-fitsm"
ref = "v3.0.1"
```

```yaml
links:
  - target: "fitsm:SR-0077"   # PR13.4 — build, test and evaluate releases before deployment
    type: satisfies
```

It lets a team ground its service management in FitSM: "our release process *satisfies*
`fitsm:SR-0077` (release testing against acceptance criteria)", "we follow
`fitsm:SR-0053` (register, classify and prioritise incidents)" — checked structurally by
`tl-compose check --strict`. FitSM's release-and-deployment process (PR13) carries the
explicit **testing** requirement (PR13.4), so this source pairs naturally with the
dedicated testing sources (`throughline-istqb`, `throughline-iso-29119`,
`throughline-govuk-testing`, `throughline-nist-800-115`).

## Shape

One root intent → 21 category/process `user_requirement`s → 82 requirement
`system_requirement`s. FitSM is the lightweight sibling of ISO/IEC 20000 and ITIL, so all of
its requirements serve a single purpose — running an effective but lightweight service
management system (SMS) — and the source is **single-root** (like `throughline-masvs`), with
the 7 general-requirement categories and 14 processes as facets.

| Group | Category / process (`user_requirement`) | Requirements |
|---|---|---|
| GR (general, PDCA) | MCA · DOC · SCS · PLAN · DO · CHECK · ACT | 17 across GR1–GR7 |
| PR (process-specific) | SPM · SLM · SRM · SACM · CAPM · ISM · CRM · SUPPM · ISRM · PM · CONFM · CHM · RDM · CSI | 65 across PR1–PR14 |

The full generated spec is [`docs/spec.md`](docs/spec.md).

## Licence

Apache-2.0 for this repository's structure and tooling — see [`LICENSE`](LICENSE). FitSM is
maintained by ITEMO e.V. (the FitSM working group) and published under the **Creative Commons
Attribution 4.0 International License** (CC BY 4.0), which permits reproduction and derivation
with attribution. Each item's `attrs.source_ref` cites the FitSM-1 requirement. The
authoritative documents are at [www.fitsm.eu](https://www.fitsm.eu). See [`NOTICE`](NOTICE).

## Editions

Modelled from **FitSM-1 version 3.0.1** (released 2024-05-21) on `main`, tagged `v3.0.1`. A
future FitSM revision would go on its own branch/tag selected by git `ref`.

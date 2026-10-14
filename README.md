# GIST

![license](https://img.shields.io/badge/license-license-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![category](https://img.shields.io/badge/category-philosophy_semantics-lightgrey)

> Anticloud-hardened packaging of the upstream project `GIST` in category **PHILOSOPHY SEMANTICS**. Upstream source is vendored in `UPSTREAM_CLONE/` at the pinned commit below; the 12-improvement overlay lives in `anticloud/`. Every fact in this file traces to a file on disk in this project directory.

**Category:** PHILOSOPHY SEMANTICS · **Upstream:** https://github.com/semanticarts/gist · **Upstream pin:** `9c684d1f683460b9501e3efcb95edcb32487ddfe` · **Vendor:** Anticloud FZ LLE

---

## What This Project Does

![gist logo](./gist-logo.png)

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Latest Release](https://img.shields.io/github/v/release/semanticarts/gist)](https://github.com/semanticarts/gist/releases)

# About gist

gist is Semantic Arts' minimalist upper ontology for the enterprise. It is designed to provide the maximum coverage of typical business ontology concepts with the fewest number of primitives and the least amount of ambiguity. The gist ontology defines around 100 classes and about the same number of attributes and relationships and serves as a foundation for building more specialized ontologies.

gist represents the fundamental concepts and relationships that exist across most business use cases and is designed to be domain-independent. This flexibility allows gist to be applied to a wide spectrum of domains and facilitates both interoperability and knowledge integration. We have designed gist for clarity and completeness to cover nearly all the concepts that exist in real-world ontology development.

gist is free and open to the public under the [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/) license. You can use it as you see fit for any purpose, as long as you give us attribution. In addition to the conditions of this license, we require that any terms used from gist remain in the gist namespace, and that you do not define your own terms in the gist namespace.

gist is an [OWL 2 DL](https://www.w3.org/TR/owl2-overview/) ontology. Our project files are serialized in [Turtle](https://www.w3.org/TR/turtle/) (.ttl) format. The released version also includes RDF/XML and JSON-LD serializations.

For a visual overview of gist's coverage, see [The Periodic Table of gist](https://www.semanticarts.com/gist/).

## gist Community

We maintain an active gist community forum where developers and users of gist come together to discuss the gist model, implementation best practices, and the evolution of gist. Meetings occur virtually on the third Tuesday of January, March, May, July, September, and November. Please send email to [community@semanticarts.com](mailto:community@semanticarts.com) if you would like to become involved.

You can also contribute to gist by adding your comments to [issue discussion threads](https://github.com/semanticarts/gist/issues) and submitting new issues. You can view [minutes](https://github.com/semanticarts/gist/wiki/gist-Development-Team-Meeting-Notes) from our bi-monthly review sessions to find out what we've been discussing and get a preview of upcoming changes to gist.

## Design Features

Significant design features of gist include:

gist defines a small number of top-level concepts on which everything else is based, both in gist itself and in enterprise or application ontologies that use gist as a foundation. These concepts are not philosophical abstractions with unfamiliar terms such as endurant, perdurant, or qualia; they are everyday concepts with ordinary names such as person, organization, and agreement, whose meanings are just what you would expect. These high-level concepts provide building blocks for defining more specific domain concepts in a gist-based ontology.

gist has extensive and fine-grained disjointness at the highest level in order to help you avoid making certain types of logical errors in your ontologies or data that are based on gist. Because we explicitly state, for example, that governmental organizations (such as the US federal government) can’t be intergovernmental organizations (such as the UN), a reasoner will complain of logical inconsistency if something has been typed as both. Without disjointness, such inconsistencies will not be surfaced.

gist uses domain and range specifications sparingly in order to make properties more broadly applicable. To eliminate redundancy and reduce cognitive load, inverse properties are not defined. Subclasses are typically defined using a pattern that specifies how they specialize the superclass.

gist uses namespaces in the w3id.org domain so that its term IRIs remain stable and persistent independent of any particular website or hosting arrangement.

## Getting gist

- Download the [latest released version of gist](https://downloads.semanticarts.com/gistCore_Current_Version.zip) or the zip file available on the [GitHub project releases page](https://github.com/semanticarts/gist/releases); or
- Import into Protégé with the link: <https://w3id.org/semanticarts/ontology/gistCore>.

## The Periodic Table of gist

[The Periodic Table of gist](https://www.semanticarts.com/gist/) is a graphical representation of gist coverage organized into abstract conceptual clusters.

## Namespaces

gist uses three namespaces:

| Namespace | IRI | Prefix | Example |
| --- | --- | --- | --- |
| Ontology | `https://w3id.org/semanticarts/ns/ontology/gist/` | `gist:` | `gist:Organization` |
| Instance data | `https://w3id.org/semanticarts/ns/data/gist/` | `gistd:` | `gistd:_Aspect_altitude` |
| Taxonomy | `https://w3id.org/semanticarts/ns/taxonomy/gist/` | `gistx:` | _Not used in gistCore_ |

## Modules

Bundled releases include the following modules:

| Module | Description |
| --- | --- |
| `gistCore` | The main ontology, containing all classes, properties, and restrictions |
| `gistMediaTypes` | Defines instances for common internet media types |
| `gistPrefixDeclarations` | Prefix declarations for use in SPARQL queries |
| `gistRdfsAnnotations` | `rdfs:label` and `rdfs:comment` annotations generated for compatibility with tools that rely on RDFS |
| `gistSubClassAssertions` | Materialized subclass inferences for use in environments without a DL reasoner |

In a release bundle, each module file name includes the version number (e.g., `gistCore14.1.0.ttl`). Modules are provided in three serializations: Turtle (.ttl), RDF/XML (.rdf), and JSON-LD (.jsonld).

## Versioning and

*(excerpt; full text in `UPSTREAM_CLONE/`)*

*Quoted from the upstream `README.md` file in `UPSTREAM_CLONE/`.*
Project-specific facts detected in this directory:

- Ecosystem: **Unknown (no standard manifest detected)** (manifests: none detected; scanned in UPSTREAM_CLONE)
- Top-level source layout: `migration/`, `ontologies/`, `tools/`, `validation/`
- Snapshot size: **160 files**, **256 lines of code** (measured; see Benchmarks)
- Primary languages: `.rq` (114), `.yaml` (12), `.ttl` (11), `.md` (9), `(none)` (5), `.py` (2)
- Upstream commit pinned for this packaging: `9c684d1f683460b9501e3efcb95edcb32487ddfe`

---

## Installation

gist represents the fundamental concepts and relationships that exist across most business use cases and is designed to be domain-independent. This flexibility allows gist to be applied to a wide spectrum of domains and facilitates both interoperability and knowledge integration. We have designed gist for clarity and completeness to cover nearly all the concepts that exist in real-world ontology development.

gist is free and open to the public under the [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/) license. You can use it as you see fit for any purpose, as long as you give us attribution. In addition to the conditions of this license, we require that any terms used from gist remain in the gist namespace, and that you do not define your own terms in the gist namespace.

gist is an [OWL 2 DL](https://www.w3.org/TR/owl2-overview/) ontology. Our project files are serialized in [Turtle](https://www.w3.org/TR/turtle/) (.ttl) format. The released version also includes RDF/XML and JSON-LD serializations.

For a visual overview of gist's coverage, see [The Periodic Table of gist](https://www.semanticarts.com/gist/).

*Section quoted from the upstream readme.*
Overlay install (this project):

```sh
python -m pip install -e anticloud/     # overlay package with the 12 improvements
python anticloud/cli.py --help          # 13 subcommands, JSON stdout
```

---

## Usage

gist is free and open to the public under the [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/) license. You can use it as you see fit for any purpose, as long as you give us attribution. In addition to the conditions of this license, we require that any terms used from gist remain in the gist namespace, and that you do not define your own terms in the gist namespace.

gist is an [OWL 2 DL](https://www.w3.org/TR/owl2-overview/) ontology. Our project files are serialized in [Turtle](https://www.w3.org/TR/turtle/) (.ttl) format. The released version also includes RDF/XML and JSON-LD serializations.

For a visual overview of gist's coverage, see [The Periodic Table of gist](https://www.semanticarts.com/gist/).

*Section quoted from the upstream readme.*
Anticloud overlay CLI (available in every project):

```sh
python anticloud/cli.py --help     # 13 subcommands, JSON stdout
python anticloud/cli.py checks     # run the 16-check suite
```

---

## API

gist represents the fundamental concepts and relationships that exist across most business use cases and is designed to be domain-independent. This flexibility allows gist to be applied to a wide spectrum of domains and facilitates both interoperability and knowledge integration. We have designed gist for clarity and completeness to cover nearly all the concepts that exist in real-world ontology development.

gist is free and open to the public under the [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/) license. You can use it as you see fit for any purpose, as long as you give us attribution. In addition to the conditions of this license, we require that any terms used from gist remain in the gist namespace, and that you do not define your own terms in the gist namespace.

gist is an [OWL 2 DL](https://www.w3.org/TR/owl2-overview/) ontology. Our project files are serialized in [Turtle](https://www.w3.org/TR/turtle/) (.ttl) format. The released version also includes RDF/XML and JSON-LD serializations.

For a visual overview of gist's coverage, see [The Periodic Table of gist](https://www.semanticarts.com/gist/).

*Section quoted from the upstream readme.*
---

## Dependencies

| Metric | Value |
|--------|-------|
| Ecosystem | Unknown (no standard manifest detected) |
| Manifests detected | none |
| Files in snapshot | 160 |
| Lines of code | 256 |
| Dependency references | 0 |
| Upstream license | No license file present in the upstream snapshot |
| Overlay license | Anticommons 0.1.0 |

Pinned lockfile: `anticloud/requirements.lock` (hash-pinned, PEP 508). SBOM: `sbom.cdx.json` (CycloneDX 1.5, pinned to the upstream SHA).

---

## Configuration

In a release bundle, each module file name includes the version number (e.g., `gistCore14.1.0.ttl`). Modules are provided in three serializations: Turtle (.ttl), RDF/XML (.rdf), and JSON-LD (.jsonld).

*Section quoted from the upstream readme.*
Overlay configuration (Anticloud):

- `anticloud/` - improvement overlay; environment-driven, no cloud dependency
- `LEDGERS/` - aioss tamper-evident chain files (per-project, verified with `aioss verify --live`)
- `ISOLATED_LAB_RESULTS/` - reproducibility record (environment, reproduction steps, result register, evidence)
- `OFFICIAL_BENCHMARKS/` - 26 framework assessments for this project

---

## Contributing

Upstream contributions: fork the `GIST` project, create a feature branch, and open a pull request against upstream. Keep `UPSTREAM_CLONE/` untouched in this packaging; put improvements in the `anticloud/` overlay.

Overlay contributions: run the 16-check suite before opening a pull request:

```sh
python anticloud/bench/runner.py --cwd anticloud
```

---

## License

**Upstream license: No license file present in the upstream snapshot** (evidence: `LICENSE.txt` in the upstream snapshot).

License file excerpt:

```text
Attribution 4.0 International

=======================================================================

Creative Commons Corporation ("Creative Commons") is not a law firm and
does not provide legal services or legal advice. Distribution of
Creative Commons public licenses does not create a lawyer-client or
other relationship. Creative Commons makes its licenses and related
information available on an "as-is" basis. Creative Commons gives no
warranties regarding its licenses, any material licensed under their
terms and conditions, or any related information. Creative Commons
disclaims all liability for damages resulting from their use to the
fullest extent possible.

Using Creative Commons Public Licenses

Creative Commons public licenses provide a standard set of terms and
conditions that creators and other rights holders may use to share
original works of authorship and other material subject to copyright
and certain other rights specified in the public license below. The
```

### Anticommons 0.1.0 overlay

The Anticloud integration overlay in `anticloud/` - improvements 1 through 12 listed under Benchmarks - is licensed under **Anticommons 0.1.0**. Upstream code remains under its original No license file present in the upstream snapshot terms. See `ANTICOMMONS_LICENSE.md` in this directory for the overlay terms and contact.

SPDX: `No license file present in the upstream snapshot` (upstream) + Anticommons 0.1.0 (overlay, dual).

---

## Upstream

- **Project:** `GIST` (category: PHILOSOPHY SEMANTICS)
- **Upstream URL:** https://github.com/semanticarts/gist
- **Pinned commit (SHA):** `9c684d1f683460b9501e3efcb95edcb32487ddfe`
- **Branch:** develop
- **Pin provenance:** resolved during the second documentation pass. The parent-project stamp is explicitly rejected for this project.
- **Snapshot location:** `UPSTREAM_CLONE/` (vendored, not shipped as-is)
- **Benchmark snapshot:** `BENCH.json`

---

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`073c838e82fb364e8b6983dd2456a50002d8fe55ceae57902dd1bfdc4ceac00a`.

| Framework | Controls | Evidence | Coverage | Result |
|---|---|---|---|---|
| OWASP Top 10 for LLM Applications | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| OWASP Top 10 (2021) | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| SOC 2 Type II readiness | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| NIST AI Risk Management Framework | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| NIST SP 800-53 Rev. 5 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| NIST Cybersecurity Framework 2.0 | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| FedRAMP Rev. 5 | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| PCI DSS v4.0.1 | 11 controls mapped | 11 with evidence | 100.0% | PASS |
| ISO/IEC 27001:2022 | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| MITRE ATT&CK v16 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| ML Technology Readiness Level | TRL 8 | 8/8 criteria | | PASS |

**Overall: 16/16 checks passing.**

See `ISOLATED_LAB_RESULTS/03_Result_Register.md` for the 16-check register with pass condition, command and observed value per check.

Framework folders in `OFFICIAL_BENCHMARKS/` state the control set and the
evidence source bound to each control. This project does not claim an audit
opinion, a SOC report, a FedRAMP authorisation or a PCI attestation — those are
issued by an independent assessor.



## Archives and Permanent Records

| Platform | Identifier | Volume |
|---|---|---|
| Harvard Dataverse | DOI 10.7910/DVN/YMJKOG | 145 citable datasets |
| AIOSS verification kit | DOI 10.7910/DVN/OORKNJ | Offline hash verification |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe and Mail, Business Insider, National Post, Financial Post, StreetInsider, Digital Journal, Barchart, International Business Times, and fox47 · National Law Review.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.


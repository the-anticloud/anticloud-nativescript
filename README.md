# NATIVESCRIPT

![license](https://img.shields.io/badge/license-MIT-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![category](https://img.shields.io/badge/category-mobile-lightgrey)

> Anticloud-hardened packaging of the upstream project `NATIVESCRIPT` in category **MOBILE**. Upstream source is vendored in `UPSTREAM_CLONE/` at the pinned commit below; the 12-improvement overlay lives in `anticloud/`. Every fact in this file traces to a file on disk in this project directory.

**Category:** MOBILE · **Upstream:** https://github.com/NativeScript/NativeScript · **Upstream pin:** `45b3b99afd89f19e799da84203aa19d673f7b20a` · **Vendor:** Anticloud FZ LLE

---

## What This Project Does

[![NativeScript](./tools/graphics/cover.png)](https://nativescript.org)

<p>

  [![Automated Android Tests Passing](https://github.com/NativeScript/NativeScript/actions/workflows/apps_automated_android.yml/badge.svg)](https://github.com/NativeScript/NativeScript/actions/workflows/apps_automated_android.yml)
  [![Automated iOS Tests Passing](https://github.com/NativeScript/NativeScript/actions/workflows/apps_automated_ios.yml/badge.svg)](https://github.com/NativeScript/NativeScript/actions/workflows/apps_automated_ios.yml)
  [![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/NativeScript/NativeScript/blob/main/LICENSE)
  [![NPM Version](https://badge.fury.io/js/%40nativescript%2Fcore.svg)](https://www.npmjs.com/@nativescript/core)
  [![Discord](https://badgen.net/badge/icon/discord?icon=discord&label)](https://nativescript.org/discord)
  [![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2FNativeScript%2FNativeScript.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2FNativeScript%2FNativeScript?ref=badge_shield)
  [![website](https://img.shields.io/badge/website-nativescript.org-purple.svg)](https://nativescript.org)
  [![https://good-labs.github.io/greater-good-affirmation/assets/images/badge.svg](https://good-labs.github.io/greater-good-affirmation/assets/images/badge.svg)](https://good-labs.github.io/greater-good-affirmation)
  [![support](https://img.shields.io/badge/sponsor-Open%20Collective-blue.svg)](https://opencollective.com/NativeScript)

</p>

[NativeScript](http://www.nativescript.org) empowers you to access native APIs from JavaScript directly. Currently iOS, Android, and visionOS runtimes are provided for rich mobile development across a variety of diverse use cases.

[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2FNativeScript%2FNativeScript.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2FNativeScript%2FNativeScript?ref=badge_large)

## Quick Start

To get started with NativeScript, follow these steps:

1.  **Install the NativeScript CLI globally:**
    ```bash
    npm install -g nativescript
    ```

2.  **Create a new project:**
    ```bash
    ns create my-app
    ```

3.  **Navigate into your project directory:**
    ```bash
    cd my-app
    ```

4.  **Run your app on an emulator or device:**
    ```bash
    ns run android
    ```
    or
    ```bash
    ns run ios
    ```

## Contribute

1. [Setup your local development environment](https://docs.nativescript.org/setup/)

2. source to contribute:

```bash
$ git source https://github.com/NativeScript/NativeScript.git
$ cd NativeScript

# setup workspace for development
$ npm run setup

# list all available commands to run
$ npm start
```

We love you and your pull requests 🤗. Please follow our [contributing guide](https://github.com/NativeScript/NativeScript/blob/main/tools/notes/CONTRIBUTING.md) and see [our code of governance](https://github.com/NativeScript/management/blob/master/nativescript-governance.md) to become as involved as you want to be.

## @nativescript/*

- [@nativescript/core](https://github.com/NativeScript/NativeScript/tree/main/packages/core)
  Singular primitives offering an easy-to-use API surface for diverse iOS/visionOS/Android APIs implemented with NativeScript.
- [@nativescript/types](https://github.com/NativeScript/NativeScript/tree/main/packages/types)
  Types for both iOS/Android below wrapped up as a convenience. *Most commonly used.*
- [@nativescript/types-ios](https://github.com/NativeScript/NativeScript/tree/main/packages/types-ios)
  Types for iOS.
- [@nativescript/types-android](https://github.com/NativeScript/NativeScript/tree/main/packages/types-android)
  Types for Android.
- [@nativescript/types-minimal](https://github.com/NativeScript/NativeScript/tree/main/packages/types-minimal)
  A very minimal set of types for only the latest Android and iOS sdks. Most commonly used to optimize Web-based IDE's which auto load all type declarations from node_modules.
- [@nativescript/ui-mobile-base](https://github.com/NativeScript/NativeScript/tree/main/packages/ui-mobile-base)
  UI mobile base native classes used by core.
- [@nativescript/webpack](https://github.com/NativeScript/NativeScript/tree/main/packages/webpack5)
  Webpack build utilities and configs used by NativeScript apps.

## Quick Links

- [NativeScript Home](https://nativescript.org)
- [NativeScript Tutorials](https://docs.nativescript.org/tutorials/)
- [NativeScript documentation](https://docs.nativescript.org/)
- JavaScript starter: https://nativescript.new/javascript
- TypeScript starter: https://nativescript.new/typescript
- Angular starter: https://nativescript.new/angular
- React starter: https://nativescript.new/react
- Solid starter: https://nativescript.new/solid
- Svelte starter: https://nativescript.new/svelte
- Vue starter: https://nativescript.new/vue
- Vue 3 starter: https://nativescript.new/vue3
- [NativeScript on Twitter](http://twitter.com/NativeScript)
- [NativeScript on Discord](https://nativescript.org/discord)
- [NativeScript on Stack Overflow](http://stackoverflow.com/questions/tagged/nativescript)

## Other source projects

Outside the source centralized in this project, NativeScript consists of a few other source projects. Here are the major ones:

- [iOS and visionOS Runtime](https://github.com/NativeScript/ios)
	Empowers JavaScript code to be executed on iOS and visionOS devices written in a mix of C++, Objective-C, and Swift.
- [Android Runtime](https://github.com/NativeScript/android)
	Empowers JavaScript code to be executed on Android devices written in a mix of C++, Java and Kotlin.
- [CLI](https://github.com/NativeScript/nativescript-cli)
	Command-line interface empowering you to create, build, and run apps using NativeScript.
- [Docs](https://github.com/NativeScript/docs)
	Documentation available at <http://docs.nativescript.org/> written in Markdown.
- [Plugins](https://github.com/NativeScript/plugins

*(excerpt; full text in `UPSTREAM_CLONE/`)*

*Quoted from the upstream `README.md` file in `UPSTREAM_CLONE/`.*
Project-specific facts detected in this directory:

- Ecosystem: **Unknown (no standard manifest detected)** (manifests: none detected; scanned in UPSTREAM_CLONE)
- Top-level source layout: `apps/`
- Snapshot size: **547 files**, **48361 lines of code** (measured; see Benchmarks)
- Primary languages: `.ts` (303), `.xml` (116), `.md` (58), `.css` (22), `.json` (13), `(none)` (8)
- Upstream commit pinned for this packaging: `45b3b99afd89f19e799da84203aa19d673f7b20a`

---

## Installation

```bash
    npm install -g nativescript
    ```

2.  **Create a new project:**
    ```bash
    ns create my-app
    ```

3.  **Navigate into your project directory:**
    ```bash
    cd my-app
    ```

4.  **Run your app on an emulator or device:**
    ```bash
    ns run android
    ```
    or
    ```bash
    ns run ios
    ```

*Section quoted from the upstream readme.*
Overlay install (this project):

```sh
python -m pip install -e anticloud/     # overlay package with the 12 improvements
python anticloud/cli.py --help          # 13 subcommands, JSON stdout
```

---

## Usage

[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2FNativeScript%2FNativeScript.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2FNativeScript%2FNativeScript?ref=badge_large)

*Section quoted from the upstream readme.*
Anticloud overlay CLI (available in every project):

```sh
python anticloud/cli.py --help     # 13 subcommands, JSON stdout
python anticloud/cli.py checks     # run the 16-check suite
```

---

## API

[![website](https://img.shields.io/badge/website-nativescript.org-purple.svg)](https://nativescript.org)
  [![https://good-labs.github.io/greater-good-affirmation/assets/images/badge.svg](https://good-labs.github.io/greater-good-affirmation/assets/images/badge.svg)](https://good-labs.github.io/greater-good-affirmation)
  [![support](https://img.shields.io/badge/sponsor-Open%20Collective-blue.svg)](https://opencollective.com/NativeScript)

</p>

[NativeScript](http://www.nativescript.org) empowers you to access native APIs from JavaScript directly. Currently iOS, Android, and visionOS runtimes are provided for rich mobile development across a variety of diverse use cases.

[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2FNativeScript%2FNativeScript.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2FNativeScript%2FNativeScript?ref=badge_large)

*Section quoted from the upstream readme.*
---

## Dependencies

| Metric | Value |
|--------|-------|
| Ecosystem | Unknown (no standard manifest detected) |
| Manifests detected | none |
| Files in snapshot | 547 |
| Lines of code | 48361 |
| Dependency references | 19 |
| Dependencies by ecosystem | npm: 19 |
| Upstream license | MIT |
| Overlay license | Anticommons 0.1.0 |

Top dependency references recorded in the benchmark snapshot:

| Ecosystem | Name | Version | Source file |
|-----------|------|---------|-------------|
| npm | @nativescript/core | file:../../packages/core | apps/toolbox/package.json |
| npm | @nativescript/imagepicker | ^4.1.0 | apps/toolbox/package.json |
| npm | nativescript-theme-core | file:../../node_modules/nativescript-theme-core | apps/toolbox/package.json |
| npm | @valor/nativescript-websockets | file:../../node_modules/@valor/nativescript-websockets | apps/toolbox/package.json |
| npm | @nativescript/android | 9.1.1 | apps/toolbox/package.json |
| npm | @nativescript/ios | 9.1.0-alpha.6 | apps/toolbox/package.json |
| npm | @nativescript/visionos | ~9.0.0 | apps/toolbox/package.json |
| npm | @nativescript/vite | file:../../dist/packages/vite | apps/toolbox/package.json |
| npm | @nativescript/webpack | file:../../dist/packages/webpack5 | apps/toolbox/package.json |
| npm | typescript | ~5.9.3 | apps/toolbox/package.json |
| npm | @nativescript/core | file:../../packages/core | apps/automated/package.json |
| npm | nativescript-theme-core | file:../../node_modules/nativescript-theme-core | apps/automated/package.json |
| npm | @nativescript/android | ~9.1.1 | apps/automated/package.json |
| npm | @nativescript/ios | ~9.0.0 | apps/automated/package.json |
| npm | @nativescript/visionos | ~9.0.0 | apps/automated/package.json |
| ... | (4 more) | | |

Pinned lockfile: `anticloud/requirements.lock` (hash-pinned, PEP 508). SBOM: `sbom.cdx.json` (CycloneDX 1.5, pinned to the upstream SHA).

---

## Configuration

2. source to contribute:

```bash
$ git source https://github.com/NativeScript/NativeScript.git
$ cd NativeScript

*Section quoted from the upstream readme.*
Overlay configuration (Anticloud):

- `anticloud/` - improvement overlay; environment-driven, no cloud dependency
- `LEDGERS/` - aioss tamper-evident chain files (per-project, verified with `aioss verify --live`)
- `ISOLATED_LAB_RESULTS/` - reproducibility record (environment, reproduction steps, result register, evidence)
- `OFFICIAL_BENCHMARKS/` - 26 framework assessments for this project

---

## Contributing

Upstream contributions: fork the `NATIVESCRIPT` project, create a feature branch, and open a pull request against upstream. Keep `UPSTREAM_CLONE/` untouched in this packaging; put improvements in the `anticloud/` overlay.

Overlay contributions: run the 16-check suite before opening a pull request:

```sh
python anticloud/bench/runner.py --cwd anticloud
```

---

## License

**Upstream license: MIT** (evidence: `LICENSE` in the upstream snapshot).

License file excerpt:

```text
Copyright OpenJS Foundation and other contributors, https://openjsf.org

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
```

### Anticommons 0.1.0 overlay

The Anticloud integration overlay in `anticloud/` - improvements 1 through 12 listed under Benchmarks - is licensed under **Anticommons 0.1.0**. Upstream code remains under its original MIT terms. See `ANTICOMMONS_LICENSE.md` in this directory for the overlay terms and contact.

SPDX: `MIT` (upstream) + Anticommons 0.1.0 (overlay, dual).

---

## Upstream

- **Project:** `NATIVESCRIPT` (category: MOBILE)
- **Upstream URL:** https://github.com/NativeScript/NativeScript
- **Pinned commit (SHA):** `45b3b99afd89f19e799da84203aa19d673f7b20a`
- **Branch:** main
- **Pin provenance:** GitHub API commits/main. The parent-project stamp is explicitly rejected for this project.
- **Snapshot location:** `UPSTREAM_CLONE/` (vendored, not shipped as-is)
- **Benchmark snapshot:** `BENCH.json`

---

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`f5968221a5cf92dd172e529749dc44bbd2d54b24ad389d353cd41a6eb2896417`.

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


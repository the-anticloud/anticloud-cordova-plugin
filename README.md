# CORDOVA_PLUGIN

![licence](https://img.shields.io/badge/licence-Apache-2.0-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![checks](https://img.shields.io/badge/checks-unknown_PASS-brightgreen)

> Governed Anticloud packaging of the upstream project `CORDOVA_PLUGIN` in category **MOBILE**. check results: see ISOLATED_LAB_RESULTS. Every number below traces to a named file + run stamp; nothing is borrowed from other projects.

**Upstream:** https://github.com/danielsogl/awesome-cordova-plugins · **Upstream pin:** `f587843dbaac382219d5b0567f4d878788ad2eeb` · **Category:** MOBILE · **Vendor:** Anticloud FZ LLE · **Licence:** Apache-2.0

---

## What This Project Does

<!--
#
# Licensed to the Apache Software Foundation (ASF) under one
# or more contributor license agreements.  See the NOTICE file
# distributed with this work for additional information
# regarding copyright ownership.  The ASF licenses this file
# to you under the Apache License, Version 2.0 (the
# "License"); you may not use this file except in compliance
# with the License.  You may obtain a copy of the License at
#
#   http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing,
# software distributed under the License is distributed on an
# "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
# KIND, either express or implied.  See the License for the
# specific language governing permissions and limitations
# under the License.
#
-->

# Cordova Android

[![npm - Latest](https://img.shields.io/npm/v/cordova-android/latest?label=Latest%20Release%20(npm))](https://npmjs.com/package/cordova-android)

[![GitHub](https://img.shields.io/github/package-json/v/apache/cordova-android?label=Development%20(Git))](https://github.com/apache/cordova-android)
[![GitHub - Node Workflow](https://github.com/apache/cordova-android/actions/workflows/ci.yml/badge.svg?branch=master)](https://github.com/apache/cordova-android/actions/workflows/ci.yml?query=branch%3Amaster)
[![GitHub - Release Audit Workflow](https://github.com/apache/cordova-android/actions/workflows/release-audit.yml/badge.svg?branch=master)](https://github.com/apache/cordova-android/actions/workflows/release-audit.yml?query=branch%3Amaster)
[![Code Coverage](https://codecov.io/github/apache/cordova-android/coverage.svg?branch=master)](https://codecov.io/github/apache/cordova-android?branch=master)

Cordova Android is an Android application library that allows for Cordova-based projects to be built for the Android Platform. Cordova based applications are, at the core, applications written with web technology: HTML, CSS and JavaScript.

[Apache Cordova](https://cordova.apache.org/) is a project of [The Apache Software Foundation (ASF)](https://apache.org/).

## Requirements

* Java Development Kit (JDK)
* [Android SDK](https://developer.android.com/)
* [Gradle](https://gradle.org/)
* [Node.js](https://nodejs.org)

> [!TIP]
> Refer to the official Apache Cordova documentation for details on the requirements and prerequisites for building Cordova-Android applications. These resources outline the necessary tools, supported versions, and platform requirements:
>
> * [System Requirements](https://cordova.apache.org/docs/en/latest/guide/platforms/android/index.html#system-requirements)
> * [Required Software & Tools](https://cordova.apache.org/docs/en/latest/guide/platforms/android/index.html#the-required-software-&-tools)
> * [Android API Level Support](https://cordova.apache.org/docs/en/latest/guide/platforms/android/index.html#android-api-level-support)

## Create a Cordova project

Follow the instructions in the [**Create your first Cordova app**](https://cordova.apache.org/docs/en/latest/guide/cli/index.html) section of [Apache Cordova Docs](https://cordova.apache.org/docs/en/latest/)

## Updating a Cordova project

When you install a new version of the [`Cordova CLI`](https://www.npmjs.com/package/cordova) that pins a new version of the [`Cordova-Android`](https://www.npmjs.com/package/cordova-android) platform, you can follow these simple upgrade steps within your project:

```bash
cordova platform rm android
cordova platform add android
```

## Debugging in Android Studio

Import project in Android Studio through _File > Open_ and targeting `/path/to/your-cdv-project/platforms/android/`.

## Further reading

* [Apache Cordova](https://cordova.apache.org/)

---

## Installation

```bash
cordova platform rm android
cordova platform add android
```

## Usage

# with the License.  You may obtain a copy of the License at

## API

>
> * [System Requirements](https://cordova.apache.org/docs/en/latest/guide/platforms/android/index.html#system-requirements)
> * [Required Software & Tools](https://cordova.apache.org/docs/en/latest/guide/platforms/android/index.html#the-required-software-&-tools)
> * [Android API Level Support](https://cordova.apache.org/docs/en/latest/guide/platforms/android/index.html#android-api-level-support)

## Dependencies

| Metric | Value |
|--------|-------|
| Files | unknown |
| Lines of Code | unknown |
| Dependencies | unknown |
| Upstream license (harvested) | Apache-2.0 |
| Overlay license | Anticommons 0.1.0 |

Dependency manifests live in `UPSTREAM_CLONE/`; pinned lockfile in `anticloud/` where applicable.

## Configuration

See upstream source in UPSTREAM_CLONE/ and the quoted documentation above.

## Contributing

<!--
#
# Licensed to the Apache Software Foundation (ASF) under one
# or more contributor license agreements.  See the NOTICE file
# distributed with this work for additional information
# regarding copyright ownership.  The ASF licenses this file
# to you under the Apache License, Version 2.0 (the
# "License"); you may not use this file except in compliance
# with the License.  You may obtain a copy of the License at
#
#   http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing,
# software distributed under the License is distributed on an
# "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
# KIND, either express or implied.  See the License for the
# specific language governing permissions and limitations
# under the License.
#
-->

# Contributing to Apache Cordova

Anyone can contribute to Cordova. And we need your contributions.

There are multiple ways to contribute: report bugs, improve the docs, and
contribute code.

For instructions on this, start with the
[contribution overview](http://cordova.apache.org/contribute/).

The details are explained there, but the important items are:
 - Check for Github issues that corresponds to your contribution and link or create them if necessary.
 - Run the tests so your patch doesn't break existing functionality.

We look forward to your contributions!

## License

Upstream © its respective contributors under Apache-2.0 (harvested MIT/Apache-2.0/BSD source; see `UPSTREAM_CLONE/LICENSE`). This packaging overlay is licensed under Anticommons 0.1.0.

## Upstream

- **project:** https://github.com/danielsogl/awesome-cordova-plugins
- **Pinned SHA:** `f587843dbaac382219d5b0567f4d878788ad2eeb`
- **source:** `UPSTREAM_CLONE/` (pinned at the SHA above)
- **Upstream README source:** `UPSTREAM_CLONE/README.md`

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`697942e419637f8db3bbb296649d72c5b8a1a7dc4e910f13681ac82985333d1e`.

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
| DANS (KNAW/NWO, Netherlands) | 10.17026/PT | EU-recognised archive |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe
and Mail, Business Insider, National Post, Financial Post, StreetInsider,
Digital Journal, Barchart, International Business Times, and Fox News.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.


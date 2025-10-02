<!-- Allow this file to not have a first line heading -->
<!-- markdownlint-disable-file MD041 no-emphasis-as-heading -->

<!-- inline html -->
<!-- markdownlint-disable-file MD033 -->

<div align="center">

# `🌎 COLLAB DIGITAL TWINS`


**Democratizing Digital Twin Technologies**

<!-- CHANGE TO CDT -->
[![Embark](https://img.shields.io/badge/embark-open%20source-blueviolet.svg)](https://embark.dev)
[![Embark](https://img.shields.io/badge/discord-ark-%237289da.svg?logo=discord)](https://discord.gg/dAuKfZS)
[![Crates.io](https://img.shields.io/crates/v/rust-gpu.svg)](https://crates.io/crates/rust-gpu)
[![Docs](https://docs.rs/rust-gpu/badge.svg)](https://docs.rs/rust-gpu)
[![Git Docs](https://img.shields.io/badge/git%20main%20docs-published-blue)](https://embarkstudios.github.io/presser/presser/index.html)
[![dependency status](https://deps.rs/repo/github/EmbarkStudios/rust-gpu/status.svg)](https://deps.rs/repo/github/EmbarkStudios/rust-gpu)
[![Build status](https://github.com/EmbarkStudios/physx-rs/workflows/CI/badge.svg)](https://github.com/EmbarkStudios/physx-rs/actions)
</div>

## TEMPLATE INSTRUCTIONS

1. Create a new repository under EmbarkStudios using this template.
1. **Title:** Change the first line of this README to the name of your project, and replace the sunflower with an emoji that represents your project. 🚨 Your emoji selection is critical.
1. **Badges:** In the badges section above, change the repo name in each URL. If you are creating something other than a Rust crate, remove the crates.io and docs badges (and feel free to add more appropriate ones for your language).
1. **CI:** In `./github/workflows/` rename `rust-ci.yml` (or the appropriate config for your language) to `ci.yml`. And go over it and adapt it to work for your project
    - If you aren't using or customized the CI workflow, also see the TODO in `.mergify.yml`
    - If you want to use the automatic rustdoc publishing to github pages for git main, see `rustdoc-pages.yml`
1. **Issue & PR Templates**: Review the files in `.github/ISSUE_TEMPLATE` and `.github/pull_request_template`. Adapt them
to suit your needs, removing or re-wording any sections that don't make sense for your use case.
1. **CHANGELOG.md:** Change the `$REPO_NAME` in the links at the bottom to the name of the repository, and replace the example template lines with the actual notes for the repository/crate.
1. **release.toml:** in `./release.toml` change the `$REPO_NAME` to the name of the repository
1. **Cleanup:** Remove this section of the README and any unused files (such as configs for other languages) from the repo.


## ♊ What is CDT?

CDT is a web-based, non-proprietary platform designed for the visualization and interaction of multi-scale geospatial information systems (GIS), open data, open building information modelling (BIM), and a wide range of other digital media, including text, images, animated and static 3D models, IFCs, and point clouds.

The platform is built with full-stack web development frameworks, using React.js for the user interface, state management, and memory optimization, and Next.js for file organization, routing, and server-side rendering (SSR). It integrates multiple open-source packages to support maps and 3D models: Maplibre as the web map renderer and Martin as the PostGIS vector tile server for GIS data, Three.js for 3D graphics, and Web-IFC from That Open Company for native browser-based IFC parsing, with IDS and BCF integration. Point cloud streaming and visualization are supported through Cloud Optimized Point Clouds (COPC), handled by the Potree and Giro3D libraries.

The backend is powered by PostgreSQL, with MinIO providing object storage for binary files such as IFC models and point clouds. All services are hosted on Canadian-based Fullhost infrastructure to ensure data sovereignty.

CDT efficiently incorporates multi-scale open data (federal, provincial, municipal), which is fetched directly from organizational APIs without requiring local data storage. Rather than functioning as a system of record, it serves as a framework and infrastructure for referencing and linking distributed data sources.

Finally, CDT includes a robust authentication system that allows users to form groups, assume different roles and credentials for controlled data and feature access, collaborate effectively, and contribute diverse types of digital media, both publicly and privately.

## 🧭 Mission

This platform bridges BIM and GIS using open standards and free and open-source technologies, enabling stakeholders to visualize and analyze data directly in the browser, thereby eliminating proprietary barriers.
The platform is being stewarded by a not-for-profit, <a href="www.collabdt.org">Collab Digital Twins</a>, established to promote openness, innovation, and long-term public benefit. Our mission is to democratize digital twin technologies. 

## Contributing

[![Contributor Covenant](https://img.shields.io/badge/contributor%20covenant-v1.4-ff69b4.svg)](CODE_OF_CONDUCT.md)

We welcome community contributions to this project.

Please read our [Contributor Guide](CONTRIBUTING.md) for more information on how to get started.
Please also read our [Contributor Terms](CONTRIBUTING.md#contributor-terms) before you make any contributions.

Any contribution intentionally submitted for inclusion in an Embark Studios project shall comply with the Rust standard licensing model (MIT OR Apache 2.0) and therefore be dual licensed as described below, without any additional terms or conditions:

### License

This contribution is dual licensed under EITHER OF

- Apache License, Version 2.0, ([LICENSE-APACHE](LICENSE-APACHE) or <http://www.apache.org/licenses/LICENSE-2.0>)

## 🚀 Beta access

To participate in the beta, please complete this short <a href="https://docs.google.com/forms/d/e/1FAIpQLScB12Qc7khiOk4a_E753jDccx6026AjO-_FINBKoZZZtkmqnA/viewform" target="_blank" rel="noopener">beta access form</a>. We will review submissions and contact you with onboarding details.



# Simon van Lierde

PhD researcher and research software engineer at the Institute of Environmental Sciences (CML), Leiden University. I build open, reproducible research infrastructure for industrial ecology and the circular economy. Most of my work turns messy product-level data into FAIR datasets and tools researchers can use directly.

Focus areas: industrial ecology, circular economy, and life-cycle assessment.
Main stack: Python, FastAPI, TypeScript/React, PostgreSQL, and Docker.

---

## Featured project

### [Reverse Engineering Lab (RELab)](https://github.com/CMLPlatform/relab)

RELab collects disassembly data on durable goods to close a long-standing product-data gap in industrial ecology. I designed and built the platform end to end: a FastAPI backend, a PostgreSQL data model built for LCA, and an Expo/React Native frontend. In active use as lab infrastructure at CML: 50+ products disassembled, 1,250+ components and 3,000+ photos catalogued, with Repair Café pilots planned.

- 🌐 Live platform: [app.cml-relab.org](https://app.cml-relab.org)
- 📖 Documentation: [docs.cml-relab.org](https://docs.cml-relab.org)
- 🧩 RPI camera plugin: [relab-rpi-cam-plugin](https://github.com/CMLPlatform/relab-rpi-cam-plugin), a FastAPI service for remote image capture during disassembly

---

## Selected work

**[credit-heatmap](https://github.com/simonvanlierde/credit-heatmap)** is a full-stack web tool for building CRediT author-contribution statements, with an interactive role matrix and JATS4R XML / JSON export for journal submission. Built on Next.js 15 with a framework-agnostic TypeScript core that runs the domain logic in the browser, deployable both as a Docker container and on Cloudflare Workers (OpenNext).
Live demo at [credit.duinlab.nl](https://credit.duinlab.nl)

**[msc-thesis-ie](https://github.com/simonvanlierde/msc-thesis-ie)** is my MSc Industrial Ecology thesis (Leiden / TU Delft): a bottom-up model of building cooling demand in The Hague and its life-cycle environmental impacts, built from BAG geospatial data, an hourly heat-balance model, and an LCA layer. It is published in the TU Delft repository, with the dataset archived on Zenodo.

**[monitoring](https://github.com/CMLPlatform/monitoring)** is the observability stack for CML's research platforms: an OpenTelemetry pipeline (Grafana, Loki, Tempo, Prometheus) collecting logs, traces, and metrics from RELab and other services, with CI-validated configs and a one-command demo.

---

## Open-source contributions

I maintain reusable tooling I need in my own work, like [check-json5](https://github.com/simonvanlierde/check-json5), a pre-commit hook whose fast-path parser makes it roughly 500× faster on large JSON files, and I send small fixes upstream to tools I use, mostly in the FastAPI and open-LCA ecosystems, such as [fastapi-mail](https://github.com/sabuhish/fastapi-mail/pull/283) and [sentier_data_tools](https://github.com/sentier-dev/sentier_data_tools/pull/2).

Outside work I build small web apps I keep tinkering with:

- [6-second-scribbles](https://6ss.duinlab.nl), a fast drawing game
- [scattergories](https://github.com/simonvanlierde/scattergories), a browser word game
- [tide](https://tide.duinlab.nl), a period tracker
- [bikespot](https://bikespot.duinlab.nl), a bike-parking tracker

---

## Elsewhere

- 🌐 Website: [simonvanlierde.github.io](https://simonvanlierde.github.io)
- 🆔 ORCID: [0009-0006-6953-909X](https://orcid.org/0009-0006-6953-909X)
- 💼 LinkedIn: [in/simon-van-lierde](https://www.linkedin.com/in/simon-van-lierde/)
- 🎓 Leiden profile: [universiteitleiden.nl](https://www.universiteitleiden.nl/en/staffmembers/simon-van-lierde)

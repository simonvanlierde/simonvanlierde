# Simon van Lierde

PhD researcher and research software engineer at the Institute of Environmental Sciences (CML), Leiden University. I build open, reproducible research infrastructure for industrial ecology and the circular economy. Most of my work turns messy product-level data into FAIR datasets and tools researchers can use directly.

Focus areas: industrial ecology, circular economy, and life-cycle assessment.
Main stack: Python, FastAPI, TypeScript/React, PostgreSQL, and Docker.

---

## Featured project

### [Reverse Engineering Lab (RELab)](https://github.com/CMLPlatform/relab)

RELab collects disassembly data on durable goods to close a long-standing product-data gap in industrial ecology. I designed and built the platform end to end: a FastAPI backend, a PostgreSQL data model built for LCA, and an Expo/React Native frontend. In active use as lab infrastructure at CML: 78 products disassembled, 1,331 components and 3,610 photos catalogued, across a lab deployment and two teardown workshops with 135 participants.

- 🌐 Live platform: [app.cml-relab.org](https://app.cml-relab.org)
- 📖 Documentation: [docs.cml-relab.org](https://docs.cml-relab.org)
- 🧩 RPI camera plugin: [relab-rpi-cam-plugin](https://github.com/CMLPlatform/relab-rpi-cam-plugin), a FastAPI service for remote image capture during disassembly

---

## Selected work

**[monitoring](https://github.com/CMLPlatform/monitoring)** is the observability stack for CML's research platforms: an OpenTelemetry pipeline (Grafana, Loki, Tempo, Prometheus) collecting logs, traces, and metrics from RELab and other services, with CI-validated configs and a one-command demo.

**[msc-thesis-ie](https://github.com/simonvanlierde/msc-thesis-ie)** is my MSc Industrial Ecology thesis (Leiden / TU Delft): a bottom-up model of building cooling demand in The Hague and its life-cycle environmental impacts, built from BAG geospatial data, an hourly heat-balance model, and an LCA layer. It is published in the TU Delft repository, with the dataset archived on Zenodo. Interactive results dashboard at [simonvanlierde.github.io/msc-thesis-ie](https://simonvanlierde.github.io/msc-thesis-ie)

**[cv-ie-taxonomy](https://github.com/simonvanlierde/cv-ie-taxonomy)** is an interactive exploded-teardown map of a computer-vision taxonomy for industrial ecology, built as a companion visual for an upcoming publication: a custom React/SVG scene with scroll-driven exploration. Live at [simonvanlierde.github.io/cv-ie-taxonomy](https://simonvanlierde.github.io/cv-ie-taxonomy/)

**[credit-matrix](https://github.com/simonvanlierde/credit-matrix)** helps co-authors draft CRediT contribution statements together, then exports the grid as a contribution heatmap plus JATS4R XML, CSV, JSON or Markdown. It runs fully in the browser, works offline and comes in nine languages. Built with Next.js 16 and TypeScript, archived on [Zenodo](https://doi.org/10.5281/zenodo.21213659). Live at [credit.duinlab.nl](https://credit.duinlab.nl)

In progress: an [AI4IE resource hub](https://github.com/simonvanlierde/ai4ie-demo) and a [project gallery](https://github.com/CMLPlatform/cml-gallery) for CML, both early prototypes.

---

## Open-source contributions

I maintain reusable tooling I need in my own work, like [check-json5](https://github.com/simonvanlierde/check-json5), a pre-commit hook whose fast-path parser makes it roughly 500× faster on large JSON files, and [project-templates](https://github.com/simonvanlierde/project-templates), Copier templates that start a Python, TypeScript, Rust or Go project with linting, tests and CI already set up. I also send small fixes upstream to tools I use, mostly in the FastAPI and open-LCA ecosystems, such as [fastapi-mail](https://github.com/sabuhish/fastapi-mail/pull/283) and [sentier_data_tools](https://github.com/sentier-dev/sentier_data_tools/pull/2).

Outside work I build small web apps I keep tinkering with:

- [6-second-scribbles](https://github.com/simonvanlierde/6-second-scribbles), a fast drawing game ([live](https://6ss.duinlab.nl))
- [scattergories](https://github.com/simonvanlierde/scattergories), a browser word game ([live](https://scattergories.duinlab.nl))
- [tide](https://github.com/simonvanlierde/tide), a period tracker ([live](https://tide.duinlab.nl))
- [bikespot](https://github.com/simonvanlierde/bikespot), a bike-parking tracker ([live](https://bikespot.duinlab.nl))

---

## Elsewhere

- 🌐 Website: [simonvanlierde.github.io](https://simonvanlierde.github.io)
- 🆔 ORCID: [0009-0006-6953-909X](https://orcid.org/0009-0006-6953-909X)
- 💼 LinkedIn: [in/simon-van-lierde](https://www.linkedin.com/in/simon-van-lierde/)
- 🎓 Leiden profile: [universiteitleiden.nl](https://www.universiteitleiden.nl/en/staffmembers/simon-van-lierde)

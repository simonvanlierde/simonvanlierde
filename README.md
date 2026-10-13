# Simon van Lierde

PhD researcher and research software engineer at the Institute of Environmental Sciences (CML), Leiden University. I build open, reproducible research infrastructure for industrial ecology and the circular economy. Most of my work takes messy data about products and turns it into FAIR datasets (findable, accessible, interoperable, reusable) and tools that researchers can use directly.

Focus areas: industrial ecology, circular economy, and life-cycle assessment.
Main stack: Python, FastAPI, TypeScript/React, PostgreSQL, and Docker.

---

## Featured project

### [Reverse Engineering Lab (ReLab)](https://github.com/CMLPlatform/relab)

Industrial ecology has long been short of data on what products are made of. ReLab helps close that gap by recording how durable goods come apart. I designed and built the platform end to end: a FastAPI backend, a PostgreSQL data model built for life-cycle assessment (LCA), and an Expo/React Native frontend.

CML uses it as lab infrastructure. By 12 October 2026 we had taken apart 94 products and catalogued 1,779 components and 4,455 photos, in the lab and at two teardown workshops with 135 participants.

- 🌐 Live platform: [app.cml-relab.org](https://app.cml-relab.org)
- 📖 Documentation: [docs.cml-relab.org](https://docs.cml-relab.org)
- 🧩 RPI camera plugin: [relab-rpi-cam-plugin](https://github.com/CMLPlatform/relab-rpi-cam-plugin), a FastAPI service that takes photos remotely while a product is taken apart

---

## Selected work

**[monitoring](https://github.com/CMLPlatform/monitoring)** collects logs, traces, and metrics from ReLab and CML's other research platforms in one place. It's an OpenTelemetry pipeline (Grafana, Loki, Tempo, Prometheus). CI validates the configs, and one command starts a demo.

**[msc-thesis-ie](https://github.com/simonvanlierde/msc-thesis-ie)** is my MSc Industrial Ecology thesis (Leiden / TU Delft). It models, from the bottom up, how much cooling the buildings in The Hague need and what that cooling does to the environment over its life cycle. It combines BAG geospatial data (the Dutch building register), an hourly heat-balance model, and an LCA layer. The thesis is in the TU Delft repository and the dataset is on Zenodo. You can explore the results in a dashboard at [simonvanlierde.github.io/msc-thesis-ie](https://simonvanlierde.github.io/msc-thesis-ie)

**[cv-ie-taxonomy](https://github.com/simonvanlierde/cv-ie-taxonomy)** is a visual to go with an upcoming paper. It shows a computer-vision taxonomy for industrial ecology as an exploded teardown that you explore by scrolling, drawn in React and SVG. Live at [simonvanlierde.github.io/cv-ie-taxonomy](https://simonvanlierde.github.io/cv-ie-taxonomy/)

**[credit-matrix](https://github.com/simonvanlierde/credit-matrix)** helps co-authors write a CRediT contribution statement (who did what on a paper) together. It exports the grid as a contribution heatmap, plus JATS4R XML, CSV, JSON or Markdown. It runs fully in the browser, works offline and comes in nine languages. Built with Next.js 16 and TypeScript, and archived on [Zenodo](https://doi.org/10.5281/zenodo.21213659). Live at [credit.duinlab.nl](https://credit.duinlab.nl)

In progress: an [AI4IE resource hub](https://github.com/simonvanlierde/ai4ie-demo) and a [project gallery](https://github.com/CMLPlatform/cml-gallery) for CML, both early prototypes.

---

## Open-source contributions

I maintain small tools I need in my own work. [check-json5](https://github.com/simonvanlierde/check-json5) is a pre-commit hook with a fast path in its parser that makes it about 660 to 750 times faster on JSON files from 47 KB to 2 MB. [project-templates](https://github.com/simonvanlierde/project-templates) holds Copier templates that start a Python, TypeScript, Rust or Go project, optionally with Docker, with linting, tests and CI already set up. I also send small fixes back to tools I use, mostly projects around FastAPI and open LCA, such as [fastapi-mail](https://github.com/sabuhish/fastapi-mail/pull/283) and [sentier_data_tools](https://github.com/sentier-dev/sentier_data_tools/pull/2).

Outside work I build small web apps and keep tinkering with them:

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

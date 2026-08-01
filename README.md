<p align="center">
  <img src="assets/profile-header.svg?v=20260802b" alt="Victor Aubry — Software Engineer and AI Infrastructure" width="100%" />
</p>

<h1 align="center">Software Engineer | AI Infrastructure</h1>

<p align="center">
  APIs, AI runtimes, Linux servers, and data pipelines.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-0B111C?style=flat-square&logo=python&logoColor=8FB0FF" alt="Python" />
  <img src="https://img.shields.io/badge/TypeScript-0B111C?style=flat-square&logo=typescript&logoColor=8FB0FF" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Rust-0B111C?style=flat-square&logo=rust&logoColor=8FB0FF" alt="Rust" />
  <img src="https://img.shields.io/badge/Linux-0B111C?style=flat-square&logo=linux&logoColor=8FB0FF" alt="Linux" />
  <img src="https://img.shields.io/badge/Docker-0B111C?style=flat-square&logo=docker&logoColor=8FB0FF" alt="Docker" />
  <img src="https://img.shields.io/badge/AWS-0B111C?style=flat-square&logo=amazonwebservices&logoColor=8FB0FF" alt="AWS" />
  <img src="https://img.shields.io/badge/OVHcloud-0B111C?style=flat-square&logo=ovh&logoColor=8FB0FF" alt="OVHcloud" />
  <img src="https://img.shields.io/badge/Hetzner-0B111C?style=flat-square&logo=hetzner&logoColor=8FB0FF" alt="Hetzner" />
</p>

<p align="center">
  <a href="#02--reference-architecture">Architecture</a> ·
  <a href="#03--selected-work">Projects</a> ·
  <a href="#04--stack">Stack</a> ·
  <a href="#05--activity">Activity</a> ·
  <a href="https://www.linkedin.com/in/victor-aubry-558491325/">LinkedIn</a>
</p>

---

## 01 — Profile

I write Python, TypeScript, Rust, and C#. My work includes APIs, background workers, Linux services, native desktop runtimes, live data paths, and operational tooling.

I started in data science and moved toward backend and platform work. I still use that background for model evaluation, data quality, and reproducible pipelines.

I spend most of my time on service boundaries, VPS and dedicated servers, event delivery, model serving, health checks, and recovery.

## 02 — Reference architecture

The core runs on a VPS or dedicated host. It serves snapshots and ordered events from the same runtime; state and lifecycle controls stay outside the delivery path.

<p align="center">
  <picture>
    <source media="(max-width: 640px)" srcset="assets/reference-architecture-compact.svg?v=20260802a" />
    <img src="assets/reference-architecture.svg?v=20260802a" alt="Horizontal system architecture: sources pass through adapter and policy gates into a supervised runtime on a VPS or dedicated host; ordered events and snapshots move through bounded state to typed APIs, live streams, and desktop or web clients." width="100%" />
  </picture>
</p>

<details>
<summary><strong>Design notes</strong></summary>

- Ordered events carry live changes. Snapshots handle startup, recovery, and degraded operation.
- External adapters normalize source-specific payloads before domain code sees them.
- Every queue, cache, history, worker pool, and retention window has a fixed limit.
- Health, maintenance, read-only mode, and shutdown stay available when live workers are paused.
- Live and test runtimes keep separate state, caches, and secret namespaces.
- New artifacts are verified before they replace the active version.

</details>

## 03 — Selected work

| Project | System |
| --- | --- |
| [NLP Sentinel](https://github.com/VicoD3X/nlp-sentinel) | FastAPI inference API: typed schemas, cached model loading, file-based or Azure telemetry, and a feedback endpoint. |
| [Spark Vision](https://github.com/VicoD3X/spark-vision) | PySpark image-feature pipeline using pandas UDFs and MobileNetV2, with Parquet output on EMR/S3. |
| [Reco Engine](https://github.com/VicoD3X/reco-engine) | Azure Functions recommendation API with Blob-backed artifacts, an in-process cache, and a cold-start fallback. |
| [Urban Segmenter](https://github.com/VicoD3X/urban-segmenter) | Keras segmentation pipeline served by FastAPI, with a Streamlit client that runs in-process or against the API. |

<details>
<summary><strong>More engineering work</strong></summary>

- [Auto-CV](https://github.com/VicoD3X/auto-cv) — Python desktop application built around SQLite repositories, deterministic document generation, and a managed `llama.cpp` process.
- [Neural Exchange](https://github.com/VicoD3X/neural-exchange) — PyTorch time-series experiment with causal baselines, saved model artifacts, generated reports, and offline tests.
- [Freight Network](https://github.com/VicoD3X/freight-network) — Python graph-analysis package using deterministic synthetic data, NetworkX metrics, generated reports, tests, and CI.

</details>

## 04 — Stack

| Layer | Stack |
| --- | --- |
| Languages | Python · TypeScript · Rust · C# · SQL · JavaScript · PowerShell |
| Backend and APIs | FastAPI · Uvicorn · Fastify · Express · Pydantic · REST · SSE · typed IPC |
| Systems and desktop | Cargo workspaces · Tauri 2 · .NET / WinForms · Node.js · native launchers · process lifecycle |
| AI and data | PyTorch · TensorFlow · scikit-learn · `llama.cpp` · pandas · PySpark · Parquet · NetworkX |
| Web and rendering | React 19 · Svelte 5 · Vite · PixiJS · MapLibre GL · Canvas · Streamlit |
| Storage and integrity | SQLite · rusqlite · Serde · JSON · SHA-2 · filesystem adapters |
| Infrastructure | Linux · Docker · VPS · dedicated servers · OVHcloud · Hetzner · AWS EMR/S3 · Azure Functions/Application Insights |
| Quality and delivery | pytest · Ruff · Cargo test · Clippy · Vitest · Playwright · ESLint · GitHub Actions |

## 05 — Activity

<p align="center">
  <img src="https://github-stats-extended.vercel.app/api?username=VicoD3X&amp;show_icons=true&amp;include_all_commits=true&amp;hide_title=true&amp;hide_border=false&amp;bg_color=0D1117&amp;title_color=91A9DF&amp;text_color=C6D2EC&amp;icon_color=7F9CE0&amp;border_color=283A63" alt="Victor Aubry GitHub statistics" width="54%" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=VicoD3X&amp;bg_color=0D1117&amp;color=91A9DF&amp;line=6F8EDC&amp;point=DCE6FF&amp;area=true&amp;area_color=243A66&amp;hide_border=false&amp;border_color=283A63&amp;radius=12&amp;days=31&amp;custom_title=Engineering%20Activity" alt="Victor Aubry engineering activity graph" width="100%" />
</p>

## 06 — Contact

[LinkedIn](https://www.linkedin.com/in/victor-aubry-558491325/) is the best way to reach me.

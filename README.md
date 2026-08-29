# Hi, I'm Joseph 🧪

Software developer with **15 years of industry experience**, currently back in school full-time for a second bachelor's/associate's in Chemistry — building toward a career in **cheminformatics and computational drug discovery**.

---

## 🔍 Open to part-time work in

- **DevOps for cloud-native, Go-based systems** — Prometheus, Terraform, and similar infrastructure/observability tooling
- **Backend development in memory-optimized open-source languages** — Go and Node.js (vanilla JS, no TypeScript)
- **ML pipeline engineering for drug discovery** — building on the work in [`reinvent4-mol2mol`](https://github.com/nidhhoggr/reinvent4-mol2mol) and [`diffsbdd-docker`](https://github.com/nidhhoggr/diffsbdd-docker)

Reach out if any of the above fits what you're hiring for.

---

## 🎓 Back in school for Chemistry

Post-baccalaureate student at North Idaho College, pursuing an Associate of Science in Chemistry as a stepping stone toward a Chemistry/bioinformatics degree (WSU or University of Idaho) and a career in computational drug discovery.

**This semester:**
- Organic Chemistry 1 (with lab)
- Biology — Intro to Cells (majors)
- Linear Algebra

---

## 🧬 Computational Drug Discovery Pipeline

A high-throughput virtual screening pipeline built around the **7KEW** binding pocket, developed through a University of Idaho INBRE internship and screening 77,500+ compounds for high-affinity antiviral candidates — written up as a full scientific paper.

| Repo | What it does |
|---|---|
| [`reinvent4-mol2mol`](https://github.com/nidhhoggr/reinvent4-mol2mol) | Transfer learning & reinforcement learning campaigns on REINVENT4 (mol2mol, LibInvent) |
| [`diffsbdd-docker`](https://github.com/nidhhoggr/diffsbdd-docker) | Dockerized DiffSBDD — pocket-conditioned diffusion/inpainting for structure-based design |
| [`compound-pool-analysis`](https://github.com/nidhhoggr/compound-pool-analysis) | RDKit-based descriptors, Murcko scaffolds, Butina clustering, and scaffold-diversity diagnostics |
| [`protein-sequence-analysis`](https://github.com/nidhhoggr/protein-sequence-analysis) | Sequence alignment analysis for target proteins |

Supporting infrastructure includes AutoDock Vina redocking QC, Apptainer/Singularity conversion for HPC deployment, and GPU-passthrough Docker setups.

---

## 💻 Repositories & Languages

109 public repos spanning a 15-year career — from full-stack PHP/JS agency work early on to Go systems tooling and Python scientific computing now.

| Language | Original repos | Focus |
|---|---|---|
| **Go** | ~11 | IPC libraries (`gipc`, `xipc`, `shmemipc`), process management (`pmon3`), Consul/HA tooling (`happac`, `cheek-turner`) |
| **Python** | ~7 | Drug discovery pipeline, bioinformatics scripting |
| **JavaScript (Node.js)** | ~20 | APIs, automation scripts, Loopback ecosystem work |
| **PHP** | ~19 | Legacy full-stack/agency projects (Symfony, WordPress, Loopback SDK) |
| Shell, Java, C/C++, Solidity, Rust | ~15 combined | Infra scripting, Android, game dev, and Solidity/web3 experiments |

**Open-source contributions:**
- [`go-gorm/gorm`](https://github.com/go-gorm/gorm) — contributed a feature allowing foreign keys to be saved without saving the associated record when explicitly specified ([commit](https://github.com/go-gorm/gorm/commit/9235b47ea28d816ef25d6bf4e037ccb5c7c7096b))
- [`sqlite`](https://github.com/nidhhoggr/sqlite) — a GORM SQLite driver built on `modernc.org/sqlite`
- [`DiffSBDD`](https://github.com/nidhhoggr/DiffSBDD) — the structure-based drug design diffusion model underpinning the pipeline above
- [`bull`](https://github.com/nidhhoggr/bull) — the Node.js premium queue library
- Loopback framework ecosystem: `loopback-datasource-juggler`, plus several Loopback mixins/connectors
- Solidity/web3 tooling: `closedsea`, `ERC721Psi`, `operator-filter-registry`

**Highlights:**
- 🌟 [`pmon3`](https://github.com/nidhhoggr/pmon3) — a Golang production process manager
- 🌟 [`ipset-blacklist-firewalld`](https://github.com/nidhhoggr/ipset-blacklist-firewalld) — zero-downtime atomic IP blocking with ipsets and firewalld

---

## 🎵 folktabs.com

[FolkTabs.com](https://www.folktabs.com/) is a free, browser-based ABC-notation player for traditional folk instruments — no install, mobile-optimized. It's built around [`sackpipa-player`](https://github.com/nidhhoggr/sackpipa-player) (with a companion [`tagelharpa-player`](https://github.com/nidhhoggr/tagelharpa-player)), which loads ABC files and plays them back alongside music notation and Säckpipa (Swedish bagpipe) chanter fingering diagrams. It runs on a custom fork of ABCJS with a Webpack 4/Babel 7 build.

A companion project, [`sackpipa-playability`](https://github.com/nidhhoggr/sackpipa-playability), crunches the entire FolkWiki.se tune archive to programmatically determine which songs are actually playable within the Säckpipa's limited chanter range — something that would be impractical to check by hand — and surfaces the results as charts and data visualizations at [compatibility.folktabs.com](https://compatibility.folktabs.com/).

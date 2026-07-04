<div align="center">

<img src="pics/tesbocfd.svg" alt="TesboCFD Logo" width="480"/>

# TesboCFD

### Built for speed. Powered by GPU.

**GPU-native computational fluid dynamics — making high-fidelity simulation go from days to minutes.**

[![Website](https://img.shields.io/badge/Website-tesbocfd.com-c05c84?logo=google-chrome&logoColor=white)](https://www.tesbocfd.com/)
[![GitHub](https://img.shields.io/badge/GitHub-Tes--bo-d648ff?logo=github)](https://github.com/Tes-bo)
[![Email](https://img.shields.io/badge/Email-cotsqa%40qq.com-fccf9a?logo=gmail)](mailto:cotsqa@qq.com)
[![CUDA](https://img.shields.io/badge/CUDA-Powered-76b900?logo=nvidia&logoColor=white)](https://developer.nvidia.com/cuda-toolkit)

</div>

---

## Who we are

**TesboCFD** is a team focused on **GPU-native computational fluid dynamics (CFD)**.
We build modern simulation software that runs the entire pipeline on the GPU —
delivering large speedups over traditional CPU clusters, so engineers spend less
time waiting and more time designing.

> **Star this repo and follow [TesboCFD on GitHub](https://github.com/Tes-bo)** to track our progress.
>
> **Open to collaboration and investment** — technical partnerships, business partnerships, and investment conversations are all welcome.

---

## Products

| Product | What it is | Status |
|---|---|---|
| **TesboFlow** | Fully GPU-native general-purpose CFD solver | Available, actively developed |
| **TesboLBM** | In-house casting-simulation solver (mold filling + solidification) | Available |
| **TesboAI** | AI + CFD product line (ML surrogates, differentiable physics, agentic CFD) | Prototypes ready, productizing |

<br/>

<div align="center">
<img src="pics/tesboflow.svg" alt="TesboFlow Logo" width="360"/>
</div>

### TesboFlow — GPU-native CFD solver

Our flagship: a fully GPU-native CFD solver for general-purpose fluid simulation.
The whole pipeline — mesh, discretization, linear algebra, post-processing — runs
on the GPU, with no CPU bottleneck.

- **Available today**: incompressible flow (steady & transient), RANS turbulence,
  moving/deforming meshes, overset (chimera) grids, and import/conversion of
  external mesh formats.
- **In active development**: multi-GPU execution.
- **On the roadmap**: multi-node (cluster) execution, broader platforms (e.g.
  arm64), compressible flow, heat transfer, multi-phase flow, and advanced
  turbulence models.

> **Performance**: TesboFlow targets **100–1000×** speedups over CPU clusters on
> typical workloads. Actual gains depend on case size and hardware, and are not a
> guarantee — we're happy to run a benchmark on your own case.

### TesboLBM — Casting simulation

An in-house casting-simulation suite for industrial casting processes and
process-defect analysis: mold filling via the Lattice Boltzmann Method (LBM,
D3Q19 + free-surface tracking) and heat transfer / solidification via the Finite
Volume Method (FVM, with adaptive mesh refinement), with the two stages coupled.
Ships with a command-line mesh generator, runs on both CPU and CUDA GPU backends,
and is proven end-to-end on real parts.

### TesboAI — AI + CFD

TesboCFD's AI + CFD product line, deeply integrated with TesboFlow. One goal above
all: **AI-assisted CFD design** — greatly accelerating design iteration toward
near-real-time, interactive exploration.

- **Machine learning / deep learning surrogates**: neural operators (FNO-type),
  reduced-order models, implicit neural representations, and data-driven
  turbulence modeling.
- **Physics-informed / differentiable physics**: physics-constrained learning and
  end-to-end differentiable CFD.
- **Agentic CFD** (early development): LLM/agent-driven natural-language CFD
  workflows.

> Several working prototypes and baselines exist today; productization is in
> progress.

---

## Why GPU-native

- **Built for the GPU from the ground up** — not a port of CPU code, so the
  architecture is cleaner and the performance ceiling is higher.
- **Whole pipeline on-device** — no CPU↔GPU data-shuffling overhead.
- **Self-developed full stack** — solver + casting + AI, deeply integrated.
- **Scalable** — from a desktop GPU workstation toward multi-GPU HPC.

---

## What we do

- **CFD software development** — advanced GPU-native solvers and high-performance
  simulation tools.
- **Engineering simulation** — simulation analysis and optimization for complex
  fluid engineering problems.
- **Technical consulting** — numerical modeling and advanced simulation support.
- **Training** — CFD theory, numerical methods, GPU/CUDA, and modern simulation
  courses. See [tesbocfd.com](https://www.tesbocfd.com/).

---

## Development highlights

- **2025** — Fully GPU-native incompressible flow solver.
- **January 2026** — Dynamic (moving/deforming) mesh on GPU.
- **March 2026** — Overset (chimera) mesh on GPU.
- **In progress** — Multi-GPU execution.
- **Next** — Multi-node parallelism, compressible flow, heat transfer, multi-phase
  flow, and advanced turbulence models.

> TesboFlow is currently under **closed-source development**.

---

## Research collaboration

We collaborate with research institutions on advanced simulation and solver
validation, including Tsinghua University, the Institute of Mechanics (CAS), and
the University of Shanghai for Science and Technology.

---

## Get in touch

- **Evaluate on your own case** — we run a collaborative pilot: you provide a
  representative case, we run it and compare against your existing results.
- **Collaboration & investment** — we welcome technical/business partnerships and
  investment conversations.
- **Contact** — cotsqa@qq.com · https://www.tesbocfd.com/ · https://github.com/Tes-bo

---

<div align="center">

**Developed and maintained by the TesboCFD Team**

**Built for speed. Powered by GPU.**

</div>

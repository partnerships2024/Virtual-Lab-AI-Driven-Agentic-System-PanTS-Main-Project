<p align="center">
  <img
    src="./Logo/VL_Agentic_System_PanTS.png"
    alt="Virtual Lab: AI-Driven Agentic System for Pancreatic Tumour Segmentation"
    width="700"
  />
</p>

<h1 align="center">Virtual Lab: An AI-Driven Agentic System for Pancreatic Tumour Segmentation Using 3D Medical Images</h1>

<p align="center">
  <strong>Agentic AI · Medical Image Analysis · Pancreatic Cancer · 3D Segmentation · Virtual Research Lab</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Research-AI%20in%20Healthcare-6C5CE7?style=for-the-badge" alt="Research">
  <img src="https://img.shields.io/badge/Domain-Pancreatic%20Cancer-FF7675?style=for-the-badge" alt="Pancreatic Cancer">
  <img src="https://img.shields.io/badge/Imaging-3D%20Medical%20Images-00B894?style=for-the-badge" alt="3D Medical Images">
  <img src="https://img.shields.io/badge/Approach-Agentic%20AI-0984E3?style=for-the-badge" alt="Agentic AI">
</p>

---

## Project Overview

This research project investigates a **Virtual Lab of AI-driven agents** for automated **pancreatic tumor segmentation from 3D medical images**.

The proposed system is designed as a multi-agent research environment in which specialised AI agents collaborate across different stages of the pancreatic cancer image-analysis workflow. Rather than functioning as a conventional single-model segmentation pipeline, the Virtual Lab aims to support an integrated research process encompassing **data preparation, image analysis, segmentation, quality assessment, experimental evaluation, and research reporting**.

The project builds upon research in **AI-driven medical image segmentation**, with a particular focus on developing an agentic framework that can support reproducible and human-supervised pancreatic tumor analysis.

---

## Research Objective

The primary objective is to develop and investigate an **AI-driven agentic Virtual Lab** capable of coordinating specialised computational agents for pancreatic tumor segmentation using three-dimensional medical imaging data.

### Key objectives

* Develop an agentic architecture for pancreatic tumor segmentation.
* Integrate specialised AI agents for different research tasks.
* Process and analyse 3D medical imaging data.
* Investigate automated tumour-region segmentation.
* Support reproducible model training and evaluation.
* Incorporate quality-control and validation mechanisms.
* Maintain human-in-the-loop scientific oversight.
* Provide an auditable workflow for computational experiments.
* Establish a foundation for future AI-assisted pancreatic cancer research.

---

## Proposed Virtual Lab Architecture

The Virtual Lab is envisioned as a **multi-agent research environment**, where individual agents perform specialised tasks while a coordinating agent manages the overall research workflow.

### Conceptual workflow

```text
                    ┌──────────────────────────┐
                    │      Research Question   │
                    └────────────┬─────────────┘
                                 │
                                 ▼
                    ┌──────────────────────────┐
                    │       PI / Orchestrator   │
                    │           Agent           │
                    └────────────┬─────────────┘
                                 │
          ┌──────────────────────┼──────────────────────┐
          │                      │                      │
          ▼                      ▼                      ▼
 ┌────────────────┐     ┌────────────────┐     ┌────────────────┐
 │ Data Curation  │     │ Image Analysis │     │ Literature /   │
 │     Agent      │     │     Agent      │     │ Evidence Agent │
 └───────┬────────┘     └───────┬────────┘     └────────────────┘
         │                      │
         └──────────────┬───────┘
                        ▼
              ┌────────────────────┐
              │ Segmentation Agent │
              │   2D / 3D Models   │
              └─────────┬──────────┘
                        │
                        ▼
              ┌────────────────────┐
              │ Evaluation & QA    │
              │       Agent        │
              └─────────┬──────────┘
                        │
                        ▼
              ┌────────────────────┐
              │ Visualisation &    │
              │ Reporting Agent    │
              └─────────┬──────────┘
                        │
                        ▼
              ┌────────────────────┐
              │ Human Researcher   │
              │   Validation Loop  │
              └────────────────────┘
```

---

## Agentic Research Components

The proposed Virtual Lab may include the following specialised agents:

| Agent                            | Primary Responsibility                                         |
| :------------------------------- | :------------------------------------------------------------- |
| **PI / Orchestrator Agent**      | Coordinates the overall research workflow and delegates tasks  |
| **Literature Agent**             | Retrieves and organises relevant scientific evidence           |
| **Data Curation Agent**          | Organises datasets, metadata, preprocessing and quality checks |
| **Medical Image Analysis Agent** | Performs image exploration and quantitative analysis           |
| **Segmentation Agent**           | Executes and manages 3D pancreatic tumor segmentation models  |
| **Model Training Agent**         | Automates training, checkpointing and experiment configuration |
| **Evaluation Agent**             | Computes segmentation metrics and comparative results          |
| **Quality Assurance Agent**      | Performs consistency and quality-control checks                |
| **Visualisation Agent**          | Generates segmentation overlays and research visualisations    |
| **Research Reporting Agent**     | Produces structured experimental summaries and reports         |
| **Human-in-the-Loop Layer**      | Enables researcher review, validation and scientific decisions |

> **Note:** The final agent architecture will be refined during the research and implementation phases.

---

# Pancreatic Tumour Segmentation

The segmentation component focuses on identifying and delineating **pancreatic tumour regions in 3D medical images**.

The initial research workflow may include:

```text
3D Medical Images
        │
        ▼
Data Quality Assessment
        │
        ▼
Preprocessing
        │
        ▼
Image Normalisation
        │
        ▼
3D Model Training
        │
        ▼
Pancreatic Tumour Segmentation
        │
        ▼
Post-processing
        │
        ▼
Quantitative Evaluation
        │
        ▼
Visual Validation
        │
        ▼
Research Report
```

Potential segmentation architectures and approaches will be evaluated according to the research requirements and available datasets.

---

# Data Sources

This section documents the datasets and publicly available resources used for pancreatic tumour segmentation research.

| Dataset / Resource | Description | Link |
| :--- | :--- | :--- |
| **PanTS** | Pancreatic tumour segmentation research and reproduction resource | *To be added* |
| **PanTS 3D Dataset Access** | Access to the PanTS 3D medical imaging dataset | [![Google Drive](https://img.shields.io/badge/Google%20Drive-PanTS%203D%20Dataset%20Access-4285F4?style=for-the-badge&logo=googledrive&logoColor=white)](https://drive.google.com/drive/folders/12A56hYP44R_pKfK_HUMoVrkpWT5itceF) |
| **Research Literature** | Published studies and benchmark methodologies | *To be added* |

### Dataset documentation

For each dataset, the repository will document:

* Dataset name and source
* Imaging modality
* Number of cases
* Image dimensions / resolution
* Annotation format
* Training / validation / testing split
* Preprocessing requirements
* Licensing and usage conditions
* Citation requirements

> **Data-use principle:** Only datasets that are legally accessible and appropriately licensed for the intended research purpose will be used.

---

# Research Resources

| Resource | Link |
| :--- | :--- |
| **Research Concept Note** | [![Research Concept Note](https://img.shields.io/badge/Research%20Concept%20Note-Open%20Document-F39C12?style=for-the-badge\&logo=google\&logoColor=white)](https://docs.google.com/document/d/16WZZN5kf4IAWRCzSOtsbxhngEN2JQmxAd-6BGR6OXZU/edit?usp=sharing) |
| **Open PanTS 3D Data Preparation & Quality Audit** | [![Google Colab](https://img.shields.io/badge/Google%20Colab-PanTS%203D%20Data%20Preparation%20%26%20Audit-F9AB00?style=for-the-badge\&logo=googlecolab\&logoColor=white)](https://colab.research.google.com/drive/1GU7P0Z3VTJDB5cm73ur6uwZNDV9RivSF?usp=sharing) |
| **PanTS Research Repository** | *To be added* |                                                                                                         

---

# Research Workflow

The Virtual Lab follows a structured research pipeline:

### Phase 1 — Research Definition

* Define the research question.
* Establish hypotheses and objectives.
* Review relevant literature.
* Identify datasets and computational requirements.

### Phase 2 — Data Preparation

* Dataset acquisition.
* Data organisation.
* Quality assessment.
* Preprocessing and normalisation.
* Training/validation/testing preparation.

### Phase 3 — Model Development

* Baseline implementation.
* 3D segmentation model development.
* Hyperparameter configuration.
* Training and checkpoint management.

### Phase 4 — Agentic Integration

* Agent design.
* Agent communication.
* Workflow orchestration.
* Automated experiment management.
* Research audit logging.

### Phase 5 — Evaluation

* Quantitative segmentation evaluation.
* Visual assessment.
* Error analysis.
* Comparative experiments.
* Robustness analysis.

### Phase 6 — Human Validation

* Researcher review.
* Segmentation verification.
* Experimental interpretation.
* Error correction and feedback.

### Phase 7 — Research Reporting

* Automated experiment summaries.
* Result visualisation.
* Reproducibility documentation.
* Scientific reporting.

---

# Evaluation

Segmentation performance will be evaluated using appropriate quantitative and qualitative measures.

Potential metrics include:

| Metric                                        | Purpose                                                              |
| :-------------------------------------------- | :------------------------------------------------------------------- |
| **Dice Similarity Coefficient (DSC)**         | Measures overlap between predicted and reference tumor regions      |
| **Intersection over Union (IoU)**             | Measures segmentation overlap                                        |
| **Precision**                                 | Measures the proportion of predicted tumor regions that are correct |
| **Recall / Sensitivity**                      | Measures the proportion of tumour regions successfully identified    |
| **Hausdorff Distance (HD)**                   | Evaluates boundary-level disagreement                                |
| **95th Percentile Hausdorff Distance (HD95)** | Provides a robust boundary-distance measure                          |
| **Inference Time**                            | Measures computational efficiency                                    |

The final evaluation protocol will be determined according to the selected dataset, model architecture and research objectives.

---

# Reproducibility & Auditability

A core principle of the Virtual Lab is **reproducible computational research**.

The repository is intended to maintain:

* Dataset documentation
* Preprocessing configurations
* Model configurations
* Training scripts
* Model checkpoints
* Testing scripts
* Evaluation results
* Experiment metadata
* Agent execution logs
* Research reports
* Version-controlled source code

Where possible, experiments should be executable through a clearly documented workflow.

---

# Human-in-the-Loop Research

The Virtual Lab is intended to **assist researchers rather than replace scientific judgement**.

Human researchers remain responsible for:

* Defining research objectives.
* Reviewing evidence.
* Validating experimental results.
* Interpreting biological and clinical implications.
* Approving research decisions.
* Reviewing model errors and limitations.

The agentic system provides computational assistance, orchestration and automation while maintaining researcher oversight.

---

# Responsible AI & Data Governance

The project will consider responsible research practices throughout development, including:

* Appropriate dataset licensing.
* Privacy-preserving data handling where applicable.
* Secure research environments.
* Reproducible computational workflows.
* Transparent model evaluation.
* Human oversight.
* Explicit documentation of limitations.
* Clear separation between computational predictions and clinical decisions.

> **Important:** Research outputs from this project are intended for scientific investigation and development. They should not be interpreted as clinical diagnoses or medical recommendations.

---

# Repository Structure

The repository is organised to support modular development and reproducible research.

```text
Virtual-Lab-PanTS/
│
├── Logo/
│   └── VL_Agentic_System_PanTS.png
│
├── Data/
│   ├── README.md
│   └── Dataset_Information/
│
├── Literature/
│   └── README.md
│
├── Agents/
│   ├── Orchestrator/
│   ├── Data_Curation/
│   ├── Image_Analysis/
│   ├── Segmentation/
│   ├── Evaluation/
│   └── Reporting/
│
├── Models/
│   ├── Baseline/
│   └── Experiments/
│
├── Experiments/
│   ├── Training/
│   ├── Testing/
│   └── Results/
│
├── Notebooks/
│
├── Documentation/
│
├── Results/
│
├── requirements.txt
│
└── README.md
```

---

# Research Development Status

| Component                    |     Status     |
| :--------------------------- | :------------: |
| Research concept             | 🟢 Defined   |
| Literature review            | 🟡 In progress |
| Dataset identification       | 🟡 In progress |
| PanTS reproduction           | 🟡 In progress |
| Baseline segmentation model  | ⚪ Planned |
| Agent architecture           | ⚪ Planned |
| Virtual Lab integration      | ⚪ Planned   |
| Experimental evaluation      | ⚪ Planned   |
| Human-in-the-loop validation | ⚪ Planned   |
| Research reporting           | ⚪ Planned   |

**Legend:**
🟢 Defined · 🟡 In Progress · ⚪ Planned

---

# Technology Stack

The implementation may integrate technologies from the following areas:

* **Python**
* **PyTorch / TensorFlow**
* **MONAI**
* **NumPy**
* **SciPy**
* **Pandas**
* **Jupyter**
* **Docker**
* **LLM-based AI agents**
* **Workflow orchestration frameworks**
* **3D medical image processing tools**

The final technology stack will depend on experimental requirements and system architecture.

---

# Related Research

This project is part of broader research into **Computational Healthcare Intelligence**, combining:

```text
Artificial Intelligence
        +
Medical Imaging
        +
Machine Learning
        +
Agentic AI
        +
Computational Cancer Research
        +
Human-in-the-Loop Research
```

The long-term objective is to investigate how agentic computational systems can support **reproducible, auditable and collaborative biomedical research workflows**.

---
## Motivation

Our pancreatic tumour segmentation research is motivated by recent advances in **medical image segmentation, AI-driven radiology, and reproducible open-source research**. The following resources provide key methodological, scientific, and implementation foundations for this work.

| **Researcher / Resource** | **Research Papers & Open-Source Implementations** |
|:---|:---|
| **Prof. Dr. Zongwei Zhou** | [Website](https://www.zongweiz.com) · [PanTS GitHub Repository](https://github.com/MrGiovanni/PanTS) |
| **Relevant Research Papers** | [Paper 1](https://arxiv.org/abs/2507.01291) · [Paper 2](https://arxiv.org/abs/1912.05074) · [Paper 3](https://arxiv.org/abs/2102.04306) · [Paper 4](https://arxiv.org/abs/2203.00131) · [Paper 5](https://arxiv.org/html/2604.20981v1) |
| **Multiclass segmentation model** | [Link](https://neuroneural.net/brainchop-test/)|

# Research Leadership

**Dr. Didar Murad**

Principal Investigator & Founding Director

**Computational Healthcare Intelligence Lab (CHI Lab), ICRI-STE**

[![CHI Lab](https://img.shields.io/badge/CHI%20Lab-Research-0A7EA4?style=for-the-badge)](https://icriste.com/computational-healthcare-intelligence-lab-chi-lab/)
[![ICRI-STE Website](https://img.shields.io/badge/Website-ICRI--STE-00A6A6?style=for-the-badge&logo=googlechrome&logoColor=white)](https://icriste.com)

The project is developed within the broader research activities of the **Computational Healthcare Intelligence Lab (CHI Lab)**.

---

# Research Disclaimer

This repository represents an ongoing research and development project. Components, methodologies, datasets, models and experimental results may change as the research progresses.

Unless explicitly stated otherwise, materials in this repository should be considered **research prototypes** and not clinically validated systems.

---

# Citation

If this research, software, methodology or associated resources are used in academic work, please cite the corresponding publication or research concept note once available.

```bibtex
@misc{murad_virtual_lab_pants,
  author       = {Murad, Didar},
  title        = {Virtual Lab: An AI-Driven Agentic System for
                  Pancreatic Tumour Segmentation Using 3D Medical Images},
  year         = {2026},
  note         = {Research and development project}
}
```

---

<p align="center">
  <strong>Computational Healthcare Intelligence Lab (CHI Lab)</strong>
  <br>
  <strong>ICRI-STE</strong>
  <br><br>
  <em>AI-Driven · Reproducible · Human-Centred Biomedical Research</em>
</p>


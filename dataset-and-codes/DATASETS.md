# 📊 Agrogami AI — Benchmark Datasets & Repository Directory

> **Directory:** `agrogami-ai-scaffolding` / `dataset-and-codes`  
> **Total Benchmarks:** 5 Curated Corpora (Multimodal, Tabular & Relational)  
> **Project Scope:** Alternative Credit Scoring, Document AI & Bengali Handwriting  
> **Affiliation:** CSE 404 (Group 05_53_06)

---

### 🗂 Directory Schema & Mirrors

<details open>
<summary><b>01 · Tabular & Credit Scoring Benchmarks (2 Datasets)</b></summary>

| ID | Benchmark / Directory | Modality | Target Schema | Kaggle Mirror |
|:--:|:----------------------|:--------:|:--------------|:--------------|
| **01** | `01_UCI_Taiwan_Default/` | Tabular | `UCI_Credit_Card.csv` | [uciml/default-of-credit-card-clients-dataset](https://www.kaggle.com/datasets/uciml/default-of-credit-card-clients-dataset) |
| **02** | `02_South_German_Credit/` | Tabular | `codetable.txt`, `read_SouthGermanCredit.R`, `SouthGermanCredit.asc` | [tmchls/south-german-credit-update-data-set](https://www.kaggle.com/datasets/tmchls/south-german-credit-update-data-set) |

</details>

<details open>
<summary><b>02 · Document AI & Vision Benchmarks (2 Datasets)</b></summary>

| ID | Benchmark / Directory | Modality | Target Schema | Kaggle Mirror |
|:--:|:----------------------|:--------:|:--------------|:--------------|
| **03** | `03_FUNSD/` | Document AI | `dataset/` (`testing_data/`, `training_data/`) | [sharmaharsh/form-understanding-noisy-scanned-documentsfunsd](https://www.kaggle.com/datasets/sharmaharsh/form-understanding-noisy-scanned-documentsfunsd) | [sharmaharsh/form-understanding-noisy-scanned-documentsfunsd](https://www.kaggle.com/datasets/sharmaharsh/form-understanding-noisy-scanned-documentsfunsd) |
| **04** | `04_BanglaWriting/` | Vision / HTR | `raw.zip` | [reasat/banglawriting](https://www.kaggle.com/datasets/reasat/banglawriting) |

</details>

<details open>
<summary><b>03 · Relational Banking & Cash-Flow Benchmarks (1 Dataset)</b></summary>

| ID | Benchmark / Directory | Modality | Target Schema | Kaggle Mirror |
|:--:|:----------------------|:--------:|:--------------|:--------------|
| **05** | `05_PKDD99_Financial/` | Relational | `account.csv`, `card.csv`, `client.csv`, `disp.csv`, `district.csv`, `loan.csv`, `order.csv`, `trans.csv` | [marceloventura/the-berka-dataset](https://www.kaggle.com/datasets/marceloventura/the-berka-dataset) |

</details>

---

### 🔍 Corpus Overviews

#### 01 · UCI Taiwan Credit Default
* **Scope:** Financial default risk prediction benchmark comprising 30,000 observations of credit clients in Taiwan.
* **Key Attributes:** Demographics, historical repayment delinquency tracking, monthly billing statements, and credit line utilization.

#### 02 · South German Credit (Groemping Update)
* **Scope:** Standardized machine-learning update of the 1,000-case German Credit risk assessment task.
* **Key Attributes:** Personal account balance status, credit duration, contractual repayment discipline, and structural co-maker attributes.

#### 03 · FUNSD (Form Understanding in Noisy Scanned Documents)
* **Scope:** Fully annotated spatial document layout analysis and Key-Value extraction corpus for document understanding models (e.g., LayoutLMv3, Donut).
* **Key Attributes:** Token-level semantic labeling across 199 annotated real-world scanned form images partitioned into formal training and testing subsets.

#### 04 · BanglaWriting
* **Scope:** Large-scale offline Bengali handwritten script corpus designed for low-resource HTR (Handwritten Text Recognition).
* **Key Attributes:** Word and bounding-box level annotations capturing variable handwriting styles, stroke characteristics, and glyph variations across native writers.

#### 05 · The Berka Dataset (PKDD '99 Financial)
* **Scope:** Comprehensive multi-table relational banking benchmark capturing anonymized customer transactions from a Czech financial institution (1993–1998).
* **Key Attributes:** 8 relational tables linking credit cards (`card.csv`), loan performance (`loan.csv`), account profiles (`account.csv`), and ledger transactions (`trans.csv`).

---
<sub>Agrogami AI · CSE 404 (Group 05_53_06) · Benchmark Corpora & Dataset Archive</sub>
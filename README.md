
# 📊 Monitoring & Evaluation – Real-Time Feedback Mechanism

**Urban Humanitarian Food Security Program (Nairobi, Kenya)**

![R](https://img.shields.io/badge/R-4.3+-blue)
![RMarkdown](https://img.shields.io/badge/RMarkdown-Analysis-green)
![Status](https://img.shields.io/badge/Status-Complete-success)

---

## 📌 Project Overview

This project presents a **Monitoring and Evaluation (M&E) analysis** of a **community-based Real-Time Feedback Mechanism (RTFM)** implemented within an urban humanitarian food security program in Nairobi, Kenya.

The analysis demonstrates how feedback systems enhance **Accountability to Affected Populations (AAP)**, program quality, and adaptive learning.
All data used are **simulated** to reflect real humanitarian MEAL systems while maintaining ethical and data protection standards.

---

## 🌍 Study Context

The simulated intervention is contextualized within the following Nairobi informal settlements:

* Kibera
* Mathare
* Mukuru kwa Njenga
* Korogocho

---

## 🎯 Objectives

### General Objective

To evaluate the effectiveness of a community-based real-time feedback mechanism in an urban humanitarian food security program.

### Specific Objectives

* Assess accessibility and utilization of feedback channels
* Evaluate response timeliness and data quality
* Identify operational challenges and best practices
* Demonstrate a replicable MEAL analytics framework

---

## 🗂 Project Structure

```
Monitoring-Evaluation/
│
├── Monitoring-Evaluation.Rmd        # Main R Markdown analysis
├── Monitoring-Evaluation.docx       # Final knitted report (Word)
├── Monitoring-Evaluation.knit.md    # Markdown version (optional, GitHub-renderable)
├── README.md                        # Project documentation
│
├── data/
│   └── Monitoring_and_Evaluation_project_data.xlsx
│
└── outputs/
    ├── figures/
    └── tables/
```

---

## 📊 Data Description

All datasets are **synthetic/simulated** and structured to mirror real humanitarian MEAL systems:

* Beneficiary demographic profiles
* Feedback submissions (SMS, hotline, helpdesk)
* Response tracking and resolution status
* Qualitative feedback themes

⚠️ No real personal or sensitive data are included.

---

## 🛠 Tools & Technologies

* **R (≥ 4.3.0)**
* **RStudio**
* **R Markdown / Quarto**
* Key packages:

  * `tidyverse`
  * `lubridate`
  * `janitor`
  * `readxl`
  * `ggplot2`

Pandoc is bundled with RStudio.

---

## ▶️ How to Run the Project Locally

1. Clone or download the repository
2. Open `Monitoring-Evaluation.Rmd` in RStudio
3. Ensure the `data/` folder is in the project root
4. Install required packages:

   ```r
   install.packages(c("tidyverse", "lubridate", "janitor", "readxl"))
   ```
5. Click **Knit**

📄 Output generated:

```
Monitoring-Evaluation.docx
```

---

## 🔄 Understanding the Rendering Process (R Markdown)

```
.Rmd  →  .knit.md  →  .docx
```

* `.Rmd` → Source analysis file
* `.knit.md` → Intermediate Markdown (Pandoc processing)
* `.docx` → Final report

The `.knit.md` file is optional and only kept if explicitly enabled.

---

## 🚫 When Files Fail to Render on GitHub (Important)

GitHub has **limited preview capabilities**. Some files that work perfectly on your computer **will not render in the GitHub interface**.

### ❌ Files GitHub Does NOT Render

* `.Rmd` (R Markdown source files)
* `.docx` (Word documents)
* Large or complex `.pdf` files

You may see messages such as:

* *“Sorry, something went wrong while trying to render this file”*
* A blank preview
* Download-only behavior

✅ **This is expected and NOT an error in the project.**

---

## ✅ Files GitHub CAN Render

GitHub natively supports:

* `README.md`
* `.md` (Markdown)
* `.png`, `.jpg`
* Small `.csv` and `.txt` files

For this reason, the repository includes:

---

## 🧭 What To Do When Rendering Fails on GitHub

### 🔹 Option 1: Download and Open Locally (Recommended)

1. Click the file
2. Select **Download**
3. Open using the appropriate software:

   * `.Rmd` → RStudio
   * `.docx` → Microsoft Word
   * `.pdf` → PDF reader

---

### 🔹 Option 2: View the Markdown Version

If available, open:

```
Monitoring-Evaluation.knit.md
```

This file:

* Renders directly on GitHub
* Shows the full report structure
* Is ideal for reviewers who cannot run R

> ℹ️ This file exists only if `keep_md: true` was enabled during knitting.

---

### 🔹 Option 3: Use Raw View

For text-based files:

1. Click **Raw**
2. View or copy the plain text
3. Download if needed

---

### 🔹 Option 4: GitHub Pages (Optional Enhancement)

For full browser-based viewing:

* Knit the report to `html_document`
* Push the `.html` file
* Enable **GitHub Pages** in repository settings

This allows live viewing without downloads.

---

## 📈 Key Outputs

* Beneficiary descriptive statistics
* Feedback channel utilization metrics
* Response time and SLA compliance analysis
* Thematic analysis of feedback issues
* Visual summaries and actionable recommendations

---

## 🔐 Ethical Considerations

* 100% simulated data
* No personal identifiers
* Suitable for training, portfolios, and academic use
* Aligned with humanitarian data protection principles

---

## 👥 Intended Audience

* MEAL Officers & Data Analysts
* NGOs & Humanitarian Organizations
* Public Health & Statistics Students
* Internship and job application portfolios
* Donor and program reporting simulations

---

## 📥 How to Get This Project

### Clone from GitHub

```bash
git clone https://github.com/ookochrispine/Monitoring-Evaluation.git
```

### Download ZIP

Use **Code → Download ZIP** from the repository page.

---

## 👤 Author

**Chrispine Buxtone Ooko**
Applied Statistician | Public Health & MEAL Practitioner
Humanitarian Analytics • Disease Modeling • Accountability Systems



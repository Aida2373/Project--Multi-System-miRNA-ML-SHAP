# An Integrative Machine Learning and SHAP-Based Identification of Candidate miRNAs Linked to Inflammatory Pathways Across Pulmonary, Neurological and Cardiovascular Diseases

## ⚠️ Academic & Publication Notice
> **Manuscript Status:** Publication Pipeline / In Preparation
> To strictly comply with peer-review integrity guidelines and safeguard proprietary feature-selection architectures prior to official publication, the raw backend data-preprocessing scripts and model training code are maintained in a secure, **private repository**. Full codebase access can be seamlessly granted to PhD admissions committees, reviewers, or prospective Principal Investigators (PIs) upon direct request via a secure contributor link.

---

## 📌 Project Abstract & Analytical Framework
Pulmonary, neurological and cardiovascular diseases are complex disorders characterized by shared inflammatory and molecular dysregulation. MicroRNAs (miRNAs) function as vital post-transcriptional regulators of inflammation and immune response across these conditions. 

This research presents an integrative machine learning and SHAP (SHapley Additive exPlanations) framework for multi-disease classification using peripheral blood miRNA expression profiles to isolate robust biomarkers and decipher underlying cross-disease mechanisms.

### 📊 Computational Workflow & Performance Metrics
* **Objective:** Investigated the role of miRNA-mediated regulation in inflammatory pathways across pulmonary, cardiovascular, and neurological disease groups, with a strict emphasis on identifying shared and disease-specific molecular mechanisms driven by chronic inflammation and immune dysregulation.
* **Data Source:** Raw peripheral blood miRNA datasets spanning **Lung Cancer, Chronic Obstructive Pulmonary Disease (COPD), Glioma, and Multiple Sclerosis (MS), Myocardial Infarction (MI) and Heart Failure (HF)** were systematically retrieved from public repositories.
* **Model Benchmarking:** Following extensive preprocessing, four distinct machine learning classifiers were developed and benchmarked. The **Random Forest** architecture achieved top-tier baseline performance with a predictive accuracy of **75%**.
* **Explainable AI Framework:** The top 20 predictive features were isolated using model-agnostic feature importance and thoroughly interpreted using **SHAP analysis** to evaluate the exact local and global mathematical contributions of candidate miRNAs.
* **Biological Translation:** Functional pathways analysis revealed that the top-contributing miRNAs converge on critical inflammatory and oncogenic pathways including **NF-κB, PI3K/Akt, MAPK, and HIF-1α**, mapping the precise links between immune activation, oxidative stress, and multi-organ tumorigenesis across the target disorders.
* **External Validation Considerations:** Due to the scarcity of comprehensive, independent multi-disease profiles in the public domain at the time of execution, external validation was constrained. The identified features were instead treated as high-potential candidates and subjected to extensive downstream biological relevance validation via literature mining and pathway enrichment.

---

## 🛠️ Computational Environment & Stack
The machine learning pipeline and explainable AI architectures were constructed using robust data science toolkits:
* **Feature Selection & ML:** Data science processing stack for Random Forest multi-class implementation, data array manipulation, and model benchmark evaluations.
* **Explainable AI:** Model-agnostic frameworks for generating local and global feature attribution interpretations, including beeswarm layouts and predictive impact summary plots.
* **Bioinformatics Pipeline:** Public multi-cohort transcriptomic matrices compiled for systemic cross-comparisons.

---

## 📂 Repository Contents
* `README.md` — Complete theoretical, methodological, and architectural framework.
* `plots/` *(Optional Upload)* — Folder reserved for peer-reviewed SHAP summary plots, Random Forest confusion matrices, and biological pathway network graphs.

---

## 📄 Contact & Secure Code Requests
For academic inquiries, potential PhD advising discussions, or to request secure, private access to the backend machine learning scripts for verification, please reach out directly:
* **Researcher:** Aida Ferrutia Peter
* **Email:** aidaferrutia10@gmail.com
* **Institution:** Anna University

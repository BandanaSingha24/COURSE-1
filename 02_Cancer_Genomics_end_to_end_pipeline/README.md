# 🧬 Genomics End-to-End Pipeline

A streamlined bioinformatics pipeline for **Somatic Variant Analysis** in cancer genomics.

## 🚀 Workflow Steps
1. **Setup:** Environment & Tool configuration (GATK, BWA, Samtools).
2. **FASTQ Data:** Automated download of tumor-normal FASTQ files.
3. **FASTQ QC:** Quality assessment using FastQC.
4. **Alignment:** Mapping reads to reference genome (hg19) via BWA-MM.
5. **Variant Calling:** Somatic mutation detection using **Mutect2**.
6. **Filtering:** Precision filtering with **FilterMutectCalls**.
7. **Annotation:** Biological impact assessment.
8. **Visualization:** Data extraction and analysis using **Pandas**.

## 🛠️ Tech Stack
* **Environment:** Google Colab (Jupyter Notebook)
* **Bio-Tools:** GATK v4.5.0, Mutect2, BWA-MEM, Samtools
* **Data Processing:** Python (Pandas), Bash/Shell scripting

## 📊 Results & Findings
* **Execution:** Successfully completed the end-to-end somatic analysis pipeline.
* **Variant Detection:** The current subsampled dataset (50,000 read pairs) resulted in an empty variant set after applying GATK's strict filtering criteria.
* **Conclusion:** This result validates the pipeline's functionality. For actual mutation discovery, this workflow is ready to be scaled to full-sized sequencing datasets.

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18215032.svg)](https://doi.org/10.5281/zenodo.18215032)

# MDEAW: A Multimodal Dataset for Emotion Analysis in a Classroom Scenario

This repository contains the **MDEAW dataset**, a multimodal database consisting of Electrodermal Activity (EDA) and Photoplethysmography (PPG) signals recorded during real-world exam scenarios. It also includes the pre-print version of the associated research paper.

## 📄 Overview

We present **MDEAW**, a dataset designed to elicit and analyze emotional reactions in students within a classroom environment. The data was recorded during exams at Eurecat Academy (Sabadell, Barcelona).

**Key Features:**
* **Subjects:** 10 students.
* **Signals:** EDA and PPG (captured using portable, wearable, wireless, low-cost, off-the-shelf equipment).
* **Context:** Real-world exam scenarios.
* **Labels:** Self-assessment of affective states (6 basic emotions) recorded after each stimulus.
* **Baselines:** The dataset establishes baselines using ReMECS, Fed-ReMECS, and Fed-ReMECS-U algorithms.

The goal of this dataset is to allow researchers to evaluate the suitability of low-cost capturing devices for emotion state recognition in everyday applications.

## 📂 Repository Structure

The dataset and documentation are organized as follows:

* **`MDEAW_Dataset.tar.xz`**: The main compressed dataset.
* **`Preprint_Article.pdf`**: The full text of the research paper.
* **Code**: Scripts used for feature extraction and baseline models.

### Dataset Contents (inside the compressed file)
Once decompressed, the dataset follows this structure:

| Folder/File | Description |
| :--- | :--- |
| `raw-data/` | Contains the raw EDA and PPG signal recordings from the wearable devices. |
| `extracted-features/` | Processed data with features extracted for machine learning tasks. |
| `emotion-labels-info.xlsx` | Ground truth file containing student self-assessments and emotion labels. |

## 🚀 How to Download and Use the Data

Due to the size of the dataset, the files are compressed using the **.tar.xz** format to ensure high compression and integrity.

### 1. Download
Clone the repository or download the `MDEAW_Dataset.tar.xz` file directly.

### 2. Decompress
**For macOS / Linux (Terminal):**
Navigate to the folder and run:

    tar -xf MDEAW_Dataset.tar.xz

*(Note: If your file has a different name, replace `MDEAW_Dataset.tar.xz` with your actual filename)*.

**For Windows:**
You can use tools like **7-Zip** or **WinRAR**:
1. Right-click the `.tar.xz` file.
2. Select "Extract here".

---

## 📚 Citation

If you use this dataset in your research, please cite the associated dataset record via Zenodo:

    @dataset{mdeaw_dataset_2026,
      author       = {Xhafa, Fatos},
      title        = {MDEAW: A Multimodal Dataset for Emotion Analysis in a Classroom Scenario},
      year         = {2026},
      publisher    = {Zenodo},
      version      = {v1.0.0},
      doi          = {10.5281/zenodo.18215032},
      url          = {https://doi.org/10.5281/zenodo.18215032}
    }

## 📧 Contact

For any questions regarding the dataset usage, collaboration, or the code, please feel free to contact the authors:

**Prof. Fatos Xhafa**
* **Affiliation:** Universitat Politècnica de Catalunya (UPC)
* **Email:** fatos.xhafa [at] upc.edu
* **Web:** https://www.cs.upc.edu/~fatos/

---
---
*If you encounter any technical issues with the repository, please open an Issue here on GitHub.*

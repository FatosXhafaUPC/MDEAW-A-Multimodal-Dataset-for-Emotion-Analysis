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

## 🔗 Related Datasets

This work builds upon and complements other standard multimodal emotion datasets used in our research:

* **DEAP:** A dataset for emotion analysis using physiological signals (EEG and peripheral) triggered by music videos.
* **AMIGOS:** A dataset for mood, personality, and affect research on individuals and groups.

## 📖 Related Publications

The following publications are related to the methodologies, algorithms (ReMECS, Fed-ReMECS), and data collection strategies used in this work:

* Arijit Nandi, Fatos Xhafa, Rohit Kumar. **A Docker-based federated learning framework design and deployment for multi-modal data stream classification.** *Computing* 105(10): 2195-2229 (2023).
* Arijit Nandi, Fatos Xhafa, Laia Subirats, Santi Fort. **Reward-Penalty Weighted Ensemble for Emotion State Classification from Multi-Modal Data Streams.** *Int. J. Neural Syst.* 32(12): 2250049:1-2250049:22 (2022).
* Arijit Nandi, Fatos Xhafa, Laia Subirats, Santi Fort. **Federated Learning with Exponentially Weighted Moving Average for Real-Time Emotion Classification.** *ISAmI* 2022: 123-133.
* Arijit Nandi, Fatos Xhafa, Laia Subirats, Santi Fort. **MDEAW: A Multimodal Dataset for Emotion Analysis through EDA and PPG signals from wireless wearable low-cost off-the-shelf Devices.** *CoRR abs/2207.06410* (2022).
* Arijit Nandi, Fatos Xhafa, Laia Subirats, Santi Fort. **Real-Time Emotion Classification Using EEG Data Stream in E-Learning Contexts.** *Sensors* 21(5): 1589 (2021).
* Arijit Nandi, Fatos Xhafa, Laia Subirats, Santi Fort. **Real-Time Multimodal Emotion Classification System in E-Learning Context.** *EANN* 2021: 423-435.
* Arijit Nandi, Fatos Xhafa, Laia Subirats, Santi Fort. **A Survey on Multimodal Data Stream Mining for e-Learner's Emotion Recognition.** *COINS* 2020: 1-6.

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

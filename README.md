<div align="center">
  <h1>Multi-Taxa Bioacoustic Data Downloader</h1>
    
</div>
<br>
<div align="center">

![License](https://img.shields.io/github/license/Md-Shaid-Hasan-Niloy/Macaulay_downloader)
![OS](https://badgen.net/badge/OS/Linux%2C%20Windows%2C%20macOS/blue)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![GitHub release](https://img.shields.io/github/v/release/Md-Shaid-Hasan-Niloy/Macaulay_downloader)](https://github.com/Md-Shaid-Hasan-Niloy/Macaulay_downloader/releases/latest)

[![GitHub issues](https://img.shields.io/github/issues/Md-Shaid-Hasan-Niloy/Macaulay_downloader)](https://github.com/Md-Shaid-Hasan-Niloy/Macaulay_downloader/issues)
![GitHub stars)](https://img.shields.io/github/stars/Md-Shaid-Hasan-Niloy/Macaulay_downloader)
[![Collaborators](https://img.shields.io/badge/Collaboration-Welcome-brightgreen)](CONTRIBUTING.md)

</div>

<br>

**Automated Python utility for bulk downloading animal vocalizations from Macaulay Library and Xeno-Canto for Machine Learning (ML) research.**

---

## 🚀 Project Goal (Phase 1: Data Acquisition)

This repository contains the core scripts used to collect and structure the training data for a generalized animal sound classification model (inspired by the BirdNET project).

The objective is to gather high-volume, labeled acoustic data across **multiple taxa** (birds, mammals, amphibians, insects) from global community science archives to build a robust deep learning dataset.

---

## 📖 Table of Contents

* [Features](#-features)
* [Setup and Installation](#-setup-and-installation)
* [Usage](#-usage)
* [Next Steps](#-next-steps)
* [Contribution](#-contribution)
* [License](#-license)
* [Contact](#-contact)

---

## ✨ Features

* **Multi-Source:** Downloads audio files from both the **Macaulay Library** (via eBird API) and **Xeno-Canto**.
* **Hierarchical Structure:** Organizes all downloaded audio into a logical, hierarchical folder structure (e.g., `data/Species_Name/Audio_ID.mp3`) suitable for direct use in deep learning pipelines.
* **Progress Tracking:** Efficiently resumes downloads and handles file naming conventions from both libraries.

---

## 🛠️ Setup and Installation

### Prerequisites

You need **Python 3.8+** installed.

### Installation

**1. Clone the Repository:**

```bash
git clone [https://github.com/Md-Shaid-Hasan-Niloy/Macaulay_downloader.git](https://github.com/Md-Shaid-Hasan-Niloy/Macaulay_downloader.git)
cd Macaulay_downloader

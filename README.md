Multi-Taxa Bioacoustic Data Downloader

Automated Python utility for bulk downloading animal vocalizations from Macaulay Library and Xeno-Canto for Machine Learning (ML) research.

🚀 Project Goal (Phase 1: Data Acquisition)

This repository contains the core scripts used to collect and structure the training data for a generalized animal sound classification model (inspired by the BirdNET project).

The objective is to gather high-volume, labeled acoustic data across multiple taxa (birds, mammals, amphibians, insects) from global community science archives to build a robust deep learning dataset.

✨ Features

Multi-Source: Downloads audio files from both the Macaulay Library (via eBird API) and Xeno-Canto.

Hierarchical Structure: Organizes all downloaded audio into a logical, hierarchical folder structure (e.g., data/Species_Name/Audio_ID.mp3) suitable for direct use in deep learning pipelines.

Progress Tracking: Efficiently resumes downloads and handles file naming conventions from both libraries.

🛠️ Setup and Installation

Prerequisites

You need Python 3.8+ installed.

Installation

Clone the Repository:

git clone [https://github.com/Md-Shaid-Hasan-Niloy/Macaulay_downloader.git](https://github.com/Md-Shaid-Hasan-Niloy/Macaulay_downloader.git)
cd Macaulay_downloader


Install Dependencies:
Install the necessary Python packages using the provided requirements.txt file:

pip install -r requirements.txt


⚙️ Usage

The main script is Download_Audio.py. It is assumed that you have configured the necessary API credentials (e.g., Macaulay Library keys or eBird credentials) within the script itself or as environment variables.

To run the downloader script:

python Download_Audio.py


The script will begin downloading files, organizing them into a new directory, typically named data/ or downloads/.

⏭️ Next Steps

The next phase of the project involves pre-processing this raw audio data into Mel-spectrograms and designing the deep convolutional neural network (CNN) model architecture for multi-taxa classification.

🤝 Contribution

If you are an Honors College student looking to collaborate, please review the project goals and contact the repository owner. Contributions to data analysis, ML model development, and documentation are welcome.

📄 License

This project is licensed under the MIT License. See the LICENSE file for details.

📧 Contact

Md. Shaid Hasan Niloy – 

$$Your Email Address$$

 (Update this!)
Project Link: https://www.google.com/search?q=https://github.com/Md-Shaid-Hasan-Niloy/Macaulay_downloader

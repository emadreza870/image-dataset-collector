

---

markdown
# Image Dataset Collector

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A simple tool to **collect custom image datasets** from Bing.  
This repository provides a **ready-to-use Jupyter Notebook** that works both locally and on Google Colab, allowing you to download, organize, and zip images for machine learning or computer vision projects.

---

## 🚀 Features
- Download images automatically from Bing by search query.
- Customize queries and number of images per class.
- Organize results into folders by search term.
- Zip datasets into a single archive for easy sharing.
- Optional integration with **Google Colab + Google Drive**.

---


````

---

## 🔧 Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/emadreza870/image-dataset-collector.git
cd image-dataset-collector
pip install -r requirements.txt
````

---

## 📒 Usage

1. Open the Jupyter Notebook:

   ```bash
   jupyter notebook notebooks/Collecting_image_datasets.ipynb
   ```

2. Edit the parameters cell:

   ```python
   dataset_name = "spice_dataset"
   queries = ["Cuminum cyminum", "Lavandula"]
   limit_per_query = 200
   ```

3. Run the notebook cells step by step:

   * Install dependencies
   * Configure dataset parameters
   * Download images
   * Zip dataset
   * (Optional) Copy ZIP to Google Drive (Colab only)

---

## ☁️ Google Colab Integration

* Mount Google Drive in Colab.
* The dataset ZIP will be saved into:

  ```
  /content/drive/MyDrive/datasets
  ```

---

## ⚠️ Notes

* Always verify the **copyright** and **usage rights** of downloaded images.
* Review and clean your dataset (duplicates, irrelevant images, etc.).
* For training ML models, consider organizing data into `train/`, `val/`, `test/`.

---

## 📜 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

👨‍💻 Maintained by [emadreza870](https://github.com/emadreza870)
Contributions, suggestions, and pull requests are welcome!






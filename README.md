# Vision-Language Models Playground

> 🛠️ *Developed as part of my internship at **DreamBot**, this project involved comparing and testing multiple Vision-Language Models (VLMs) in diverse environments.*

This repository contains experiments and utilities for working with various **Vision-Language Models (VLMs)**, tested across Google Colab, Kaggle, and Jetson Nano platforms.

## 📁 File Structure

* `4_vlms.py`:
  Python script containing implementations and testing code for the following models:

  * **BLIP**
  * **Smol-VLM**
  * **Git-VLM**
  * **Nano-VLM**
    Optimized for execution in Google Colab or compatible environments.

* `tinyvlm.ipynb`:
  Jupyter Notebook tailored for **TinyVLM**, meant to be executed in **Kaggle Notebooks**. This notebook showcases usage, testing, and inference workflows with TinyVLM.

* `test images`:
  Folder containing sample test images used across different VLM models for inference and evaluation.

* `VLM types.xlsx`:
  Spreadsheet summarizing different VLM architectures, types, their sizes, capabilities, and intended use-cases.

* `README.md`:
  Project overview and guidance.

## 💡 Getting Started

1. **Google Colab (for 4\_vlms.py)**:

   * Upload `4_vlms.py` and the `test images` folder.
   * Run the script block by block, ensuring the test images are available in the correct path.

2. **Kaggle Notebook (for tinyvlm.ipynb)**:

   * Upload the notebook and test images.
   * Execute in GPU runtime for efficient inference.

3. **Model Comparison**:

   * Refer to `VLM types.xlsx` to understand model characteristics and make informed selection decisions.

## 🖼️ Test Images

All test images used for model evaluation are included in the `test images` folder. Make sure to adjust file paths accordingly in your code.



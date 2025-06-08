# Falling and Smoking Recognition using FastAI

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amir925/Falling-Smoking-recognition-with-fastAI/blob/main/Coder_DeepL_4ipynb.ipynb)

## 🧠 Project Overview

This project implements an image classification model using [FastAI](https://docs.fast.ai/) to detect two distinct situations:

- 🚬 **Smoking**
- 🤕 **Falling**

The main goal is to build a deep learning model that accurately recognizes these actions from image data.

## 📁 Dataset Structure

The data is organized into the following directory structure:

```
/DataML
├── /smoking       # Images of people smoking
├── /falling       # Images of people falling
```

## 🚀 Getting Started

To run this notebook in **Google Colab**, follow these steps:

1. Click the Colab badge above.
2. Make sure your Google Drive is mounted.
3. Ensure the path `/content/drive/MyDrive/DataML/` exists and contains your dataset.

## 📦 Dependencies

Install the required Python packages with:

```bash
pip install fastbook fastai kora Pillow
```

## 🧪 Model Training

The model uses the FastAI library for training and inference. Key steps include:

- Loading image data with `ImageDataLoaders`
- Resizing input images to a standard size (e.g., 224x224)
- Training a binary classification model to distinguish between smoking and falling

## 💾 Saving and Exporting

After training, the model can be saved and reloaded:

```python
learn.export('model.pkl')
```

## 👨‍💻 Author

- ✍️ AmirMohammad Ahmadi — 2022

## 📜 License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

> Contributions and suggestions are welcome! Feel free to open an issue or submit a pull request.

<div align="center">

# DeepLearning_lecture

**Keras-based deep learning lecture and assignment notebooks**

![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white) ![Deep Learning](https://img.shields.io/badge/Deep_Learning-7C3AED?style=flat-square)

[한국어](./README.md)

</div>

---

## Overview

This repository archives deep learning lecture and assignment notebooks with sample datasets, images, and model files. It includes Dense layers, sigmoid/tanh/ReLU experiments, Keras model construction, and iris/wine/housing-style exercises.

It is a lecture archive rather than a packaged application, so this README focuses on navigation and reproducibility notes.

The notebooks are useful as learning artifacts: they show activation functions, simple neural-network structure, classification datasets, and saved model assets in a sequence that follows the course material.

## Highlights

| Area | Description |
|---|---|
| Basic neural-network practice | `1강 코드.ipynb` covers Keras Dense layers and sigmoid output layers. |
| Manual implementation assignment | `과제 1 코드.ipynb` explores sigmoid/tanh neural-network behavior. |
| Classification practice | `과제2 코드.ipynb` and `와인 종류 예측하기.ipynb` cover iris and wine classification tasks. |
| Sample data | `data-master/` contains CSV, image, and hdf5 model files. |
| Lecture archive | Keeps notebooks, assignment code, and data assets in one place for later review. |

## Repository Structure

| Path | Role |
|---|---|
| *.ipynb | Lecture and assignment notebooks |
| data-master/ | CSV datasets, sample images, and model artifacts |

## Learning Order

1. Start with `1강 코드.ipynb` for basic Keras model structure and Dense layers.
2. Continue with `과제 1 코드.ipynb` to inspect sigmoid and tanh activation behavior.
3. Use `과제2 코드.ipynb` and `와인 종류 예측하기.ipynb` for classification examples.
4. Check `data-master/` to understand the CSV, image, and model assets used by the notebooks.

TensorFlow/Keras behavior may differ across versions. For reproducible runs, create a virtual environment, pin the required packages, and execute notebook cells in order.

## Quick Start

### Start Jupyter

```bash
jupyter lab
```

### List notebooks

```bash
find . -name "*.ipynb" | sort
```

### Suggested order

1강 코드.ipynb -> 과제 1 코드.ipynb -> 과제2 코드.ipynb -> 와인 종류 예측하기.ipynb

## Verification

| Check | Command |
|---|---|
| Notebook count | `find . -name "*.ipynb" | wc -l` |

## Operational Notes

- Some notebooks may assume older environments or local paths.
- Keras/TensorFlow versions can affect execution behavior, so record the environment when reproducing results.
- A useful next cleanup step would be adding `requirements.txt` or `environment.yml` to pin the lecture environment.

## Documentation Sources

This README was written from the following files and documents in this repository.

- `1강 코드.ipynb`
- `과제 1 코드.ipynb`
- `과제2 코드.ipynb`
- `와인 종류 예측하기.ipynb`
- `data-master/`

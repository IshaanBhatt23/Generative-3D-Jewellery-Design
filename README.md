# Generative 3D Jewellery Design from 2D Images

This project enables users to generate 3D models of jewellery from 2D images using OpenAI's Point-E model. The output is a downloadable `.obj` mesh file suitable for visualization and 3D printing.

---

## Overview

- **Input**: A 2D image of jewellery (PNG, JPG).
- **Output**: A 3D mesh model in `.obj` format.
- **Framework**: Google Colab / Python
- **Model**: OpenAI's Point-E

---

## Features

- Uses OpenAI’s `Point-E` model for generating point clouds from images.
- Converts point clouds to 3D mesh using marching cubes.
- Saves the final 3D model as an `.obj` file.
- Fully executable in Google Colab or local environments with GPU support.

---

## Tools and Technologies

- [Point-E](https://github.com/openai/point-e)
- Trimesh
- NumPy
- Matplotlib
- PyTorch
- OpenCV
- Google Colab (recommended)

---

## Setup Instructions


1. **Install Dependencies**

```bash
pip install -r requirements.txt
```

2. **Run in Google Colab**

If using Colab, open the notebook and run all cells. Upload your 2D image when prompted.

---

## Output

- A `.obj` file containing the 3D mesh

---

## Notes

- Ensure GPU is enabled in Colab (`Runtime > Change runtime type > GPU`).
- Some dependencies may require restarting the runtime after installation.

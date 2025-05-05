# image-text-3-D_model
## Overview
This project demonstrates a simple prototype to convert:
- A photo (with background removed)
- Or a text prompt (e.g., "a small toy car")
into a basic 3D model (.obj).

## Requirements
Install using:
requirements.txt

## How to Run
1. Open `main.ipynb` in Google Colab or Jupyter.
2. Upload an image (.png/.jpg) when prompted.
3. The background will be removed, and a dummy 3D model will be generated.
4. For text input, a placeholder 3D model will be created.
5. The models are visualized and downloadable.

## My Approach
- Used `rembg` to remove background from image.
- Created a dummy 3D object using `trimesh`.
- Rendered it with `pyrender`.
- Used basic logic to support both image and text input paths.

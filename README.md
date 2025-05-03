# Signs-Vectorization-BIM
Vectorize high-contrast road sign images into DXF for BIM modeling using OpenCV and Python.

# Sign Face Vectorizer (DXF Export using OpenCV)

This project converts high-contrast road sign images into DXF vector files using OpenCV. The generated DXFs are suitable for BIM modeling workflows (Modeling in Navisworks).

---

## Features

- Uses OpenCV for image processing and contour detection
- Outputs DXF files using `ezdxf`
- Supports batch image processing
- Supports optional fine tuning the polylines in case of noisy output

---

## Input

- High-contrast PNG or JPG images of sign faces from a simple screenshot

---

## Output

- DXF files with vectorized contours
- Each contour is converted to a closed polyline

---

## Requirements

Install dependencies via pip:

```bash
pip install opencv-python-headless ezdxf matplotlib

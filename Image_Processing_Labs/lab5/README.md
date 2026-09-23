# Spatial Filtering (Lab 5)

A practical guide to spatial filtering techniques in digital image processing using Python, comparing **smoothing** and **sharpening (Unsharp Masking)** methods.

---

## 💡 Overview
Spatial filtering modifies pixel values based on their neighbors using a matrix kernel:
* **Low-Pass Filters:** Smooth images and reduce noise by dimming sharp details.
* **High-Pass Filters:** Enhance edges and sharpen image details.

---

## 🧪 Key Technique: Unsharp Masking
1. **Blur** the original image using Gaussian Blur.
2. **Subtract** the blurred image from the original to extract the detail mask.
3. **Add** the weighted mask back to the original image.

---

## 🛠 Tech Stack
* **Python** | OpenCV | NumPy | Matplotlib | scikit-image



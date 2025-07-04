# 🧠 Day 76 — Image Manipulation with NumPy (Beginner-Friendly, Medical-AI Inspired)

## 📅 Journey Milestone:
This project is part of my [100 Days of Data Science / AI / Python Learning Journey](#), and today I took a deep dive into image manipulation using nothing but NumPy and Matplotlib.

As a medical student learning AI, I wanted to understand how machines **see** images — and how that same logic applies to **X-rays, MRIs, and diagnostic scans**.

---

## 🚀 What I Learned

### ✅ Images Are Arrays:
- Every image is a matrix of numbers (pixels).
- A color image has shape `(Height, Width, 3)` → RGB channels.
- A grayscale image is a 2D array.

### 🧰 NumPy Skills Applied:
- `np.array()` → Converting images to arrays
- `.shape`, `.dtype` → Understanding dimensions & types
- `@` operator → Grayscale conversion via dot product
- `np.flipud()` → Flipping images vertically
- `np.rot90()` → Rotating images 90°, 180°, etc.
- `255 - array` → Inverting colors (solarization)
- `np.random.random()` → Simulating visual noise

### 🖼️ Matplotlib for Visualization:
- `plt.imshow()`, `cmap='gray'`, `.axis('off')`

---

## 🔬 Why This Matters in Medical AI

| Use Case              | How This Helps                              |
|------------------------|---------------------------------------------|
| X-ray preprocessing    | Grayscale, rotate, resize                   |
| Tumor detection AI     | Normalize, adjust brightness                |
| Retinal image analysis | Channel-wise image processing               |
| AI training (vision)   | Flip, rotate, add noise for data diversity  |

---

## 🧪 Project Features

- 📥 Load any image
- 🎨 Convert to grayscale using sRGB luminance weights
- 🔁 Flip vertically
- 🔄 Rotate 90° clockwise
- 🌑 Invert colors (negative)
- 📉 Simulate noise
- 💾 Save manipulated images to disk



## 📌 How to Run


# Install requirements
pip install matplotlib pillow numpy scipy
Then open the Jupyter notebook:


👨‍⚕️ About Me
Hi! I’m Faisal Zia, a medical student learning Data Science, AI, and Python from scratch.
I believe doctors of the future must understand how machines think and learn.
Join me on my journey toward building medical AI tools that save lives!

🔗 LinkedIn: https://www.linkedin.com/in/faisal-zia-dev/
🐦 X / Twitter: https://x.com/faisalziachap  

# AutoVision-Notebook-Generator

**Generate ready-to-download Jupyter notebooks for computer vision workflows—from image classification to advanced models like YOLO, SORA, and Transformers. No coding required.**

---

## 🚀 Features

- **Interactive Input Panel**: Configure tasks, models, preprocessing, datasets, training, evaluation, and integrations.  
- **Live Notebook Preview**: Right panel shows code/markdown snippets generated progressively.  
- **Per-Session Controls**: Generate or clear individual snippets.  
- **Global Controls**: Reset settings or clear all for the entire notebook.  
- **Pre-configured Defaults**: Lightweight stable defaults for popular models and tasks.  
- **Pre-trained & Custom Models**: Auto-handle model weights and preprocessing.  
- **Download Ready**: Generates `.ipynb` (default) or optional `.py` file.  
- **Extensible & Scalable**: Easily add new models, tasks, or preprocessing options.

---

## 🎯 Supported Tasks

- Image Classification  
- Object Detection  
- Segmentation  
- Pose Estimation  
- OCR  
- Video Processing  
- Multimodal Transformers  
- Diffusion / Generative Models  

---

## ⚙️ Installation

```bash
git clone https://github.com/YourUsername/AutoVision-Notebook-Generator.git
cd AutoVision-Notebook-Generator
pip install -r requirements.txt
````

*Optional:* If using JS frontend, install dependencies via:

```bash
npm install
```

---

## 🖥 Usage

1. Open `src/index.html` in a browser.
2. Configure your project using the **left input panel**.
3. Use **Generate** buttons to add snippets to the notebook preview.
4. Use **Clear** to remove individual snippets, or **Reset Settings / Clear All** for full reset.
5. Click **Download Notebook** to get your `.ipynb` file.

---

## 🗂 Repo Structure

```
src/
 ├─ index.html
 ├─ style.css
 ├─ app.js
 ├─ notebook_generator.py
 └─ templates/
     ├─ cell_templates.json
     └─ config_templates.json
assets/
examples/demo_notebooks/
tests/
docs/
```

---

## 📌 Contributing

* Fork the repo, create a feature branch, submit a pull request.
* Report issues for bugs or feature requests.

---

## 📄 License

MIT License

---

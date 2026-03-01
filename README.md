# NexusView 🚀

[![PyPI version](https://img.shields.io/pypi/v/NexusView.svg)](https://pypi.org/project/NexusView/)
[![Python versions](https://img.shields.io/pypi/pyversions/NexusView.svg)](https://pypi.org/project/NexusView/)
[![License](https://img.shields.io/pypi/l/NexusView.svg)](https://github.com/ajaygopireddy216/NexusView/blob/main/LICENSE)

**NexusView** is a lightweight Python library designed for Data Scientists and Jupyter Notebook users. It allows you to seamlessly render live websites and embed YouTube videos directly within your `.ipynb` environment (Jupyter Notebook, JupyterLab, Google Colab).

Stop switching tabs to read documentation or watch tutorials—view them right next to your code!

---

## ✨ Features

- **🌐 Website Rendering:** Render any HTTPS website directly in an output cell.
- **▶️ YouTube Integration:** intelligent parsing of YouTube URLs to embed the video player automatically.
- **📏 Customizable:** easily adjust width, height, and alignment of the viewport.
- **⚡ Lightweight:** Zero heavy dependencies; built on top of standard IPython display tools.

---

## 📦 Installation

You can install NexusView via pip:

```bash
pip install NexusViewAjayKumarReddy
```

```python
from NexusViewAjayKumarReddy.youtube import render_youtube_video

render_youtube_video("https://www.youtube.com/watch?v=h25pePMdoPA&t=712s")
```

```python
from NexusViewAjayKumarReddy.site import render_site

render_site("https://www.google.com")
```

# How to Install this package in Your System

```bash
conda create -n nexusview_env python=3.8 -y
```

```bash
conda activate nexusview_env
```

```bash
pip install -r requirements_dev.txt
```
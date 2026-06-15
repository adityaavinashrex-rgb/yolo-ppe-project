# YOLO PPE Project

A multi-tiered object detection pipeline designed to track Personal Protective Equipment (PPE) compliance across hazardous industrial sites. 

*Special thanks to the engineering team at **[Detect Technologies](https://detecttechnologies.com/)** for providing the foundational guidance and industry benchmarks that made this pipeline alignment possible.*

---

##  Project Architecture

This repository is split into two primary operational branches to optimize for both high-throughput cloud environments and lightweight edge-device deployment:

1. **Cloud Execution (Google Colab / GPU):** A fully-featured, high-resolution ($imgsz=480$) model leveraging cloud GPUs for deep training passes and rapid video streaming inference.
2. **Local Workstation (CPU Pipeline):** A lightweight, optimized smoke-test pipeline utilizing low-impact configurations ($imgsz=128$, `workers=0`) to allow data engineers to run automation scripts, process video tracking, and test workflows locally without cloud credits.

---

##  Performance, Metrics & Documentation

* **Model Analytics:** Detailed evaluation graphs, precision-recall curves, and training history logs are completely documented and tracked inside the `metrics` branch.
* **Knowledge Base:** For a complete breakdown of project definitions, design choices, data schemas, and technical constraints, please visit our **Project Wiki** or view the localized reports inside the directory files.

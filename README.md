# FloodVLM: Context-Aware Vehicle Detection

This project implements a VLM-augmented perception pipeline for detecting vehicles in flooded conditions, inspired by the research of Polin et al. (2025).

## 🚀 Features
* **VLM Reasoning:** Uses Llama 3.2 Vision / QwenVL for environmental context.
* **Dual Detectors:** Comparison between YOLOv10 and RF-DETR.
* **Flood Metrics:** Centimeter-level estimation based on vehicle anatomy.

## 📊 Comparison Results
| Model | Condition | mAP |
| :--- | :--- | :--- |
| YOLOv10 (Baseline) | Heavy Rain/Flood | 0.72 |
| **FloodVLM (Ours)** | **Heavy Rain/Flood** | **0.84** |

## 🛠️ Installation
```bash
pip install -r requirements.txt

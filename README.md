# Pneumonia Detection ML

**Quick:** Fine-tuned VGG16 for binary classification (Normal vs Pneumonia) using chest X-ray images (Colab project).

---

## Repo structure
- `notebooks/` – Colab notebooks (`train.ipynb`, `inference.ipynb`)
- `src/` – Python scripts (model building, preprocessing, utils)
- `reports/` – plots (confusion matrix, metrics)
- `models/` – info about model weights (we store large weights on Drive)
- `DATA_LINKS.md` – dataset & model download links
- `requirements.txt` – Python dependencies

---

## How to run (Colab)
1. Open `notebooks/inference.ipynb` in Colab (button below).  
2. Mount your Google Drive and download model weights into `/content/drive/MyDrive/ai_project/`.  
3. Run cells to load the model and try predictions.

**Open in Colab:**  
`https://colab.research.google.com/github/<your-username>/pneumonia-detection-ml/blob/main/notebooks/inference.ipynb`

---

## Results (summary)
- Model: VGG16 (transfer learning, ImageNet weights)  
- Test accuracy: **~89.4%** (see `reports/` for details)  

---

## Notes
- Dataset: Kaggle Chest X-Ray Pneumonia (don’t upload full dataset here). See `DATA_LINKS.md`.  
- Model weights are large — follow `models/README.md` to download them from Drive.

---

## Contact
Sadia — student (B.Tech). For issues or questions, open an issue here on GitHub.

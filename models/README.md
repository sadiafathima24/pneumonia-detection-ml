# Models

We keep trained model weights on Google Drive due to size.

Steps to use:
1. Download `best_vgg16.h5` from the Drive link in `DATA_LINKS.md`.
2. In Colab, mount Drive:
   from google.colab import drive
   drive.mount('/content/drive')
3. Place the file in `/content/drive/MyDrive/ai_project/`.
4. Load in Colab:
   from tensorflow.keras.models import load_model
   model = load_model('https://drive.google.com/file/d/13CG2YwKa6e6r-Tdbz4FcX1t0h2ofzUXI/view?usp=drive_link')

# HematoVision - Blood Cell Classifier

A web app built with Flask and TensorFlow to classify blood cell images into 4 types.

## 💻 How to Run Locally

1. Clone the repo
2. Add your `hemato_model.h5` inside the `model/` folder
3. Install requirements:
   ```
   pip install -r requirements.txt
   ```
4. Run:
   ```
   python app.py
   ```

## 🌍 Deploy on Render

1. Push this repo to GitHub
2. Go to https://render.com
3. New → Web Service → Connect your repo
4. Use:
   - Build Command: `pip install -r requirements.txt`
   - Start Command: `python app.py`

Enjoy your live HematoVision app!

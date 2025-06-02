# 🔍 FastAPI + Machine Learning + HTML Form

A simple API built with **FastAPI** to serve predictions from a Machine Learning model (Scikit-learn or Keras). It includes a basic HTML form to input data and display the model's prediction in a web interface.

## 🚀 Run the App

```bash
# Clone the repository
git clone https://github.com/your-username/your-repo.git
cd your-repo

# Create a virtual environment
python3 -m venv venv
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Start the FastAPI server
uvicorn main:app --host 0.0.0.0 --port 8000
```

## 🗂 Project Structure

```
.
├── main.py                # FastAPI app
├── model.pkl              # Trained ML model (Scikit-learn or Keras)
├── requirements.txt       # Project dependencies
└── templates/
    └── form.html          # HTML form for user input and prediction
```

## 🌐 Access the App

Once the server is running, open your browser and go to:

```
http://<your-public-IP>:8000
```

Use `localhost` if running locally.

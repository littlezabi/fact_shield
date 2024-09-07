# 📰 Fake News Detection with AI

Welcome to the **Fake News Detection** project! This project uses Artificial Intelligence to determine whether the news is real or fake. It combines a Flask backend, AI model, a React + TypeScript frontend, and MongoDB as the database.

## 🚀 Features

- **AI-Powered**: Detects if the news article is real or fake using machine learning models.
- **React & TypeScript**: A modern, responsive frontend built with the latest web technologies.
- **Flask Backend**: The AI model is loaded and served using Flask.
- **MongoDB**: All data is stored securely in MongoDB.

## 🛠️ Installation & Setup

Follow these steps to get the project up and running on your local machine.

### 1. Clone the Repository

```bash
git clone https://github.com/littlezabi/fact_shield.git
cd fact_shield
```
### 2. Backend Setup (Flask)

Navigate to the backend directory and install the necessary Python dependencies:
```bash
cd backend
pip install -r requirements.txt
```
Start the Flask server:
```bash
python app.py
```
### 3. Frontend Setup (React + TypeScript)
Navigate to the frontend directory, install the dependencies, and start the development server:
```bash
cd frontend
npm install
npm run dev
```
### 4. MongoDB Setup
Make sure you have MongoDB running locally or use a remote MongoDB cluster. Update the connection string in the backend configuration to point to your MongoDB instance.

### 📂 Project Structure
```bash
/fake-news-detection
├── /backend
│   ├── app.py          # Flask app entry point
│   └── model/          # AI model files
├── /web
│   ├── src/            # React components and frontend logic
│   └── public/         # Static assets
└── /database
    └── mongo_setup.js  # MongoDB setup script
```
### 📊 Technologies Used
- **Frontend**: React, TypeScript
- **Backend**: Flask (Python)
- **Database**: MongoDB

### 🏁 Running the Project
To start the entire project, follow these commands:
#### 1. Backend
```bash
cd backend
flask run
```
#### 2. Frontend
```bash
cd frontend
npm run dev
```
Now, visit the frontend on `http://localhost:3000` and the backend API on `http://localhost:5000`.

🤝 Contributing
Feel free to fork this repository, submit issues, or make pull requests to improve the project!

👨‍💻 Created by **littlezabi**

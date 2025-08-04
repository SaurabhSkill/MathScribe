# 📝 Handwritten MathScribe


---

## 🚀 Overview

This application can recognize and solve handwritten equations involving:

- Basic arithmetic: ➕ Addition, ➖ Subtraction, ✖️ Multiplication, ➗ Division  
- Algebraic expressions: Linear, Quadratic, Cubic, and higher-degree equations

It uses:
- **OCR (Optical Character Recognition)** for image preprocessing and character segmentation
- **CNN (Convolutional Neural Networks)** for handwritten character prediction

---

## 📷 Example Use Case

Upload an image containing a handwritten equation like:


The system will:
1. Predict the characters using CNN
2. Parse the equation
3. Solve and return the answer:  
> `x = 2`

---

## 🛠 Tech Stack

- **Frontend**: ReactJS  
- **Backend**: FastAPI  
- **AI/ML**: Python, OpenCV, TensorFlow, CNN  
- **OCR**: Custom preprocessing with OpenCV  
- **Deployment**: Docker-ready

---

## 📦 Installation

### 🔧 Manual Setup (Local)

1. **Clone the repository**
   ```bash
   git clone <repo-link>
   cd <repo-folder>

2. Install frontend dependencies
cd frontend
npm install

3. Start frontend
npm start

Open: http://localhost:3000

4. Install backend dependencies
In a new terminal:

cd ../api
pip install -r requirements.txt

(If requirements.txt is missing, install manually:)

pip install fastapi uvicorn python-multipart numpy opencv-python tensorflow

5. Start backend server

uvicorn app:app --port 8000 --reload
Open: http://localhost:8000

 Docker Setup (Optional)

  1. From the root folder, run:

 docker-compose up --build

 2. Access the application:

Frontend: http://localhost:3000

Backend API: http://localhost:8000


Contact <br>
📛 Developer: Saurabh Gupta<br>
💻 GitHub: github.com/SaurabhSkill<br>
📝 Linkedin : http://linkedin.com/in/saurabh-gupta-0902642a4






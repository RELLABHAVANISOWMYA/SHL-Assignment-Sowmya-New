![Screenshot 2025-04-05 214153](https://github.com/user-attachments/assets/bf94763e-debb-4ab5-bf7b-cd8d05bfc24b)![Screenshot 2025-04-05 214153](https://github.com/user-attachments/assets/21f5dde4-127b-4a27-9955-f5b8e7acc005)# 🔍 SHL Assessment Recommendation Engine

This is a **content-based recommendation system** built using Python and Flask that intelligently suggests SHL assessments based on user queries. It leverages the SHL product catalog and offers a simple web interface for seamless recommendations.

---

## 🧠 Project Objective

Hiring managers often face difficulties choosing the right assessments for job roles. This tool helps simplify the process by recommending relevant SHL assessments based on a natural language query or job description.

---

## ✨ Features

- 🔎 **Search for assessments** by typing a query (e.g., job role, skills, duration, type of test).
- 📋 Recommends top **relevant SHL Individual Test Solutions**.
- 🧾 Displays:
  - Assessment Name (linked to SHL catalog)
  - Remote Testing Support (Yes/No)
  - Adaptive/IRT Support (Yes/No)
  - Duration
  - Test Type
- 💻 Clean and minimal user interface built with HTML (no CSS frameworks).
  
---

## 🛠️ Tech Stack

| Component     | Technology         |
|---------------|--------------------|
| Language      | Python             |
| Web Framework | Flask              |
| ML & Data     | scikit-learn, pandas |
| Frontend      | HTML               |

---

## 🚀 How to Run Locally

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/RELLABHAVANISOWMYA/SHL-Assignment-Sowmya-New.git
cd SHL-Assignment-Sowmya-New
```

### 2️⃣ Set up a Virtual Environment

```bash
python -m venv venv
```

#### Activate the Environment

- **Windows:**
  ```bash
  venv\Scripts\activate
  ```

- **Mac/Linux:**
  ```bash
  source venv/bin/activate
  ```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Make Sure This File Exists

Ensure `shl_catalogue.csv` is in the root of the project. It contains the parsed assessment data.

### 5️⃣ Run the App

```bash
python -m app.app
```

### 6️⃣ Open in Browser

Visit [http://127.0.0.1:5000](http://127.0.0.1:5000) to use the application.

---

## 📸 Preview

### 🏠 Home Page  
![Homepage](assets/homepage.png)

### 📊 Results Page  
![Results](assets/results.png)

---

## 📬 Contact

Created by **Bhavani Sowmya Rella**  
📧 rellabhavanisowmya@gmail.com  
🔗 [GitHub](https://github.com/RELLABHAVANISOWMYA)

---

```

---




```bash
git add README.md
git commit -m "Added README file"
git push origin main
```

Would you like me to generate a sample `requirements.txt` for your setup too?

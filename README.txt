# 🧮 Python Basic Calculator

A simple **web-based calculator** built using **Flask (Python)** that performs basic arithmetic operations like addition, subtraction, multiplication, and division.
This project demonstrates the use of **Flask routing, templates, and form handling** to create an interactive web application.

---

## 🚀 Features

* Perform basic arithmetic operations:

  * ➕ Addition
  * ➖ Subtraction
  * ✖️ Multiplication
  * ➗ Division
* User-friendly web interface
* Input validation and error handling
* Lightweight and easy to deploy

---

## 🛠️ Tech Stack

* **Backend:** Flask (Python)
* **Frontend:** HTML, CSS (Bootstrap or custom)
* **Language:** Python 3.x

---

## 📦 Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/Astitva13/Python-Basic-Calculator.git
cd Python-Basic-Calculator
```

### 2. Create and activate a virtual environment (optional but recommended)

```bash
python -m venv venv
source venv/bin/activate       # For macOS/Linux
venv\Scripts\activate          # For Windows
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

> If you don’t have a `requirements.txt`, you can manually install Flask:

```bash
pip install flask
```

### 4. Run the Flask app

```bash
python app.py
```

### 5. Open in your browser

Visit 👉 [http://127.0.0.1:5000/](http://127.0.0.1:5000/) to access the calculator.

---

## 🧩 Project Structure

```
flask-calculator/
│
├── app.py                # Main Flask app
├── templates/
│   └── index.html        # Frontend HTML form and result display
├── requirements.txt      # Dependencies
└── README.md             # Project documentation
```

---

## 💡 How It Works

1. User enters two numbers and selects an operation.
2. Flask receives the data via POST request.
3. The server performs the selected operation.
4. The result is displayed back on the webpage.

---

## ⚠️ Error Handling

* Division by zero is handled gracefully.
* Invalid or missing inputs are validated before computation.

---

## 🧠 Example

**Input:**

* First Number: 10
* Second Number: 5
* Operation: Divide

**Output:**

> Result: 2.0 ✅

---

## 🧰 Future Enhancements

* Add support for advanced operations (square root, power, modulus, etc.)
* Implement a history of previous calculations
* Add user authentication for personalized usage
* Deploy on platforms like **Render**, **Vercel**, or **Heroku**

---

## 👨‍💻 Author

**Astitva Mishra**
📧 [astitvamishra13@gmail.com]
🔗 [GitHub Profile](https://github.com/Astitva13)

---

## 📄 License

This project is licensed under the **MIT License** – feel free to use and modify it.


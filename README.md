# 🍎 Calorie & Nutrient Tracker

A **simple web-based calorie and nutrient tracker** built with the **Django** framework.
Users can log their daily food intake, monitor **macronutrient distribution** (carbs, protein, fats), and track their progress toward a **calorie goal**.

---

## ✨ Features

* **Food Logging** – Select and add food items to your daily log.
* **Daily Breakdown** – View carbs, protein, fats, and calories for all consumed food items.
* **Automatic Totals** – Nutrients and calories are summed up in real-time.
* **Macronutrient Distribution** – Donut chart visualization using **Chart.js**.
* **Calorie Goal Progress** – Progress bar toward a predefined goal (**2000 kcal**).
* **Food Item Removal** – Delete any logged food item easily.

---

## 🖼 Screenshots & Demo

**Main Interface**
<img width="1916" height="948" alt="image" src="https://github.com/user-attachments/assets/7ee0d350-4069-4033-bf26-c2a0ec7d6d8a" />

---

## 🛠 Technologies Used

**Backend:** Django (v5.2.5)
**Database:** SQLite3
**Frontend:** HTML, CSS, JavaScript, Bootstrap (v4.0.0), Chart.js

---

## 📂 Project Structure

```
mysite/
│── manage.py
│── mysite/
│   ├── settings.py      # Project settings
│   ├── urls.py          # Main URL configuration
│── myapp/
│   ├── models.py        # Food & Consume models
│   ├── views.py         # Application logic
│   ├── urls.py          # App-specific URL routes
│   ├── templates/myapp/
│       ├── index.html   # Main tracker interface
│       ├── delete.html  # Delete confirmation page
```

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/imsaqib04/nutrient-calorietracker.git
cd nutrient-calorietracker/mysite
```

### 2️⃣ Install Dependencies

```bash
pip install Django
```

### 3️⃣ Run Migrations

```bash
python manage.py makemigrations myapp
python manage.py migrate
```

### 4️⃣ Create a Superuser

```bash
python manage.py createsuperuser
```

### 5️⃣ Start the Development Server

```bash
python manage.py runserver
```

---

## 📌 Usage

* Access the app: **[http://127.0.0.1:8000/](http://127.0.0.1:8000/)**
* Admin panel: **[http://127.0.0.1:8000/admin/](http://127.0.0.1:8000/admin/)** (add food items to the database)
* The **index page** will display the tracker interface.

---

## 📜 License

This project is licensed under the **MIT License**.

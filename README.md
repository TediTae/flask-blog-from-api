# Simple Flask Blog

A minimal blog web application built with Flask and Requests.  
This project fetches blog post data from a public JSON API and renders them on dynamic HTML pages using Jinja2 templating.

---

## 🚀 Features

- Home page displaying all blog posts
- Dynamic post detail pages
- External API integration using `requests`
- Clean and beginner-friendly Flask structure (no database, no class-based views)

---

## 🛠️ Technologies Used

- Python 3.x
- Flask
- Jinja2
- Requests
- HTML5 (templates)

---

## 📦 Installation

1. Clone the repository:

```bash
git clone https://github.com/TediTae/flask-blog-from-api.git
cd flask-blog-from-api
```
2. (Optional but recommended) Create a virtual environment:
    - python -m venv venv
    - source venv/bin/activate  # On Windows: venv\Scripts\activate

3. Install the dependencies:
   - requests
   - flask

---

## 📁 Project Structure
flask-blog-from-api/
├── app.py
├── requirements.txt
├── static/
│   └── style.css
└── templates/
    ├── index.html
    └── post.html

---

## 🌐 API Source
- Blog data is fetched from this public JSON endpoint:
- 📎 https://api.npoint.io/7b983f7605c621e43e8b
- You can replace it with your own API or local JSON file if needed.

---

## 🧠 Why This Project?
This project is perfect for:
  - Beginners learning Flask routing and templating
  - Developers practicing API consumption with Python
  - Anyone building small prototype blog applications without a database

---

## 📄 License
This project is open source under the MIT License.

---

## 🙏 Acknowledgments

This project is based on and inspired by Angela Yu's **100 Days of Code: The Complete Python Pro Bootcamp** course.  
Special thanks to Angela Yu for the excellent teaching resources.

---

## 📬 Contact
If you have any questions, feedback, or suggestions, feel free to reach out:
- Email: tolgayilmaz1377@gmail.com


# 🔥 ISANEX Framework

**Isanex** is a modern, lightweight PHP framework built from scratch with clarity, power, and simplicity in mind. It follows the **MVC architecture**, leverages **SOLID principles**, and is designed to help developers deeply understand the fundamentals of backend development with PHP.

> _“Isanex is the great symbol that means greatness, power, and clean code.”_

---

## 🧩 Features

- 🚀 Minimalist & Fast Core
- 🧱 MVC Architecture (Model-View-Controller)
- 💡 Clean OOP Structure
- 🧭 Simple & Extendable Routing System
- 🔐 Configurable & Secure
- 🔄 Built-in Autoloading (PSR-4)
- 🛠️ Designed for Learning & Mastery

---

## 📂 Project Structure

isanex/
├── public/ # Entry point (index.php)
├── app/
│ ├── Controllers/ # Controllers
│ ├── Models/ # Models
│ ├── Views/ # Views (PHP or templated)
│ └── Core/ # Core framework logic
├── config/ # Configuration files
├── routes/ # Route definitions
├── storage/ # Logs, cache, etc.
├── vendor/ # Composer packages
├── .env # Environment settings
└── composer.json # Autoload + dependencies

yaml
Copy
Edit

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/isabekoviskandar/isanex.git
cd isanex
2. Install Dependencies
bash
Copy
Edit
composer install
3. Set Up Your Environment
Copy .env.example to .env and configure your settings (e.g., database, app mode).

bash
Copy
Edit
cp .env.example .env
4. Run the App
bash
Copy
Edit
php -S localhost:8000
Visit http://localhost:8000 in your browser.

⚙️ Routing Example
php
Copy
Edit
// routes/web.php

$router->get('/', 'HomeController@index');
$router->post('/login', 'AuthController@login');
✨ Philosophy
Isanex is for those who:

Want to master the fundamentals of MVC

Want to understand what happens “under the hood”

Believe in clarity over complexity

Enjoy writing clean, maintainable, SOLID code

🧠 Learn From the Code
Every component is designed to be readable and learnable. No magic. You’ll understand how everything works — from routing to rendering.

🔒 License
MIT License. Use it freely, modify it, fork it, learn from it.

📛 Logo
The Isanex logo symbolizes greatness and power — a flame of creativity and a sharp blade of precision.

🤝 Contribute
Want to improve Isanex or learn while building it?

Fork it

Build something cool

Submit a pull request

Made with 🔥 by Iskandar

yaml
Copy
Edit

---

Let me know if you want a dark version of the logo, or if you’d like me to help generate the actual `index.php`, router class, or other starter files next.








Ask ChatGPT

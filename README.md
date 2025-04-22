<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Expense Tracker - Django App</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      margin: 0;
      padding: 0;
      background-color: #f7f7f7;
      color: #333;
    }
    .container {
      width: 90%;
      max-width: 900px;
      margin: 40px auto;
      padding: 20px;
      background-color: white;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
    }
    h1, h2 {
      color: #007BFF;
    }
    pre {
      background: #eee;
      padding: 1em;
      overflow-x: auto;
      border-radius: 6px;
    }
    code {
      background: #eee;
      padding: 2px 4px;
      border-radius: 4px;
    }
    img {
      max-width: 100%;
      border-radius: 8px;
      margin: 10px 0;
    }
    table {
      width: 100%;
      border-collapse: collapse;
      margin: 1em 0;
    }
    table, th, td {
      border: 1px solid #ddd;
    }
    th, td {
      padding: 10px;
      text-align: left;
    }
    a {
      color: #007BFF;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
    hr {
      border: 1px solid #ddd;
      margin: 2em 0;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>💸 Expense Tracker - Django Web Application</h1>
    <p>
      A web-based Expense Tracker built with <strong>Django</strong>. This project allows users to track income, expenses, and member balances in an organized and user-friendly way.
    </p>

    <h2>📸 Screenshots</h2>
    <p><em>Add your screenshots here (e.g. dashboard, add expense form, etc.)</em></p>
    <img src="screenshots/dashboard.png" alt="Dashboard Screenshot">
    <img src="screenshots/add_expense.png" alt="Add Expense Screenshot">

    <h2>🚀 Features</h2>
    <ul>
      <li>👥 Manage multiple members</li>
      <li>💰 Record earnings</li>
      <li>🧾 Track categorized expenses</li>
      <li>⚖️ Auto-calculate balances</li>
      <li>📊 Income vs Expense summary</li>
      <li>🔐 Django-admin backend</li>
      <li>🌐 Responsive and clean UI</li>
    </ul>

    <h2>🏗️ Tech Stack</h2>
    <table>
      <thead>
        <tr>
          <th>Layer</th>
          <th>Technology</th>
        </tr>
      </thead>
      <tbody>
        <tr><td>Framework</td><td>Django (Python)</td></tr>
        <tr><td>Frontend</td><td>HTML, CSS</td></tr>
        <tr><td>Database</td><td>SQLite</td></tr>
        <tr><td>Templating</td><td>Django Templates</td></tr>
      </tbody>
    </table>

    <h2>📂 Project Structure</h2>
    <pre><code>
ExpenseTrackernew/
├── ExpenseTracker/
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── home/
│   ├── migrations/
│   ├── templates/
│   ├── static/
│   ├── models.py
│   ├── views.py
│   └── urls.py
├── db.sqlite3
├── manage.py
└── requirements.txt
    </code></pre>

    <h2>🛠️ Getting Started</h2>
    <h3>Requirements</h3>
    <ul>
      <li>Python 3.7+</li>
      <li>pip (Python package installer)</li>
      <li>Virtual environment (recommended)</li>
    </ul>

    <h3>Installation</h3>
    <pre><code>
git clone https://github.com/anujrathore073/ExpenseTrackernew.git
cd ExpenseTrackernew

# Optional: Create and activate virtual environment
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run migrations
python manage.py migrate

# Start the server
python manage.py runserver
    </code></pre>

    <p>Now open <a href="http://localhost:8000" target="_blank">http://localhost:8000</a> in your browser.</p>

    <h2>🧠 How It Works</h2>
    <ul>
      <li>Django handles all backend logic and routing</li>
      <li>All data is saved in a local SQLite database</li>
      <li>HTML templates are dynamically rendered using Django</li>
      <li>Views and models handle business logic and data persistence</li>
    </ul>

    <h2>📜 License</h2>
    <p>This project is licensed under the <strong>MIT License</strong>. See <code>LICENSE</code> file for details.</p>

    <h2>👤 Author</h2>
    <p>
      <strong>Anuj Rathore</strong><br/>
      🔗 <a href="https://github.com/anujrathore073" target="_blank">GitHub Profile</a>
    </p>

    <h2>🤝 Contributing</h2>
    <p>
      Contributions are welcome! Feel free to fork the repo and submit a pull request.<br/>
      Also feel free to report bugs or request features via GitHub Issues.
    </p>

    <hr />
    <p align="center">⭐ If you like this project, don't forget to star it on GitHub!</p>
  </div>
</body>
</html>

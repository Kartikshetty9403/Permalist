#📝 Permalist — A Modern To-Do List Web App

Permalist is a clean, fast, and database-driven To-Do application built using Node.js, Express, EJS, and PostgreSQL.
It lets users create, edit, and delete checklist items with a smooth and minimal interface.

This project focuses on simplicity, clean backend structure, and secure environment variable usage.

🚀 Features

✔️ Add new tasks easily

✏️ Edit tasks inline

❌ Delete tasks instantly

📄 Clean checklist UI

🗄️ PostgreSQL-powered persistent storage

⚡ Fast Express.js backend

🧩 EJS templating for dynamic pages

🔐 Secure .env configuration (DB credentials hidden)

🛠️ Tech Stack

Frontend

HTML5

CSS3

EJS Templates

Backend

Node.js

Express.js

Body-Parser

Database

PostgreSQL

pg Node client

--------------------------------------------------------------------------------------------------

⚙️ Installation & Setup

Follow these steps to run the project locally:

1️⃣ Clone the repository
git clone https://github.com/YOUR-USERNAME/Permalist.git
cd Permalist

2️⃣ Install dependencies
npm install

3️⃣ Create a PostgreSQL database

Create a database named:

Permalist


Inside it, create a table:

CREATE TABLE items (
    id SERIAL PRIMARY KEY,
    title VARCHAR(255)
);

4️⃣ Create your .env file

Inside the project root:

DB_USER=postgres
DB_HOST=localhost
DB_DATABASE=Permalist
DB_PASSWORD=YOUR_PASSWORD
DB_PORT=5432

5️⃣ Start the server
node index.js


Now open the app in your browser:

http://localhost:3000

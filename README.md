To ensure your Flask application runs correctly (both on your computer and when you upload it to the web), you must follow a specific directory structure. Flask looks for files in specific folders by default.

Here is exactly how you should organize your files:

The Structure Tree
Create a main folder (e.g., named acting_site) and arrange your files inside it exactly like this:

Plaintext

acting_site/
│
├── app.py                <-- Your main Python file 
│
├── static/               <-- FOLDER for CSS, Images, JS
│   ├── style.css         <-- Your CSS file 
│   └── logo.png          <-- Your logo image
│
└── templates/            <-- FOLDER for all HTML files
    ├── base.html         <-- The master layout 
    ├── index.html        <-- Home page 
    ├── about.html        <-- About page 
    ├── opportunities.html <-- Opportunities page 
    └── contact.html      <-- Contact page

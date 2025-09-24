SDG 4: Quality Education Web App

This is a mobile-friendly web application built with HTML, CSS, and JavaScript to support SDG 4: Quality Education.
It aims to provide access to free learning resources, track study progress, share community insights, and inspire daily learning — all within a simple, lightweight, and responsive interface.

🎯 Goal

SDG 4 (Sustainable Development Goal 4) focuses on:

"Ensuring inclusive and equitable quality education and promoting lifelong learning opportunities for all."

This app demonstrates how technology can promote education through free resources, community collaboration, and interactive tools.

✨ Features
🔐 Authentication

Login and signup forms (email + password)

Basic form validation

Data stored locally using localStorage (no backend required)

🏠 Homepage

Displays SDG 4 title, logo, and description

Responsive hero section with inspirational design

📚 Learning Resources

Categorized into Literacy, STEM, Digital Skills, Vocational Training

Each category links to trusted platforms (Khan Academy, Coursera, UNESCO, freeCodeCamp, etc.)

Cards enhanced with images/icons for better interactivity

💡 Daily Knowledge Bite

Displays a new inspiring fact, quote, or learning challenge each day

Automatically rotates through preloaded quotes

📝 Study Tracker

Users can log study sessions or skills

Saves progress locally with streaks and badges

Visual badges motivate consistent learning

🌍 Community Section

Users can post tips, notes, or book recommendations

Posts are stored and displayed locally (via localStorage)

Encourages peer-to-peer sharing

🎨 Design

Clean red-and-white theme (inspired by SDG 4 branding)

Glassmorphism-style cards and sections

Fully responsive design (mobile-first approach)

🛠️ Tech Stack

HTML5 – Structure

CSS3 – Styling and responsiveness

Vanilla JavaScript (ES6+) – Logic, interactivity, and local storage

No frameworks required (lightweight and portable)

📂 Project Structure
sdg4-education-app/
│
├── index.html        # Main HTML file
├── style.css         # CSS for styling
├── script.js         # JavaScript for app logic
├── README.md         # Documentation
└── assets/           # (optional) Images/icons for resources

🚀 Getting Started
1️⃣ Download or Clone the Project
git clone https://github.com/your-username/sdg4-education-app.git

Or download the .zip file and extract it.

2️⃣ Open in Browser

Simply open index.html in your preferred browser (Chrome, Edge, Firefox, etc.).
No server setup is required.

📱 Mobile Friendly

The app is designed to adapt seamlessly between desktop and mobile screens.
Features like the mobile navigation menu and stacked layout ensure usability across devices.

🔒 Limitations

Authentication is local only (no real backend or encryption).

Posts, study logs, and user accounts are stored in localStorage (cleared if the browser storage is reset).

Not suitable for production use without a backend.

🌟 Future Improvements

Connect authentication to a backend (Firebase, Supabase, etc.)

Add progress visualization with charts

Enable file/image uploads in community posts

Expand multilingual support

Deploy online via GitHub Pages, Netlify, or Vercel

🤝 Contribution

Want to improve this project?

Fork the repo

Create a new branch (feature-new)

Commit your changes

Submit a Pull Request

📜 License

This project is open-source and available under the MIT License.

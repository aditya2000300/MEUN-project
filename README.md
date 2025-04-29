🧹 MEUN - Meet Everything U Need
Welcome to MEUN, a modern web platform that connects users with reliable Indian workers such as maids, drivers, cooks, security guards, cleaners, and caretakers. Designed for simplicity and usability, MEUN offers real-time booking, interactive features, and secure payments—all in one place.

📌 Table of Contents
🚀 Project Overview

✨ Features

🛠️ Setup and Installation

📦 Dependencies

⚙️ Configuration

💻 Running the Project

🗃️ Database and APIs

🤝 Contributing

📄 License

🚀 Project Overview
MEUN is a React-based web application built to simplify the hiring process for household and professional services. With a responsive design, animations, and seamless user experience, MEUN leverages modern web technologies to deliver a functional and attractive platform.

✨ Features
🔐 User Authentication – Signup and login with secure credentials

📆 Worker Booking – Browse and book workers via a secure Razorpay payment system

🟢 Live Availability – Real-time status updates for worker availability

🗺️ Interactive Map – Displays cities served using Leaflet.js

💬 FAQ & Testimonials – Informative and animated user feedback sections

🌙 Dark Mode – Toggle between light and dark themes

🤖 Chatbot Support – Integrated with Botpress for automated assistance

🛠️ Setup and Installation
Follow these steps to set up and run the MEUN project locally:

1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/aditya2000300/MEUN-project.git
cd MEUN-project
2. Install Dependencies
bash
Copy
Edit
npm install
3. Configure Environment Variables
Create a .env file in the root directory and add:

env
Copy
Edit
REACT_APP_RAZORPAY_KEY=your_razorpay_api_key
REACT_APP_BOTPRESS_BOT_ID=your_bot_id
REACT_APP_BOTPRESS_CONFIG_URL=https://your-botpress-config-url
⚠️ Make sure to replace the placeholders with your actual API keys.

📦 Dependencies
MEUN uses the following major libraries and tools:


Library	Purpose
React ^19.0.0	Frontend framework
React Router DOM ^7.4.0	Routing
Framer Motion ^12.5.0	Animations
GSAP ^3.12.7	Advanced animations
Leaflet ^1.9.4 + React Leaflet ^5.0.0	Maps
Slick Carousel ^1.8.1	Sliders
FontAwesome	Icons
Tailwind CSS	Styling
Razorpay	Payment gateway
Botpress	AI-powered chatbot
Install all dependencies using:

bash
Copy
Edit
npm install
⚙️ Configuration
Tailwind CSS: Pre-configured via tailwind.config.js

ESLint: Configured via eslint.config.js

Browser Compatibility: Supports all modern browsers (configured in package.json)

💻 Running the Project
Start the Frontend Server:
bash
Copy
Edit
cd client
npm start
Navigate to http://localhost:3000 to view the application.

(Optional) Start the Backend Server:
bash
Copy
Edit
cd client
npm run dev
This will run the server on http://localhost:5000.

🗃️ Database and APIs
📂 Database (Optional for Production)
Currently, the project uses mock data like featuredWorkers and testimonials. For a production setup:

Use MongoDB or Firebase to store:

User details

Worker profiles

Booking data

Update API endpoints accordingly

🔌 APIs Used
Razorpay – For payment integration

Botpress – For chatbot interaction

Document your API keys and endpoints in .env or maintain a separate API.md.

🤝 Contributing
We welcome contributions! Here's how to contribute:

Fork the repository

Create your feature branch:

bash
Copy
Edit
git checkout -b feature-branch
Commit your changes:

bash
Copy
Edit
git commit -m "Add new feature"
Push to your branch:

bash
Copy
Edit
git push origin feature-branch
Open a Pull Request

📄 License
This project is licensed under the MIT License.
See the LICENSE file for more details.

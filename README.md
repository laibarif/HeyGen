# 🎥 HeyGen Streaming Avatar Demo

This is a web-based demo project developed for **HeyGen** to demonstrate streaming avatar functionality. The application includes a **Student Verification** interface that redirects users to a streaming avatar interface after input validation.

---

## 📁 Project Structure
```
streaming-avatar-demo/
│
├── dist/ # Compiled output (if applicable)
├── node_modules/ # Node.js dependencies
├── public/ # Public assets
├── src/ # Source code files (e.g., TypeScript, components)
├── .env # Environment variables
├── .env_example # Template for .env file
├── .gitignore # Git ignored files
├── avatar.html # Avatar rendering UI
├── index.html # Student verification UI
├── package.json # Project metadata and dependencies
├── package-lock.json # Exact dependency versions
└── tsconfig.json # TypeScript configuration
```

## 🚀 Features

- 🎓 **Student Verification Page**  
  Simple form to input student ID with Tailwind CSS styling. Redirects users to the avatar page.

- 🧑‍💻 **Streaming Avatar Page (`avatar.html`)**  
  Displays avatar streaming content with query string-based routing.

- 💾 **Session Storage**  
  Student ID and avatar preferences are saved using `sessionStorage`.

- 🎨 **Responsive UI**  
  Tailwind CSS-based responsive and interactive design.

## 🔧 Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/streaming-avatar-demo.git
cd streaming-avatar-demo
```

### 2. Install Dependencies
Make sure you have Node.js installed. Then run:
```
npm install
```
### 3. Setup Environment Variables
Create a .env file based on .env_example.

### 4. Run Locally
Use a local server (like Live Server extension in VSCode or any static server).
```
npx serve 
```
Or use:
```
npm start

```
🧪 Technologies Used
```
HTML5

Tailwind CSS

JavaScript

TypeScript (configured via tsconfig.json)

Node.js (for dependency management)
```

🌐 Deployment
This project is ready to be hosted on platforms like Vercel, Netlify, or GitHub Pages for demonstration purposes.

📄 License
This project is for internal and demo use by Neksogix and HeyGen. Not for public distribution.

🤝 Acknowledgements
Developed as part of the Neksogix Internship Program for client project integration with HeyGen avatar streaming technology.

Let me know if you'd like to include preview screenshots, instructions for a specific build process (like Webpack/Vite), or if this will be part of a larger system.

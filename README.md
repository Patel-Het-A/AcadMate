# 📚 AcadMate

**AcadMate** is a centralized academic resource platform designed to streamline access to categorized **study materials** and **previous year papers** for students. Admins can securely upload files using OneDrive integration, while users can browse, view, and save materials organized by category, branch, and subject.

🌐 **Live Demo:** [https://acadmate-vx8s.onrender.com](https://acadmate-vx8s.onrender.com)

## 🚀 Features

* 📂 **Hierarchical Material Organization**: Browse materials by type (Study Materials, PYQs), branch, and subject.
* ☁️ **OneDrive Integration**: Admins can upload and manage files using Microsoft Graph API (OAuth with PKCE).
* 👨‍🏫 **Admin Panel**: Upload PDFs, DOCX, PPTs, and images with metadata.
* 💾 **Save to Profile**: Users can save individual files to their profile for quick access.
* 🔒 **Secure Auth**: JWT-based authentication system for admins and users.

## 🛠️ Tech Stack

* **Frontend**: React.js, Tailwind CSS, Redux
* **Backend**: Node.js, Express.js, MongoDB
* **File Storage**: Microsoft OneDrive via Graph API
* **Authentication**: JWT (JSON Web Tokens), OAuth 2.0 PKCE (OneDrive)
* **Deployment**: Render

## 📦 Installation (Local Setup)

```bash
# Clone the repository
git clone https://github.com/yourusername/acadmate.git
cd acadmate

# Install backend dependencies
cd sbackend
npm install

# Install frontend dependencies
cd ../frontend
npm install

# Run both frontend and backend (use concurrently or separate terminals)
npm run start
```
---





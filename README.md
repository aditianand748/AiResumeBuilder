## Resume Builder
- A simple and intuitive web application that helps users create a new resume or improve an existing one.
Designed to speed up the resume creation process with structured templates and helpful suggestions.

## Live Preview
<a href="https://reusme-builder.vercel.app/" target="_blank">resume builder</a>

## Tech Stack & Tools
Frontend (React, Tailwind, prebuiltUI) 
<br/>
Backend (Node.js, Express.js)
<br/>
Database (MongoDB)
<br/>
Authentication (JWT, OAuth)
<br/>
AI: Gemini 
<br/>
Images: ImageKit for background removal & face focus

# ✅ Features:
## 🧱 Resume Creation
- Build resumes from scratch using guided inputs.
- Structured fields (Personal Info, Experience, Education, Skills, etc.).

## 🛠️ Resume Enhancement
- Improve existing resumes via content optimization.
- Clean formatting & structured output.

## 🤖 AI Enhancements
- Enhances professional summaries for clarity & tone.
- Optimizes job descriptions with strong action verbs & measurable achievements.
- Keeps content consistent and professional without changing meaning.

## 🖼️ Image Handling
- Add a profile picture to resume.
- Remove background & auto-focus on face using ImageKit.

## 🎨 Accent Color
- Customize heading accent colors.
- Set background color behind profile picture.

## 💾 Saving & Exporting
- Manual save.
- Export to PDF or Docx (based on implementation).

## 🔐 Public / Private Resume Modes
- Public: Share resumes via a unique link.
- Private: No share link — stays hidden.

## 👤 Authentication
- Users can log in and log out to securely manage resumes.

## 📱 Responsive UI
- Fully responsive for desktop, tablet, and mobile.


# 🧩 Usage Flow
- signup or login
- Choose Create Resume or Upload Existing.
- Enter details or upload an existing resume.
- (Optional) upload photo → remove background → apply color.
- Use AI to enhance summaries & job roles.
- Select template and customize colors.
- Choose Public or Private visibility and download button.
- Manually Save your resume.
- Export to PDF/Docx if needed.

## ⚙️ Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/aditianand748/AiResumeBuilder.git
cd AiResumeBuilder
```

### 2. Backend Setup
```bash
cd server
npm install
npm run dev
```

Create a `.env` file in the `server` directory:
```env
PORT=3000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
IMAGEKIT_PUBLIC_KEY=your_imagekit_public_key
IMAGEKIT_PRIVATE_KEY=your_imagekit_private_key
IMAGEKIT_URL_ENDPOINT=your_imagekit_url_endpoint
GEMINI_API_KEY=your_gemini_api_key
```

### 3. Frontend Setup
```bash
cd ../client
npm install
npm run dev
```

Create a `.env` file in the `client` directory:
```env
VITE_BASE_URL=http://localhost:3000
```

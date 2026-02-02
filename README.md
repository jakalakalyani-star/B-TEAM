# ResumeAI - Resume Screening & Scoring Tool

ResumeAI is a premium, full-featured web application designed to help recruiters and job seekers evaluate resume relevance against specific job roles.

## 🚀 Features

- **Premium Interface**: A modern, glassmorphism-inspired dark mode UI.
- **Smart Scoring**: Uses advanced keyword matching to generate a relevance score (0-100%).
- **PDF Support**: Directly upload PDF resumes for automatic text extraction using `pdf.js`.
- **Keyword Analysis**: Highlights matched and missing keywords for better optimization.
- **Authentication System**: Secure login and registration flow with session persistence.
- **Stateless & Portable**: Pure HTML/CSS/JS architecture—no server installation or Node.js required.

## 🛠️ Project Structure

```text
kprs/
├── index.html          # Main application dashboard
├── login.html          # Secure login portal
├── register.html       # Account registration page
├── assets/
│   ├── css/
│   │   └── style.css   # Premium glassmorphism styles
│   └── js/
│       ├── app.js      # Main UI & Event controller
│       ├── auth.js     # User authentication logic
│       └── backend.js  # Scoring algorithm & static data
```

## 🏁 Getting Started

### Prerequisites
- Any modern web browser (Chrome, Edge, Firefox, Brave).

### Installation
1. Download or clone this project folder to your local machine.
2. Navigate to the project root directory.

### Running the Tool
1. Double-click `login.html` to start the application.
2. **Login Credentials**:
   - Default Admin: `admin` / `admin`
   - Or create your own account using the **Sign Up** page.

## 📖 How to Use

1. **Login**: Enter your credentials to access the tool.
2. **Select Role**: Choose a target job role from the dropdown (e.g., Frontend Developer).
3. **Input Resume**:
   - **Upload**: Click the PDF upload button to auto-extract text.
   - **Paste**: Directly paste resume text into the text area.
4. **Analyze**: Click "Analyze Relevance" to generate your score.
5. **Review**: Examine the matched/missing keywords to see how to improve the resume.

## ⚙️ Technologies Used

- **HTML5**: Semantic structure.
- **CSS3**: Custom variables, Glassmorphism, and responsive grid layouts.
- **JavaScript (ES6+)**: Core logic and DOM manipulation.
- **PDF.js**: Mozilla's open-source PDF parsing library.
- **LocalStorage**: Browser-based data persistence for users and sessions.

## 📄 License
MIT License - Feel free to use and modify for your own projects.

# AI-Powered-Resume-and-Cover-Letter-Generator

✨ AI-Powered Cover Letter & Resume Generator 📝
<p align="center">
<img src="https://img.shields.io/badge/Python-3.9%2B-blue?style=for-the-badge&logo=python" alt="Python Version">
<img src="https://img.shields.io/badge/Framework-Gradio-orange?style=for-the-badge" alt="Framework">
<img src="https://img.shields.io/badge/AI%20Engine-Gemini%20Pro-purple?style=for-the-badge" alt="AI Engine">
<img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="License">
</p>

<p align="center">
Tired of writing resumes and cover letters from scratch? This project uses the power of Google's Gemini AI to automatically generate professional, tailored application documents for you in seconds!
</p>

✅ Core Features
🤖 AI-Powered Content: Leverages Google's Gemini Pro to write compelling summaries, professional bullet points, and persuasive cover letters.

📄 Dual Generators: Includes two powerful modules in one app:

Resume Generator: Builds a complete resume from your structured information.

Cover Letter Generator: Creates a tailored letter by analyzing your resume against a specific job description.

🎨 Context-Aware & Tailored: The cover letter generator intelligently pulls relevant skills from your resume to match the job you're applying for.

📤 Multiple Formats: Download your final documents as both a professional PDF and an editable TXT file.

🌐 Interactive Web UI: A clean, user-friendly interface powered by Gradio makes the entire process intuitive and easy.

☁️ Colab Ready: Designed to run seamlessly in a free Google Colab notebook—no local installation required!

🛠️ Technology Stack
Core Language: 🐍 Python

AI Engine: 🧠 Google Gemini Pro (via langchain_google_genai)

Web UI: 🎨 Gradio

PDF Handling: 📄 PyPDF2 (for reading) & fpdf2 (for writing)

Environment: ☁️ Google Colab

🚀 Getting Started in 3 Easy Steps
You can run this entire application for free in your browser using Google Colab.

Step 1: Open a Google Colab Notebook
Click here to open a new, empty Colab notebook.

Step 2: Set Your Google API Key
In your Colab notebook, click the key icon (🔑) in the left sidebar to open the "Secrets" tab.

Click "Add a new secret".

For the Name, enter GOOGLE_API_KEY.

For the Value, paste your actual Google Gemini API key.

Make sure the "Notebook access" toggle is turned on.

Step 3: Copy, Paste, and Run!
Copy the entire code block from the file below and paste it into a single cell in your Colab notebook.

🔗 Link to the full Python script

(Note: If you are viewing this on GitHub, click the link above to see the code. Then, copy and paste it into your Colab cell.)

Press Shift + Enter or click the play button (▶️) to run the cell. The Gradio web interface will appear directly in the output area!

🤔 How It Works
The application follows a simple, powerful architecture:

            +---------------------------------+
            |       Gradio Web Interface      |
            | (User Inputs Data, Files, Text) |
            +---------------------------------+
                          |
                          v
            +---------------------------------+
            |    Python Backend (in Colab)    |
            |  (Constructs a detailed prompt) |
            +---------------------------------+
                          |
                          v
            +---------------------------------+
            |       Google Gemini AI API      |
            |    (Generates professional text)  |
            +---------------------------------+
                          |
                          v
+------------------------+ +------------------------+
|   PDF Creation (fpdf2) | |   TXT Creation (I/O)   |
+------------------------+ +------------------------+
              |                      |
              v                      v
        [PDF Download]         [TXT Download]

💡 Future Enhancements
This project has a lot of potential for growth. Here are some ideas for the future:

More Templates: Add a selection of visual resume templates (e.g., "Modern," "Classic").

Cloud Sync: Implement an option to automatically save generated documents to Google Drive.

More Formats: Add support for .docx output for easy editing in Microsoft Word.

Profile Photos: Allow users to upload a profile photo to embed in the resume.

🤝 Contributing
Contributions are welcome! If you have ideas for improvements or want to fix a bug, feel free to:

Fork the repository.

Create a new branch (git checkout -b feature/AmazingFeature).

Commit your changes (git commit -m 'Add some AmazingFeature').

Push to the branch (git push origin feature/AmazingFeature).

Open a Pull Request.

📜 License
This project is licensed under the MIT License - see the LICENSE file for details.

<p align="center">
Developed by <b>Abhijeet Singh</b>
</p>

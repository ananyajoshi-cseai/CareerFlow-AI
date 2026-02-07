# 🧠 CareerFlow AI: Intelligent Career Toolkit

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.12-blue?logo=python" alt="Python">
  <img src="https://img.shields.io/badge/Framework-Streamlit-FF4B4B?logo=streamlit" alt="Streamlit">
  <img src="https://img.shields.io/badge/AI-Gemini_1.5_Flash-4285F4?logo=google-gemini" alt="Gemini">
  <img src="https://img.shields.io/badge/Architecture-End--to--End-brightgreen" alt="Architecture">
  <img src="https://img.shields.io/badge/License-MIT-green" alt="License">
</p>

**CareerFlow AI** is a professional-grade career optimization platform designed to bridge the gap between candidate profiles and industry requirements. By leveraging **Google Gemini 1.5 Flash**, it automates complex tasks like skill-gap analysis, resume scoring, and competitive offer comparison into a seamless, interactive experience.

---

## ✨ Core Features

* **🔍 AI Skill-Gap Scanner**: Deep analysis of Resumes vs. JDs to extract missing technical and soft skills with actionable feedback.
* **⚔️ Job Battle Arena**: A data-driven side-by-side comparison tool that scores job offers based on long-term growth and relevance.
* **📊 Visual Analytics**: High-impact **Radar (Spyder) charts** and match donuts for instant visual assessment of your professional profile.
* **📄 Automated PDF Generation**: Instantly creates tailored, professional cover letters ready for export based on your extracted skills.
* **🛡️ Secure Key Management**: Built with enterprise standards using **Streamlit Secrets** to protect sensitive API credentials.

---

## 🛠️ Technical Stack

* **Frontend & UI**: Streamlit with custom **Glassmorphism CSS** for a premium dark-mode aesthetic.
* **Intelligence Layer**: Google Generative AI (**Gemini 1.5 Flash**) for advanced NLP and reasoning.
* **Database**: **SQLite3** for persistent tracking and history of job application analytics.
* **Data Visualization**: **Plotly** for interactive charts and **Streamlit Lottie** for modern UI animations.
* **Document Processing**: PDFPlumber and FPDF for document parsing and generation.

---

## 🚀 Getting Started

### Prerequisites
* Python 3.12+
* Google Gemini API Key

### Installation
1.  **Clone the repository**:
    ```bash
    git clone [https://github.com/ananyajoshi-cseai/CareerFlow-AI.git](https://github.com/ananyajoshi-cseai/CareerFlow-AI.git)
    cd CareerFlow-AI
    ```
2.  **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```
3.  **Environment Setup**:
    Add your API key to `.streamlit/secrets.toml` or directly into the Streamlit Community Cloud Secrets dashboard:
    ```toml
    GEMINI_API_KEY = "YOUR_API_KEY_HERE"
    ```

### Running Locally
```bash
streamlit run app.py
```

## 📈 Roadmap & Future Scope

- [x] **v1.0 Launch**: Core scanner and visual analytics.
- [ ] **Automated Course Recommendations**: Linking detected skill gaps directly to free learning resources on Coursera or YouTube.
- [ ] **LinkedIn Profile Optimizer**: AI-driven suggestions for LinkedIn headlines and 'About' sections based on resume analysis.
- [ ] **Multi-user Authentication**: Secure login systems to allow users to save and track their career progress over time.

---

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. 

1. Fork the Project.
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`).
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the Branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.

---

## 📜 License

Distributed under the MIT License. See `LICENCE` for more information.

---

<p align="center">
  <b>Developed with ❤️ by Ananya Joshi</b><br>
  <i>B.Tech Computer Science & AI @ IGDTUW</i><br>
  <a href="https://www.linkedin.com/in/ananya-joshi-cseai/">LinkedIn</a> • 
  <a href="https://careerflow-ai.streamlit.app/">Live Demo</a>
</p>

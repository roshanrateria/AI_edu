```markdown
# GraderX: AI Interview Companion  


[![Video Demo](https://img.shields.io/badge/demo-watch%20video-red)](https://youtu.be/srLEcEIc1QM)  

---

## 📌 Overview  
GraderX is an AI-driven interview preparation platform that combines **computer vision** and **large language models (LLMs)** to provide personalized feedback on verbal and non-verbal communication. Originally developed during a computer vision hackathon, this tool simulates real-world interviews while analyzing speech patterns, body language, and technical/behavioral responses.  

**Note**:  
- This repository contains a **demonstration version** of the project. Core functionalities (e.g., AI model integrations, video analytics) are excluded due to a **pending patent** for the system architecture.  
- The included PowerPoint (`GraderX (1).pptx`) refers to outdated technologies (Gemini 1.5 Pro, NeMo) and is retained for archival purposes only.  

---

## 🚀 Key Features  
- **Resume & Job Description Analysis**: Extracts skills, experience, and role-specific requirements using NLP.  
- **Adaptive Question Generator**:  
  - Technical questions (e.g., system design, coding scenarios).  
  - Behavioral questions aligned with STAR frameworks.  
- **Multimodal Feedback**:  
  - **Verbal**: Filler word detection, pacing analysis (120-150 words/minute).  
  - **Non-Verbal**: Eye contact tracking, facial expression classification.  

---

## 🛠 Technologies Used  
- **AI/ML**:  
  - **Gemini 2.0 Flash**: Real-time question generation and intent recognition.  
  - **DeepSeek-R1**: Role-specific NLP for resume/job parsing.  
- **Computer Vision**:  
  - [GazeTracking](https://github.com/antoinelame/GazeTracking): Eye contact analysis.  
  - [DeepFace](https://github.com/serengil/deepface): Emotion recognition.  
- **Web App**: React.js (frontend), Flask (backend), AWS EC2 (hosting).  

---

## ⚠️ Limitations  
1. **Non-Functional Code**:  
   - The `utils.py` module (containing API keys, patent-pending algorithms, and CV pipelines) is excluded.  
   - The repository serves as a **code skeleton** for demonstration purposes only.  
2. **Outdated References**:  
   - The PowerPoint mentions deprecated technologies (Gemini 1.5 Pro, NeMo). The current system uses **Gemini 2.0 Flash** and **DeepSeek-R1**.  

---

## 🔧 Setup (For Reference Only)  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/roshanrateria/Interview.git  
   ```  
2. Install dependencies:  
   ```bash  
   pip install -r requirements.txt  
   ```  
3. Run the Flask server (demo mode):  
   ```bash  
   python app.py  
   ```  

**Note**: The app will NOT execute core functionalities without `utils.py`.  

---

## 📅 Future Work  
- Launch web application with real-time feedback.  
- Integrate industry-specific interview simulations (tech, healthcare).  
- Expand multilingual support (Spanish, Mandarin).  

---

## 📜 License  
 Commercial use or redistribution of the **patent-pending architecture** is prohibited.  

---

## 📧 Contact  
**Roshan Rateria**  
- GitHub: [roshanrateria](https://github.com/roshanrateria)  
- LinkedIn: [Connect here](https://www.linkedin.com/in/roshanrateria/)  

--- 

🔒 **Confidentiality Notice**: The proprietary algorithms and system design are protected under a draft patent (filed Q2 2024).  
```

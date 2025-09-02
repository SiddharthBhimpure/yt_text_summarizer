# 🎥 YouTube Text Summarizer

A **Streamlit-based web application** that extracts transcripts from YouTube videos and generates a **concise, structured summary** using **Google Gemini Pro**. This tool helps users quickly grasp the key points of long videos without watching them entirely.  

---

## 🚀 Features
- Extracts **transcripts** from YouTube videos using `youtube-transcript-api`
- Summarizes videos into **clear bullet points** (within ~250 words)
- Generates summaries using **Google Gemini Pro API**
- Displays the video thumbnail for better context
- Interactive **Streamlit UI** for ease of use

---

## 🛠️ Tech Stack
- **Python 3**
- **Streamlit** – Web app framework  
- **Google Generative AI (Gemini Pro)** – For intelligent summarization  
- **YouTube Transcript API** – To fetch video transcripts  
- **dotenv** – For managing API keys securely  

---

## ⚙️ Installation

### 1. **Clone the repository**  
git clone https://github.com/yourusername/yt_text_summarizer.git

cd yt_text_summarizer

### 2. Create virtual environment 
python -m venv venv

source venv/bin/activate   # For Linux/Mac

venv\Scripts\activate      # For Windows
 
### 3. Install dependencies
pip install -r requirements.txt

### 4. Add your API Key
Create a .env file in the root folder and add your Google Gemini API key:

GOOGLE_API_KEY=your_api_key_here

### 5. Run the Streamlit app:

streamlit run app.py



## 👤 Author
**Siddharth Bhimpure**  
- 🎓 B.Tech in AI & Data Science  


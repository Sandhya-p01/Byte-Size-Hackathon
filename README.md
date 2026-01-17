# Byte-Size-Hackathon
# PulsePoint AI 🎬

Turn long videos into short, shareable reels automatically using AI.

---

## Problem Statement
Mentors, educators, and creators produce hours of long-form content, but modern audiences consume information in short bursts. Valuable insights are often buried in long videos. PulsePoint AI extracts the best moments and generates short, engaging reels.

---

## How It Works
- Upload a long-form video (MP4) in the web app
- The app cuts the video into 3–5 short clips (currently using fixed timestamps)
- Reels are playable directly in the app
- (Optional future upgrade: detect emotional peaks using audio energy & sentiment analysis)

---

## Tech Stack
- **Frontend + Backend:** Streamlit  
- **Video Processing:** MoviePy  
- **Audio Analysis:** Librosa (future)  
- **Transcription/AI:** OpenAI Whisper (future)(Optional)

---

## How to Run Locally
1. Clone the repo:
```bash
git clone <your-repo-link>
cd PulsePoint-AI
```
2. Install Dependencies:
```bash
pip install -r requirements.txt
```
3. Run the app:
```bash
python -m streamlit run app.py
```
4. Open the browser and upload your video.

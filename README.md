# 👋 Hand Gesture Controlled AI Math Solver

A real-time hand-gesture-controlled drawing application that uses OpenCV for hand tracking and Google’s Gemini AI to **solve math problems drawn in the air** — all wrapped in a clean Streamlit UI.

---

## 🚀 Key Features

- **Real-time Hand Tracking** – powered by OpenCV + cvzone  
- **Gesture Recognition** – control drawing and AI triggering with finger poses  
- **Virtual Drawing Canvas** – NumPy + OpenCV based  
- **Gemini-Powered Math Solver** – sends drawings to Google Gemini to get answers  
- **Streamlit UI** – simple web interface  
- **Dynamic Drawing** – draw with index finger  
- **Canvas Reset** – clear when only thumb is up  
- **AI Trigger** – lift all fingers (except thumb) to send to AI  
- **Webcam Integration** – works from your laptop camera  

---

## 🛠️ Tech Stack

| Category   | Technology             | Description                                    |
|-----------|------------------------|------------------------------------------------|
| Frontend  | Streamlit              | Web UI                                         |
| Backend   | Python                 | Application logic                              |
| Vision    | OpenCV (cv2)           | Video capture, drawing                         |
|           | cvzone                | Easier hand tracking                           |
| AI        | Google Gemini AI       | Math solving                                   |
|           | google-generativeai   | Python library to access Gemini                |
| Data      | NumPy                  | Array ops + canvas                             |
|           | Pillow (PIL)           | Convert images for Gemini                      |
| Other     | os                     | File usage                                     |

---

## 📦 Getting Started

### ✅ Prerequisites

- Python 3.6+
- pip

### 🔧 Installation

```bash
git clone <repository_url>
cd <repository_directory>
pip install -r requirements.txt
```

`requirements.txt` should include:

```
streamlit
opencv-python
cvzone
numpy
google-generativeai
pillow
```

### 🔐 Set Up Gemini API Key

- Get an API key from Google AI Studio.
- Option 1 (recommended): export env variable

```bash
export GOOGLE_API_KEY="YOUR_API_KEY"
```

- Option 2 (less secure):

```python
import google.generativeai as genai
genai.configure(api_key="YOUR_API_KEY")
```

### ▶️ Run Locally

```bash
streamlit run edit2.py
```

Open the URL shown in terminal (usually `http://localhost:8501`)

---

## 📁 Project Structure

```
├── edit2.py            # Main Streamlit app
├── requirements.txt    # Python dependencies
├── .gitignore          # Ignore files
└── README.md           # Documentation
```

---

## 🤝 Contributing

1. Fork this repo  
2. Make a new branch  
3. Commit changes with good messages  
4. Open a Pull Request  

---

## 📝 License

MIT

---

## 📬 Contact

Questions/suggestions → **ikeshav62@gmai.com**

---

## 💖 Thanks

Thanks for checking this out — hope you like it! Feel free to send feedback or contribute 🙏

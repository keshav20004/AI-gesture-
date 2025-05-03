# ✏️ AI Math Solver

A Streamlit-based app that captures handwritten math problems, interprets the input using computer vision, and sends the problem to Google's Gemini API to generate step-by-step solutions.

---

## 🔧 Features

- ✍️ Draw math problems directly on a canvas
- 🧠 Image-to-text interpretation using a hand pose detection model
- 🔎 Sends input to Google Gemini API for detailed math solution + explanation
- 📜 Real-time solution display via Streamlit UI

---

## 🛠️ Tech Stack

- **Frontend**: Streamlit
- **ML/CV**: MediaPipe (hand detection), OpenCV, PIL
- **LLM**: Google Gemini (via `google.generativeai`)
- **Backend**: Python

---

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- Google Cloud Project with [Generative Language API](https://ai.google.dev/) enabled
- Billing activated for your GCP project

### Installation

```bash
git clone https://github.com/your-username/ai-math-solver.git
cd ai-math-solver
pip install -r requirements.txt

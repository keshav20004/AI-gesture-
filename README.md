👋 Hand Gesture Controlled AI Math Solver
This project is a real-time hand gesture-controlled drawing application that leverages OpenCV for video capture and hand tracking, and Google's Gemini AI model to solve math problems drawn on a virtual canvas. The application is built using Streamlit for a user-friendly web interface. It allows users to draw math equations using hand gestures, which are then interpreted by the Gemini AI model to provide solutions.

🚀 Key Features:

Real-time Hand Tracking: Utilizes OpenCV and cvzone to detect and track hand movements in real-time.
Gesture Recognition: Interprets hand gestures to control drawing and trigger AI processing.
Virtual Canvas: Creates an interactive drawing canvas using NumPy and OpenCV.
AI-Powered Math Solving: Integrates with Google's Gemini AI model to solve math problems drawn on the canvas.
Streamlit UI: Provides a user-friendly web interface for interacting with the application.
Dynamic Drawing: Draws lines on the canvas based on the position of the index finger.
Canvas Reset: Clears the canvas when only the thumb is raised.
AI Trigger: Sends the canvas content to the Gemini AI model when all fingers except the thumb are raised.
Webcam Integration: Seamlessly integrates with the user's webcam for real-time video input.
🛠️ Tech Stack:

Category	Technology	Description
Frontend	Streamlit	Web application framework for creating the user interface.
Backend	Python	Programming language for the application logic.
Vision	OpenCV (cv2)	Library for video capture, image processing, and drawing.
cvzone	Computer vision library simplifying hand tracking.
AI	Google Gemini AI	AI model for solving math problems.
google.generativeai	Python library for interacting with the Gemini AI model.
Data	NumPy	Library for numerical operations and canvas creation.
PIL (Pillow)	Library for image format conversion for AI model compatibility.
Other	os	Used for checking file existence.
📦 Getting Started:

Prerequisites
Python 3.6+
Ensure you have pip installed.
Installation
Clone the repository:

git clone <repository_url>
cd <repository_directory>
Install the required packages:

pip install -r requirements.txt
Create a requirements.txt file with the following content:

streamlit
opencv-python
cvzone
numpy
google-generativeai
pillow
Set up Google Gemini AI API Key:

Obtain an API key from Google AI Studio.

Set the API key as an environment variable:

export GOOGLE_API_KEY="YOUR_API_KEY"
Or, you can directly set it in your script (not recommended for security reasons):

import google.generativeai as genai
genai.configure(api_key="YOUR_API_KEY")
Running Locally
Run the Streamlit application:

streamlit run edit2.py
Access the application:

Open your web browser and go to the URL displayed in the terminal (usually http://localhost:8501).

📂 Project Structure:

├── edit2.py               # Main application file
├── requirements.txt      # List of Python dependencies
├── .gitignore            # Specifies intentionally untracked files that Git should ignore
├── README.md             # Project documentation


🤝 Contributing:

Contributions are welcome! Please follow these steps:

Fork the repository.
Create a new branch for your feature or bug fix.
Make your changes and commit them with descriptive messages.
Submit a pull request.
📝 License:

This project is licensed under the MIT License - see the LICENSE file for details.

📬 Contact:

If you have any questions or suggestions, feel free to contact me at ikeshav62@gmai.com

💖 Thanks Message:

Thank you for checking out this project! I hope you find it useful and interesting. Your feedback and contributions are highly appreciated.

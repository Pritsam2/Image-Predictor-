🎬 Bollywood Celebrity Lookalike Finder

Have you ever wondered which Bollywood celebrity you resemble the most? This fun and smart project uses facial recognition technology to match your photo with a Bollywood star. Upload your image, and our model will find the closest match from a curated dataset of Bollywood celebrities.

🔍 Features

📸 Upload a selfie or portrait image
🧠 Facial feature extraction using deep learning
🎭 Match your face to the most similar Bollywood celebrity
📊 Confidence score of the match
💻 Simple, user-friendly interface (web or CLI-based)
🛠 Tech Stack

Python
Face Recognition (using dlib or face_recognition library)
OpenCV for image preprocessing
Streamlit / Flask for the web interface (optional)
Pandas, NumPy for data handling
scikit-learn / cosine similarity for matching
📁 Project Structure

bollywood-lookalike/
│
├── data/                  # Bollywood celebrity images
├── src/                   # Main source code
│   ├── detector.py        # Face detection and alignment
│   ├── matcher.py         # Matching logic
│   └── app.py             # Web interface or CLI
├── notebooks/             # Jupyter notebooks for experiments
├── requirements.txt       # Python dependencies
└── README.md              # Project overview


🧩 Fingerprint Recognition System using OpenCV and Streamlit

🎯 Project Overview

This project demonstrates a minutiae-based fingerprint recognition system built with OpenCV, NumPy, scikit-image, and Streamlit.
It extracts and compares fingerprint features — ridge endings and bifurcations — using advanced image processing techniques and visualizes results in a clean web interface.

🧠 Purpose: Educational & experimental implementation for biometrics and cybersecurity learning.

🧠 Key Features
Feature	Description
🔍 CLAHE Enhancement:-	Improves fingerprint contrast and ridge visibility

🎚 Matching Tolerance:-	Adjustable pixel threshold for matching accuracy

🧭 Gabor Filter:-	Enhances ridge texture and directionality

🧩 Minutiae Detection:- 	Identifies ridge endings (red) and bifurcations (blue)

💡 Interactive UI:- 	Built on Streamlit for real-time experimentation

🧱 Skeleton View:- 	Optional visualization of thinned fingerprint structure

🖼️ Demo Preview

⚙️ Tech Stack

Component	Technology

--> Frontend:-	Streamlit

--> Image Processing:-	OpenCV, scikit-image

--> Logic:- 	NumPy, SciPy

--> Visualization:- Matplotlib

--> Deployment:- 	Streamlit CLI / Localhost

📂 Folder Structure

Fingerprint-Recognition/

│── fingerprint_app_improved.py

│── requirements.txt

│── assets/

│   └── demo_screenshot.png

│── README.md

│── LICENSE


🧰 Installation & Usage
Step 1: Clone the repository
git clone https://github.com/Himanshu6611/Fingerprint-Recognition.git

cd Fingerprint-Recognition

Step 2: Install dependencies
pip install -r requirements.txt

Step 3: Run the application
streamlit run fingerprint_app_improved.py

Step 4: Open in Browser

Streamlit will show:

Local URL: http://localhost:8501


Click the link to launch the web interface.

🧾 Requirements.txt
-> opencv-python

-> numpy

-> scikit-image

-> streamlit

-> scipy

-> matplotlib


🧪 How It Works

1️⃣ Preprocessing

-> Converts image to grayscale

-> Applies CLAHE & optional Gabor filter

-> Performs binarization & skeletonization

2️⃣ Minutiae Extraction

-> Detects ridge endings & bifurcations

-> Marks with red (endings) and blue (bifurcations) circles

3️⃣ Matching Algorithm

-> Computes Euclidean distance between keypoints

-> Calculates match score based on tolerance

4️⃣ Output

-> Displays both fingerprints side by side

-> Shows similarity score and decision threshold

💡 Use Cases

-> Biometric and forensic training

-> Cybersecurity projects

-> AI & image processing demos

-> Educational learning tools

🔮 Future Enhancements

🔁 Add rotation and scale alignment

💾 Database-based fingerprint storage and matching

📱 Integrate mobile camera scanning

🧠 Apply CNN or deep learning-based matching

🔒 Encrypt fingerprint feature data

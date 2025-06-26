 Automation of Facial Palsy Rehabilitation Evaluation using Machine Learning

This project automates the rehabilitation assessment of facial palsy patients using computer vision and machine learning. By analyzing facial landmarks and asymmetry through images or videos, the system provides quantitative scores that assist in clinical evaluation—offering a cost-effective and efficient solution to traditional manual grading.
🎯 Objective

To build an automated tool that evaluates facial palsy by detecting facial asymmetry and assigning a severity grade using machine learning models trained on real patient data.
🧠 Core Features

    🖼️ Facial Landmark Detection using Dlib/MediaPipe

    📏 Asymmetry Measurement for affected vs unaffected facial regions

    🤖 ML Model for classifying facial palsy severity (e.g., normal, mild, moderate, severe)

    📊 Visualization of detected features and asymmetry

    💾 Batch evaluation support for multiple patient images

🛠️ Technologies Used

    Python 3.x

    OpenCV – Image processing

    Dlib / MediaPipe – Facial landmark detection

    Scikit-learn – Model training and evaluation

    NumPy, Pandas – Data manipulation

    Matplotlib, Seaborn – Visualization

📂 Project Structure

facial-palsy/
│
├── facial_landmarks.py         # Facial landmark detection logic
├── asymmetry_analysis.py       # Asymmetry measurement functions
├── model_training.ipynb        # ML model training and evaluation
├── data/                       # Dataset of facial images
├── results/                    # Prediction results and visual outputs
├── README.md                   # Project documentation
└── requirements.txt            # Python dependencies

⚙️ How to Run

    Clone the Repository

git clone https://github.com/ronaktomar001/facial-palsy.git
cd facial-palsy

Install Dependencies

pip install -r requirements.txt

Run Landmark Detection

python facial_landmarks.py --image path/to/image.jpg

Run Asymmetry Analysis and Prediction

python asymmetry_analysis.py --input path/to/folder/

Train the Model (optional)
Open and run:

    model_training.ipynb

📈 Accuracy

    Achieved approximately 83% accuracy in classification of severity levels based on test data.

📸 Sample Outputs

    (Include some annotated images with facial landmarks and asymmetry highlighted)

📌 Future Improvements

    Extend support for real-time video analysis

    Improve accuracy with deep learning (e.g., CNN)

    Integrate with clinical scoring systems (e.g., House-Brackmann scale)

📧 Contact

Ronak Tomar
🔗 GitHub Profile
✉️ ronaktomar001@gmail.com

🧩 Key Features

-Automated attendance recording (no manual input needed)

-Real-time face detection and recognition

-Fraud prevention — eliminates proxy attendance

-Web-based interface for teachers to upload class photos and view results

-Excel report export for attendance records

-Secure and anonymous data handling




🧠 Technologies Used
-Category	Tools / Libraries
-Face Detection	MTCNN
-Face Recognition	ArcFace via InsightFace
-Deep Learning	TensorFlow / PyTorch
-Web Framework	Streamlit
-Image Processing	OpenCV, Scikit-Image
-Data Handling	Pandas, NumPy
-Storage	Google Drive (dataset handling)





⚙️ System Architecture

-Data Collection & Preprocessing

-Capture individual and group student images.

-Apply augmentation (rotation, brightness, cropping) for dataset diversity.

-Align and label faces using MTCNN.

-Model Development & Evaluation

-Generate embeddings using ArcFace.

-Train and test models under multiple configurations.

-Evaluate using metrics: Accuracy, Precision, Recall, F1-score, FAR, FRR.

-Web Application Deployment

-Integrate trained model into a Streamlit interface.

-Allow real-time photo upload and recognition.

-Save attendance logs and generate downloadable reports.




📈 Results (FYP I)
Metric	Value
Accuracy	77.27%
Precision	79.79%
Recall	77.27%
F1-Score	76.28%

Preliminary results indicate solid recognition performance with further improvements expected in FYP II through dataset expansion and optimization.





🔒 Data Privacy

-Images are collected with consent.

-No raw facial images are stored permanently.

-Attendance reports use anonymous identifiers.





🧰 Functional Requirements

-Face detection & recognition (MTCNN + ArcFace)

-Data preprocessing (alignment, augmentation)

-Real-time processing during classes

-Web-based upload and attendance report generation

-Secure data handling and export to Excel

# skin-sight-ai-_Skin-diseases-detection-and-diagnoses-
check out my project here - https://colab.research.google.com/drive/11J37HgGUrklrJvDBTqhv6leQXS3maC_Y?usp=sharing

Skin Sight AI
Skin Sight AI is a deep learning-based skin disease classification system that leverages Convolutional Neural Networks (CNNs) for early, automated diagnosis of five common skin conditions using dermatoscopic images.

🚀 Features
Disease Classification: Automatically classifies dermatoscopic images into five common skin conditions:
* Actinic Keratosis
* Dermatofibroma
* Melanoma
* Seborrheic Keratosis
* Squamous Cell Carcinoma

- Image Segmentation: Isolates skin lesions from surrounding tissue to focus analysis.
- Feature Extraction: Analyzes color, texture, and border features to enhance classification accuracy.
- Data Augmentation: Applies techniques to improve model robustness across diverse skin tones and imaging conditions.
- Severity Estimation: Provides an estimation of disease severity to aid in clinical decision-making.
- Deployment Ready: Designed for use in remote and resource-limited settings, facilitating accessible dermatological diagnostics.

🧰 Tech Stack
* Python
* TensorFlow / Keras
* OpenCV (for image segmentation)
* NumPy
* Matplotlib
* Scikit-learn


📂 Dataset
- HAM10000 Dataset: Utilizes the HAM10000 dataset, which contains 10,015 dermatoscopic images of common pigmented skin lesions.
- Preprocessing: Images are preprocessed and augmented to ensure class balance and diversity, enhancing model generalization.
SpringerLink

📈 Model Architecture
- Convolutional Neural Networks (CNNs): Employs CNNs for feature extraction and classification tasks.
- Segmentation Module: Incorporates image segmentation to isolate lesions, improving focus on relevant features.
- Feature Extraction: Analyzes key features such as color, texture, and border irregularities.
- Severity Estimation: Implements a module to estimate the severity of detected conditions.

🌍 Deployment
- Skin Sight AI is optimized for deployment in remote and resource-limited settings, providing accessible diagnostic support where traditional dermatological services may be unavailable.

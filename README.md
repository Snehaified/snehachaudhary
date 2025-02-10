# 🎯 Software Engineer | AI Enthusiast
💡 Passionate about leveraging **Artificial Intelligence** to solve real-world challenges in **healthcare, sustainability, and automation**.  

### Projects
### **1️⃣ In-Silico Detection and Segmentation of Brain Tumors Using Deep Learning and Image Processing**

🧠 **Impact**: Early and cost-effective detection of brain tumors, potentially saving lives.
🛠  **Tech Stack**: Python, TensorFlow, OpenCV, CNNs, Image Processing

🔹 Problem:  Manual diagnosis using MRI scans is time-consuming & prone to errors due to tumor size variations and similarities with healthy tissues.
🔹 Solution: Developed an AI-based system to detect and localize brain tumors from MRI scans using Deep Learning.

- Applied CLAHE and filtering techniques to enhance MRI images before classification.
- Built a segmentation model to highlight tumors at the pixel level, improving diagnostic accuracy.
- Enables early tumor detection, reducing cancer diagnosis costs.
  
<figure>
  <img src="assests/brain_tumor_detection.png" alt="Brain Tumor Detection" width="600">
  <figcaption>Figure 1: Input MRI scan and its corresponding mask, the MRI image with the actual mask, the mask predicted by the ResUNet model and the MRI image 
with the predicted mask</figcaption>
</figure>


### **2️⃣ BioCrypt : Gradient-based facial encoding for key generation to encrypt and decrypt multimedia data**

🔒  **Impact**: Resilience against attacks and enhanced security system for sensitive data
🛠  **Tech Stack**: Python, Scikit-learn, AES, 

🔹 Problem: Traditional password-based security is prone to hacking & forgetting, while biometric-only security can be spoofed or replayed.
🔹 Solution: Developed a biocryptosystem using face recognition & AES encryption to securely encrypt and decrypt any type of file (text, audio, video).

How It Works:
✅ Captures facial traits using Histogram of Oriented Gradients (HOG) for feature extraction, even in low-light conditions.
✅ Uses Support Vector Machine (SVM) for accurate classification of authorized users.
✅ Once verified, the system encrypts/decrypts files using AES (Advanced Encryption Standard).
✅ Provides an extra layer of security by incorporating biometric data in a 2FA process.

Key Features & Results:
✔️ High Security: Biometric authentication makes unauthorized access nearly impossible.
✔️ Robust Encryption: AES encryption ensures strong data protection.
✔️ Experimental Validation: Achieved high precision & security based on entropy, avalanche effect, and Hamming distance.

📌 Use Cases:
🔹 Secure file storage & sharing
🔹 Online transactions with biometric authentication
🔹 Data archiving with enhanced security

<figure>
  <img src="assests/brain_tumor_detection.png" alt="Brain Tumor Detection" width="600">
  <figcaption>Figure 1: Input MRI scan and its corresponding mask, the MRI image with the actual mask, the mask predicted by the ResUNet model and the MRI image 
with the predicted mask</figcaption>
</figure>

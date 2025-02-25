Secure Data Hiding in Image Using Steganography
A Python-based steganography tool that securely hides encrypted data within images using the Least Significant Bit (LSB) technique. This project enhances secure communication by embedding sensitive information in images while maintaining their visual integrity.

🚀 Features
✅ Steganography Implementation – Hides secret messages inside images using LSB technique.
✅ AES Encryption – Encrypts data before embedding, adding an extra layer of security.
✅ Minimal Image Distortion – Ensures that hidden data remains undetectable.
✅ User-Friendly Interface – Simple GUI for embedding and extracting messages.
✅ Robust Security – Data extraction requires both the original image and the correct decryption key.

🔧 Technologies Used
Programming Language: Python
Libraries: OpenCV, NumPy, Pillow
Encryption Algorithm: AES (Advanced Encryption Standard)

📌 How It Works
Encrypt the Secret Message – The input text is first encrypted using AES.
Embed the Encrypted Data – The encrypted data is hidden in an image using the LSB method.
Extract and Decrypt – The hidden message can be retrieved using the same key and then decrypted.


📂 Installation & Setup
Clone the repository:
bash
Copy
Edit
git clone https://github.com/Anubprashnath/Secure Data Hiding in Image Using Steganography.git
cd steganography-project
Install dependencies:
bash
Copy
Edit
pip install -r requirements.txt
Run the program:
bash
Copy
Edit
python main.py
📌 Use Cases
🔹 Secure Government & Defense Communications
🔹 Corporate Data Protection
🔹 Journalists & Whistleblowers Secure Messaging
🔹 Personal Secure Communication

🚀 Future Enhancements
🔹 Support for multiple image formats (JPEG, PNG, BMP)
🔹 Integration of deep learning for anti-steganalysis protection
🔹 Real-time secure messaging feature

📜 License
This project is open-source under the MIT License.


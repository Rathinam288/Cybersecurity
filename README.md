# encrpy-decrypt
Image-Based Message Encryption & Decryption
This project implements image steganography to hide and retrieve secret messages within an image using OpenCV. The encryption process embeds a message into the pixel values, and the decryption extracts it back.

🚀 Features
✅ Hide a secret message inside an image.
✅ Password-protected encryption & decryption.
✅ Uses pixel manipulation to store data.
✅ Retrieves the original message without distortion.

🛠️ Technologies Used
Python
OpenCV (cv2)
Image Processing
File Handling

PROJECT STRUCTURE

│── encrypt.py       # Encrypts a message into an image  
│── decrypt.py       # Decrypts the message from the image  
│── encryptedImage.jpg  # The output image with the hidden message  
│── password.txt     # Stores the encryption password  
│── README.md        # Project documentation  
│── presentation.ppt # Project explanation slides  
│── sample_image.jpeg # Original image for encryption  

⚡ How to Use
🔹 Encryption
1️⃣ Run encrypt.py

python encrypt.py

2️⃣ Enter your secret message and passcode.
3️⃣ The encrypted image (encryptedImage.jpg) is generated.

🔹 Decryption
1️⃣ Run decrypt.py
2️⃣ Enter the correct passcode.
3️⃣ The hidden message is retrieved and displayed.

📌 Future Enhancements
🔹 Support for larger messages across multiple pixels.
🔹 Advanced encryption using cryptographic techniques.
🔹 GUI-based interface for better usability.




### **Steganography Image Encryption Project**

This project demonstrates a simple image-based steganography technique, where a secret message is embedded into an image file. The message is hidden by modifying the pixel values of the image, and it can later be decrypted using a passcode. This project utilizes **OpenCV** for image manipulation and basic Python data structures for encoding and decoding the message.

#### **Key Features:**
- **Message Encryption:** A secret message is converted into its ASCII representation and embedded within the pixels of an image.
- **Passcode-based Decryption:** Only the correct passcode allows the decryption of the embedded message, ensuring security.
- **Customizable Image and Message:** Users can input their own image, secret message, and passcode for encryption and decryption.

#### **How it Works:**
1. The secret message is converted to ASCII values, and each character is stored in the image pixel values.
2. A password is required to decrypt the message, ensuring only authorized access.
3. The message is extracted from the altered pixels and displayed to the user once the correct passcode is provided.

#### **Technologies Used:**
- Python
- OpenCV (cv2)
- Basic Data Structures (Dictionary, List)

#### **Usage Instructions:**
1. Clone the repository and install required dependencies.
2. Run the script and input your secret message and passcode to encrypt the image.
3. To decrypt, provide the correct passcode when prompted.

# AICTE_Steganography_Project
This project demonstrates a simple implementation of image steganography using Python and OpenCV. The application allows users to hide (encrypt) a secret message inside an image and later retrieve (decrypt) the message using a simple UI built with Tkinter.
Features
Encryption: Embed a secret message into an image.
Decryption: Extract the hidden message from an image.
Passcode Protection: Secure the hidden message using a passcode.
GUI Interface: User-friendly interface with separate tabs for encryption and decryption.
Technologies Used
Python 3.13: The primary programming language.
OpenCV (cv2): For image processing (reading, writing, and modifying images).
NumPy: For efficient array manipulation, especially for pixel data.
Tkinter & ttk: For creating the GUI with a dark theme.
OS Module: For file path operations and checking file existence.
Installation
Clone the Repository:
git clone <https://github.com/aakash2806/Steganography_Project.git>
cd <repository-folder>
Install Dependencies: Ensure you have Python 3.13 installed.Then, install the required packages:
pip install opencv-python numpy
Usage
Configuring the Folder/Image Path

The current code uses a fixed folder path (F:\Python\steganography project) and expects an image file named mypic.jpg in that folder. To change these settings:

Open the code file.
In both the encrypt() and decrypt() functions, update the folder variable to your desired path:
folder = r"your\desired\folder\path"
Update the image file name if needed:
Update the image file name if needed:
Ensure that the specified image exists in the given folder before running the program.
Running the program
Save the provided code into a file, for example, steganography_tool.py.
Run the script from the command line:
python steganography_tool.py
The GUI will open with two tabs:
Encryption Tab: Enter your secret message and passcode, then click "Encrypt" to embed the message into the image. The encrypted image (encryptedpic.png) will be saved in your configured folder.

Decryption Tab: Enter the passcode to retrieve the hidden message from the encrypted image.

Folder Structure
steganography_project/
├── README.md
├── steganography_tool.py
└── (Folder where images are stored, e.g., "F:\Python\steganography project")
     ├── mypic.jpg           # Input image
     └── encryptedpic.png    # Output image (generated after encryption)
License
This project is open source and available under the MIT License.

Contribution
Contribution, suggestion, and bug reports are welcome! Feel free to open an issue or submit a pull requesr.



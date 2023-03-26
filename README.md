# Image-Encryption
This Python script allows you to encrypt an image file using a simple encryption algorithm. The encrypted image can only be decrypted using the same script.

Installation: 
1. Clone the repository to your local machine: 
git clone https://github.com/your-username/image-encryption.git
2. Install the required packages:
pip install -r requirements.txt
Usage
Open image-encryption.py and modify the input_file and output_file variables to match your desired input and output file paths.

Run the script:
python image-encryption.py

Enter a password when prompted. Note that the password is case-sensitive and cannot be recovered once entered, so make sure to remember it.
The script will encrypt the input image and save the encrypted output to the specified output file path.
To decrypt the encrypted image, runt the script again and select "decrypt". when prompted. Enter the same password used to encrypt the image, and the script will output the decrypted image to the specified output file. 

Limitations
The current implementation only supports PNG and JPEG image formats.
The encryption algorithm used in this script is not suitable for high-security applications and is intended for educational purposes only.
License
This project is licensed under the MIT License - see the LICENSE.md file for details.

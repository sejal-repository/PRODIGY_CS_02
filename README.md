# PRODIGY_CS_02
Image Encryption and Decryption using Pixel Manipulation
How It Works
Each pixel in a digital image is made up of three color channels: Red, Green, and Blue (RGB).
During encryption, the value of each color channel is modified using a simple formula:

# Encrypted Pixel =(Original Pixel+Key)% 256 
# Encrypted Pixel=(Original Pixel+Key)%256
The same logic is reversed during decryption:

# Decrypted Pixel=(Encrypted Pixel−Key)% 256
# Decrypted Pixel=(Encrypted Pixel−Key)% 256
This ensures the original image can be perfectly recovered only with the correct key.

# Files Included
image_encryptor.py – Main Python script for encryption and decryption.
CAT.jpg – Sample input image.
encrypted_CAT.jpg – Encrypted output image.
decrypted_CAT.jpg – Decrypted image after using the correct key.
README.md – Project explanation and instructions.

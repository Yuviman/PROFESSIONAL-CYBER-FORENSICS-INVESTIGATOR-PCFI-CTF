Can you give the Linux Tool that is used for Steganography?
steghide is used for extracting embedded data from images and also hide data inside files

after downloading the file use steghide to extract the data file:
steghide extract -sf 1b82a10a3d5edc5208439f24c50c8e69.jpg
(-sf is the flag to mention Source File, dont forget the enter the passphrase:pass123)
steghide extract -sf 1b82a10a3d5edc5208439f24c50c8e69.jpg -p pass123

Then you get the extrated data file which can be read using cat:
cat secrets.txt

![1b82a10a3d5edc5208439f24c50c8e69](https://github.com/user-attachments/assets/5c978b11-7e21-43f1-9219-6c33f4253ca6)

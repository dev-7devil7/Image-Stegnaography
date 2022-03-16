# Image-Stegnaography
Steganography is the art of hiding the fact that communication is taking place, by hiding information. Many different carrier file formats can be used, but digital images are the most popular because of their frequency on the Internet.


For hiding secret information in images, there exists a large variety of steganographic techniques (LSB encoding, MSB encoding, PARITY bit coding) some are more complex than others and all of them have respective strong and weak points. Different applications have different requirements of the steganography technique used. The current available image steganography techniques are not secure data can be retrieved with techniques like Reverse Engineering.


The main objective of this project is to send and receive confidential information like bank details, passwords or any secret information by hiding it in images securely by encrypting the data. In order to increase the strength information is encrypted and signed with password by converting it into hash with one of the most secure hashing technique called SHA256(which is used in bitcoin) . Therefore the information encoded by the sender can only be decoded by the receiver who has correct password. There by providing authentication. We will be adding some user friendly features to help naïve users.

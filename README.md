Asymmetric Encryption and Decryption Using Python
This project demonstrates how to perform asymmetric encryption and decryption using Python's cryptography library. The implementation includes generating RSA key pairs, encrypting a message with the public key, and decrypting it with the private key.

Features
Generate RSA private and public key pairs.
Serialize keys into PEM format for storage and sharing.
Encrypt messages with the RSA public key.
Decrypt messages with the RSA private key.
Ensure secure padding using the OAEP scheme.

Technologies Used
Language: Python 3.12.4
Library: cryptography

Code Workflow
1. Generate RSA Keys
We generate a 2048-bit RSA key pair using Python's cryptography library.

2. Serialize Keys
Both private and public keys are serialized into PEM format for easy storage or sharing.

3. Encrypt a Message
The public key is used to encrypt a message securely, ensuring confidentiality.

4. Decrypt the Ciphertext
The private key decrypts the ciphertext, recovering the original message

Author
Arjun J R

📧 Email: arjunjr6996@gmail.com
💼 LinkedIn: linkedin.com/in/arjun-j-r-4901a6219
🐙 GitHub: Arjun-JR


## Secure Chat Application

### 📌 Project Overview
The **Secure Chat Application** is a Windows-based application developed in **Visual Studio** using **VB.NET**.  
It allows users to exchange messages securely using both **symmetric** and **asymmetric** cryptographic techniques.  
The project implements multiple algorithms for encryption, decryption, integrity checking, and authentication.

---

### 🛠 Technology Stack
- **IDE:** Visual Studio  
- **Language:** VB.NET  
- **Framework:** .NET Framework / Windows Forms  
- **Crypto Algorithms:** Symmetric, Asymmetric, Hashing, and Digital Signature

---

### 🔐 Supported Cryptographic Techniques

### Symmetric Encryption
- Caesar Cipher  
- Monoalphabetic Cipher  
- Polyalphabetic Cipher  
- Hill Cipher  
- Playfair Cipher  
- One-Time Pad (OTP)  
- Rail Fence Cipher  
- Columnar Cipher  
- DES (Data Encryption Standard)  
- AES (Advanced Encryption Standard)  
- RC4 Stream Cipher  

### Asymmetric Encryption
- RSA  
- ECC (Elliptic Curve Cryptography)  

### Key Exchange
- Diffie-Hellman (DH)  

### Integrity & Authentication
- SHA Hashing (Message Integrity)  
- DSA (Digital Signature Algorithm)  

---

### 💡 How It Works

1. **Key Exchange**  
   - Symmetric: Pre-shared key between sender & receiver  
   - Asymmetric: Public/Private key pairs for secure message exchange  

2. **Encryption**  
   - Sender selects technique, inputs plaintext, and applies encryption with the chosen key  

3. **Transmission**  
   - Encrypted message (ciphertext) is sent to receiver  

4. **Decryption**  
   - Receiver uses correct key/technique to decrypt back to plaintext  

5. **Integrity & Authentication**  
   - SHA hashing ensures data integrity  
   - DSA verifies sender authenticity  

---

### 📸 Screenshots

**Main Interface**  
![Main Interface](images/main_interface.png)

**Encryption Example**  
![Encryption Example](images/encryption_example.png)

**Decryption Example**  
![Decryption Example](images/decryption_example.png)

> *(Replace image paths with actual screenshots in your `images/` folder)*

---

[← Back](https://github.com/mmransem09/mmransem09/blob/main/README.md)

## 📊 Example Workflow

**Sender:**
```plaintext
Plaintext: HELLO WORLD
Key: MYKEY
Technique: AES
Ciphertext: Zx9Pq1fL0tY...

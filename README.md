# pdfencryptdecrypt
KDE Plasma Service Menu for Encrypting /

Decrypting PDF Files with AES 256 bits

## Introduction

AES (Advanced Encryption Standard) with a key length of 256 bits is considered secure due to its robust cryptographic algorithm and the sheer number of possible key combinations. With 256 bits, there are 22562256 possible keys, which is an astronomically large number (more than the estimated number of atoms in the observable universe). This immense key space makes brute-force attacks computationally infeasible, even with the most powerful computers available today. Additionally, AES has undergone extensive scrutiny and analysis by cryptographers worldwide, and no practical vulnerabilities have been found when implemented correctly. Therefore, AES 256 bits is widely trusted for securing sensitive data and is considered one of the most secure encryption standards available.

This guide provides instructions on how to use the KDE Plasma service menu to encrypt and
decrypt PDF files using the symmetrical 256-bit AES method. These actions are accessible via the
context menu when right-clicking on a PDF file.

## Requirements:

- Linux operating system with Plasma desktop environment
- Install the Service Menu system-wide: # cp pdfencryptdecrypt.desktop /usr/share/kservices5/ServiceMenus/
- qpdf binary must be installed

## Encrypting a PDF File

- **Action:** Encrypt a secure PDF using the symmetrical 256-bit AES method
- **Description:** This action allows you to encrypt a PDF file to enhance its security.

- **Instructions:**
  1. Right-click on the PDF file you want to encrypt.
  
  2. Select "Encrypt PDF" from the context menu.
  
  3. Follow the on-screen instructions:
  - Enter the user password.
  - Enter the owner password. 
  - Select printing permissions.
  - Select modification permissions.
  - Select extraction permissions.
  
  4. Click "OK" to proceed.

  5. Wait for the encryption process to complete.
  
  6. A confirmation message will appear when the PDF has been encrypted successfully.

## Decrypting a PDF File

- **Action:** Decrypt a secure PDF using the symmetrical 256-bit AES method
- **Description:** This action allows you to decrypt a previously encrypted PDF file.
- **Instructions:**
  1. Right-click on the encrypted PDF file you want to decrypt.

  2. Select "Decrypt PDF" from the context menu.
  
  3. Follow the on-screen instructions:
  - Enter the user password.
  - Enter the owner password.
 
  4. Click "OK" to proceed.

  5. Wait for the decryption process to complete.
  
  6. A confirmation message will appear when the PDF has been decrypted successfully.

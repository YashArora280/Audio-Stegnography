# Audio-Stegnography
Secure Audio Communication using Diffie-Hellman and AES
Python | Cryptography | Audio Encryption | Diffie-Hellman Key Exchange | AES | PyDub

Developed a secure audio transmission system integrating Diffie-Hellman key exchange to establish a shared secret between sender and receiver.

Utilized the shared secret to derive a 256-bit AES key for encryption and decryption of .wav audio files using ECB mode with PKCS7 padding.

Implemented key generation, secure key sharing via public/private keys, and encrypted audio storage with randomized filenames.

Designed CLI-based interaction to support end-to-end encryption and decryption workflow for audio files, demonstrating applied cryptography in multimedia.

Ensured compatibility with multiple audio formats via PyDub and handled secure key persistence in external files.

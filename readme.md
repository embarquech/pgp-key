PGP Public Key

This repository contains my PGP public key and official fingerprint.
Use it to encrypt messages or verify my identity.

Email:
contact@embarque.ch

Fingerprint:
BA0657F51DB4D6F523EEE322C87F38B4246D3D18

Files:
- pubkey.asc : my public key in ASCII format
- fingerprint.txt : my fingerprint (optional)

How to import my key:

From this repository:
gpg --import pubkey.asc

From a key server:
gpg --recv-keys BA0657F51DB4D6F523EEE322C87F38B4246D3D18
# or by email (if confirmed)
gpg --recv-keys contact@embarque.ch

Verify the fingerprint:
gpg --fingerprint contact@embarque.ch
# Make sure the fingerprint matches the one above

Encrypt a message for me:
gpg --encrypt --armor -r contact@embarque.ch message.txt

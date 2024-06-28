# Scyther--Enctyption-Methods
Encryption Protocol Simulations using Scyther  This repository contains Scyther scripts modeling simple protocols using various encryption methods. The protocols include roles for a client and a server, along with the necessary setup for encryption and decryption.
# Encryption Protocol Simulations using Scyther

This repository contains Scyther scripts modeling simple protocols using various encryption methods. The protocols include roles for a client and a server, along with the necessary setup for encryption and decryption.

## Encryption Methods

The following encryption methods are modeled in this repository:

1. AES (Advanced Encryption Standard):
   - A symmetric encryption algorithm widely used across the globe.
   - Involves key exchange, encryption, and decryption processes.

2. 3DES (Triple Data Encryption Standard):
   - An enhancement of the original DES algorithm that applies the encryption process three times.
   - Provides better security compared to DES.

3. Blowfish:
   - A symmetric-key block cipher designed for fast performance.
   - Known for its simplicity and effectiveness.

4. RSA (Rivest-Shamir-Adleman):
   - An asymmetric encryption algorithm used for secure data transmission.
   - Involves the generation of public and private keys, key exchange, encryption, and decryption processes.

5. AES-ECDH (AES with Elliptic Curve Diffie-Hellman):
   - Combines AES for encryption and ECDH for key exchange.
   - Ensures secure key exchange and data encryption.

6. AES-ECC (AES with Elliptic Curve Cryptography):
   - Combines AES for encryption and ECC for key exchange.
   - Provides a secure method for key exchange and data encryption using elliptic curve cryptography.
  
   7- DES

## Files

Each encryption method is represented by a separate Scyther script:

- `AESProtocol.spdl`: AES encryption protocol.
- `TripleDESProtocol.spdl`: 3DES encryption protocol.
- `BlowfishProtocol.spdl`: Blowfish encryption protocol.
- `RSAProtocol.spdl`: RSA encryption protocol.
- `AESECDHProtocol.spdl`: AES-ECDH encryption protocol.
- `AESECCProtocol.spdl`: AES-ECC encryption protocol.

## Usage

To run the encryption protocol simulations using Scyther, follow these steps:

1. Install Scyther:
   - Download and install Scyther from [Scyther's official website](https://people.cispa.io/cas.cremers/scyther/).

2. Load the Script:
   - Open Scyther and load the desired script file.

3. Run the Analysis:
   - Run the analysis in Scyther to check for any security vulnerabilities or property violations.

## Example Scyther Script

Each script models the encryption and decryption processes in a symbolic manner, focusing on verifying the security properties of the protocol rather than performing actual cryptographic operations.



## Acknowledgements

- Scyther tool for formal analysis of security protocols.
- The authors of the respective encryption algorithms.



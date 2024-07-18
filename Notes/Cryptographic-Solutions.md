Cryptography - Practice and study of writing and solving codes to hide the rue meaning of the information  
Encryption - Process of converting ordinary information (plaintext) into an unintelligible form (ciphertext)  
Key - Essential piece of information that determines the output of a cipher  

Symmetric Algorithms - Use the same key for both encryption and decryption  
Asymmetric Algorithms - Use a pair of keys, a public key for encryption  and a private key for decryption  
Steganography - The practice of hiding secret data within ordinary, non-secret files or messages to avoid detection  
Tokenization - Substitutes sensitive data elements with non-sensitive equivalents called tokens  
Data Masking/Data Obfuscation - Process of disguising original data to protect sensitive information while maintaining its authenticity and usability  

Symmetric Algorithm - Encryption algorithm in which both the sender and the reciever must know the same shared secret using a privately held key  
Asymmetric Algorithm - (Public Key) - Encryption algorithm where diffferent keys are used to encrypt and decrypt the data  
Hybrid Implementation - Utilizes asymmetric encryption to securly transfer a private key that can then be used with symmetric encryption  
Stream Cipher - Utilizes a keystream generator to encrypt data bit by bit using a mathematical XOR function to create the ciphertext  
Block Cipher - Breaks the input into fixed-length blocks of data and performs the encryption on each block  

Symmetric Algorithms  
Data Encryption Standard (DES) - Encryption algorithm which breaks the input into 64-bit blocks (block) and uses transposition and substitution to create ciphertext using an effective key strength of only 56-bits  
Triple DES (3DES) - Encryption algorithm which uses three separate symmetric keys to encrypt, decrypt,then encrypt the plaintext into ciphertext using 3 different keys in order to increase the strength of DES  
International Data Encryption Algorithm (IDEA) - Symmetric block cipher which uses 64-bit blocks to encrypt plaintext into ciphertext  
Advances Encryption Standard (AES) - Symmetric block cipher that uses 128-bit, 192-bit, or 256-bit blocks and a matching encryption key size to encrypt plaintedxt into ciphertext  
Blowfish - Symmetric block cipher that uses 64-bit blocks and a variable length encryption key to encrypt plaintext into ciphertext  
Twofish - Provides the ability to use 128-bit blocks in its encryption algorithm and uses 128-bit, 192-bit, or 256-bit encryption keys  
RC Cipher Suite - Created by Ron Rivest, a cryptographer who's created six algorithms under the name RC which stands for the Rivet Cipher  
&nbsp;&nbsp;&nbsp;&nbsp;RC4 - Symmetric stream cipher using a variable key size from 40-bits to 2048-bits that is used in SSL and WEP  
&nbsp;&nbsp;&nbsp;&nbsp;RC5 - Symmetric block cipher that ses key sizes up to 2048-bits  
&nbsp;&nbsp;&nbsp;&nbsp;RC6 - Symmetric block cipher that was introduced as a replacement for DES but AES was chosen instead  

Asymmetric Algorithms  
Digital Signature - A hash digest of a message encrypted with the sender's private key to let the recipient know the document was created and sent by the person claiming to have sent it  
Diffie-Hellman (DH) - Used to conduct key exhanges and secure key distribution ove an unsecure network - used for the key exchange inside of creating a VPN tunnel  
RSA (Rivest, Shamir, and Adleman) - Asymmetric algorithm that relies on the mathematical difficulty of factoring large prime numbers  
Elliptic Curve Cryptography (ECC) - Heavily used in mobile devices and it's based on the algebraic structure of elliptical curves over finite fields to define its keys  
&nbsp;&nbsp;&nbsp;&nbsp;Elliptic Cuve Diffie-Hellman (ECDH) - ECC version of the popular Diffie-Hellman key exchange protocol  
&nbsp;&nbsp;&nbsp;&nbsp;Elliptic Curve Diffie-Hellman Ephemeral (ECDHE) - Uses a different key for each portion of the key establishment process inside the Diffie-Hellman key exchange  
&nbsp;&nbsp;&nbsp;&nbsp;Elliptic Curve Digital Signature Algorithm (ECDSA) - Used as a public key encryption algorithm by the US Government in their digital signatures  

Hashing - One-way cryptographic function that takes an input and produces a unique message digest as its output  
MD5 - Creates a 128-bit hash value that is unique to the input file  
SHA-1 - Creates a 160-bit hash digest, which significantly reduces the number of collisions that occur  
SHA-2 - Family of hash functions that contain longer hash digests (224, 256, 384, 512)  
SHA-3 - Newer family of hash functions, and its hash digest can go between 224 and 512 bits  
RIPEMD (REACE Integrity Primitice Evaluation Message Digest) - Comes in 160, 256, and 320-bit verisons  
RIPEMD-160 - Open-soource hashing algorithm that was created as a competitor to the SHA family  
HMAC (Hash-based Message Authentication Code) - Used to check the integrity of a message and provides some level of assurance that its authenticity is real  
Digital Security Standard (DSS) - Relies upon a 160-bit message digest created by the Digital Security Algorithm  

Pass the Hash Attack - Hacking technique that allows the attacker to authenticate to a remote server or service by using the underlying hash of a user's password instead of requiring the associated plaintext password  
Mimikatz - Provides the ability to automate the process of harvesting the hashes and conducting the attack  
Birthday Attack - Occurs when an attacker is able to send two different messages through a hash algorithm and it results in the same identitcal hash digest, reffered to as a collision  
Key Stretching - Technique that is used to mitigate a weaker key be increasing the time needed to crack it  
Salting - Adding random data into a one-way cryptographic hash to help protect against password cracking techniques  
Dictionary Attack - Use every word from a word list to attack a hash  
Brute-Force - Tries every possible comination  
Rainbow Tables - Precomputed tables for reversing cryptographic hash functions  
Nonce - Stands for "number used once", is a unique, often random number that is added to password-based authentication process  

Public Key Infrastructure (PKI) - An entire system of hardware, software, policies, procedures, and people that is based on asymmetric encryption - creates the asymmetric key pairs that consist of those public and private keys  
Framework for managing didgital keys and certificates that facilitate secure data transfer, authentication, and ecrypted communications over networks  
Certificate Authority - Issues digital certificates and keeps the level of trust between all of the certificate authorities around the world  
Key Escrow - Process where cryptographic keys are stored ina secure, third-party location, which is effectively an "escrow"  
Digital Certificate - Digitally signed electronic document that binds a public key with a user's identity  


Digital Certificates  
Wildcard Certificate - Allows all of the subdomains to use the same public key certificate and have it displayed as valid  
&nbsp;&nbsp;&nbsp;&nbsp;Subject Alternate Name (SAN) field - Certificate that specifies what additional domains and IP addresses are going to be supported  
Single-sided Certificate - Only requires the server to be validated  
Dual-Sided Certificate - Requires both the server and the user to be validated  
Self-signed Certificate - Digital certificate that is signed by the same entity whose identity it certifies  
Third-party Certificate - Digital certificate issues and signed by a trusted certificate authority  
Root of Trust - Each certificate is validated using the concept of a root of trust or the chain of trust  
Certificate Authority - Trusted third party who is going to issue these digital certificates  
Registration Authority - Requests identifying information from the user and forwards that certifiate request up to the certificate authority to create the digital certificate  
Certificate Signing Request - A block of encoded text that contains information about the entity requesting the certificate  
Certificate Revocation List - Serves as an online list of digital certificates that the certificate authority has already revoked  
OCSP - Allows to determine the revocation status of any digital certificate using its serial number  
OCSP Stapling - Allows the certificate holder to get the OCSP record from the server at regular intervals  
Public Key Pinning - Allows an HTTPS website to resist impersonation attacks from users who are trying to present fraudulent certificates  
Key Escrow - Occurs when a secure copy of a user's private key is being held  
Key Recovery Agent - Specialized type of software that allows the restoration of a lost or corrupted key to be performed  

Blockchain - A shared immutable ledger for recording transactions, tracking assets, and building trust  
Public Ledger - A record-keeping system that maintains participants' identities in a secure and anonymous format  
Smart Contracts - Self-executing contracts where the terms of agreement or conditions are written directly into lines of code  
Permissioned Blockchain - Used for buiness transactions and it promotes new levels of trust and transparency using this immutable public ledgers  

Trusted Platform Module (TPM) - Dedicated microcontroller designed to secure hardware through integrated cryptographic keys  
Hardware Security Module (HSM) - Physical device that safeguards and manages digital keys, primarily used for mission-critical situations like financial transactions  
Key Management System - Integrated approach for generating, distributing, and managing cryptographic keys for devices and applications  
Secure Enclave - Co-processor integrated into the main processor of some devices, designed with the sole purpose of ensuring data protection  

Steganography - Derived from Greek words meaning "covered writing", and it is all about concealing a message within another so that the very existence of the message is hidden  
Tokenization - Transformative technique in data protection that involves substituting sensitive data elements with non-sensitive equivalents, called tokens, which have no meaningful value  
Data Masking - Used to protect data by ensuring that it remains recognizable but does not acutally include sensitive information  

Cryptographic Attacks - Techniques and strategies that adversaries employ to exploit vulnerabilities in cryptographic systems with the intent to compromise the onfidentiality, integrity, or authenticity of data  
&nbsp;&nbsp;&nbsp;&nbsp;Downgrade Attack - Aims to force a system into using a weaker or older cryptographic standard or protocol than what it's currently utilizing  
&nbsp;&nbsp;&nbsp;&nbsp;Collision Attack - Aims to find two different inputs that produce the same hash output  
&nbsp;&nbsp;&nbsp;&nbsp;Quantum Computing - A computer taht uses quantum mechanics to generate and manipulate quantum bite (qubits) in order to access enormous processing powers  
&nbsp;&nbsp;&nbsp;&nbsp;Quantum Communication - A communicaitons network that relies on qubits made of photons (light) to send multiple combinations of ones and zeros simultaneously which results in tamper resistant and extremely fast communications  
&nbsp;&nbsp;&nbsp;&nbsp;Qubit - A quantum bit composed of electrons or photons that can represent numberous combinations of ones and zeros at the same time through superposition  
&nbsp;&nbsp;&nbsp;&nbsp;Post-quantum Cryptography - A new kind of cryptographic algorithm that can be implemented using today's classical computers but is also impervious to attacks from future quantum computers  

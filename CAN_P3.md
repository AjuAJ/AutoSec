
### **Your Objective**: 
The goal of this challenge is to turn on the vehicle's LED, but the communication is encrypted, adding a layer of complexity. To succeed, you must identify the algorithm and the mode used. And then encrypt the message accordingly

# Libs to be installed in ardunio 
- CAN by Sandeep Mistry
- Crypto by Rhys Weatherley

# Challenge Breakdown

1. **Encrypted Communication**
   - The vehicle's system uses encrypted messages to ensure secure communication.
   - Your first task is to identify the encryption algorithm (e.g., AES, DES) and the encryption mode (e.g., CBC, ECB) protecting the data.
   - Encryption algorithm's DID - 0xAB 0xCD
   - Mode of encryption's DID - 0xEF 0xEF

2. **Seed and Response Mechanism**
   - Once you understand the encryption process, you’ll need to encrypt a command using the correct algorithm and mode.
   - The command must be formatted according to the UDS (Unified Diagnostic Services) protocol and encrypted to match the system's expectations.
   - Key to encrypt the data - {0x2b, 0x7e, 0x15, 0x16, 0x28, 0xae, 0xd2, 0xa6, 0xab, 0xf7, 0x97, 0x75, 0x46, 0x4b, 0x32, 0x58};

3. **UDS Protocol Interaction**
   - The system communicates using UDS, which defines standard read (0x22) and write (0x2E) services.
   - You must use these services to send a properly encrypted command to turn on the LED.
   - The write command for controlling the LED includes a specific Data Identifier (DID) and data payload.
   - LED's DID - 0xA5 0xA5
   - Data Payload to turn on the LED - 0x43 0x21

4. **Solving the Puzzle**
   - Successfully decrypting the initial messages and encrypting your command proves your understanding of secure communication.
   - Sending the correct encrypted message will result in the LED being turned on, marking the challenge as complete.
   

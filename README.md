# The Matrix Hackathon: Red Pill vs Blue Pill

Welcome, Agent! You're at a crossroads. You must choose your path carefully, as each leads to a different world of hacking challenges. 

Do you want to take the **Red Pill** and dive into the deep, secure world of **CAN bus systems** and automotive network hacking? Or will you take the **Blue Pill** and explore the world of **Wi-Fi** and **Bluetooth** vulnerabilities in modern car systems?

---
## 🤖 **Choose Your Path:**

### 🌹 **Red Pill: CAN Bus Hacking (Automotive Systems)**

By choosing the **Red Pill**, you will enter the world of **automotive systems** and **Controller Area Network (CAN)**, where you'll manipulate critical car systems to gain control of the vehicle. These challenges require an understanding of Basic CAN protocol, Basic Ardiuno programming, UDS (Unified Diagnostics Services) and of course Security.

#### **Challenges:**

1. **Problem 1: Hack the CAN Bus**
   - Your mission is to infiltrate a vehicle's **CAN bus** and gain control over its electronic components, like the engine or door locking systems. The goal of this challenge is to intercept and manipulate unprotected communication between 2 ECUs to turn the LED ON, demonstrating the risks of unsecured systems.
   - Tools Required: **Arduino**
   - UNO and Driver: https://daimler.sharefile.eu/d-sd25737c608ed459bb01ca121f708c7ef (Due to limited laptops, we request the participants to download the IDE and drivers on your laptops)
2.  **Problem 2: Secured Access**
   - The challenge involves solving a cryptographic handshake by responding correctly to a random seed. Once unlocked, you'll use UDS commands to retrieve a hidden key, proving your success.
   - Tools Required: **Arduino**
   - UNO and Driver: https://daimler.sharefile.eu/d-sd25737c608ed459bb01ca121f708c7ef (Due to limited laptops, we request the participants to download the IDE and drivers on your laptops)
3.  **Problem 2: Secured Communication**
   - The challenge involves decrypting and re-encrypting messages to interact with a vehicle's system, which uses UDS protocols. You'll need to identify the encryption algorithm protecting the data before sending valid commands. Once the encryption is cracked, you can send the correct message to control the system and turn on the LED.
   - Tools Required: **Arduino**
   - UNO and Driver: https://daimler.sharefile.eu/d-sd25737c608ed459bb01ca121f708c7ef (Due to limited laptops, we request the participants to download the IDE and drivers on your laptops)
---

### 🔵 **Blue Pill: Wi-Fi & Bluetooth Hacking (Wireless Communication)**

The **Blue Pill** represents the world of **modern connectivity**. You'll focus on breaking into **Wi-Fi** and **Bluetooth** systems, where vehicles communicate wirelessly with phones, sensors, and other devices. Hack into these systems and you could gain control of the vehicle's critical functions.

#### **Challenges:**

1. **Problem 1: Extract Wi-Fi Credentials**
   - Your task is to gain access to the **vehicle's secure Wi-Fi network**. Using  wireless sniffing techniques, you'll extract the credentials, allowing you to connect to the vehicle’s network and retrieve critical information.
   - Tools Required: **Wireshark**, **nmap**, **Linux**
  
2. **Problem 2: Attack Wi-Fi Networks**
   - In this challenge, you'll be tasked with **Attacking Open Wi-Fi Networks**. Using network enumeration and monitoring techniques, you have to exploit the vulnerabilities and get access to confidentail information.
   - Tools Required: **Wireshark**, **nmap**, **Linux**

3. **Problem 3: Hijack Bluetooth Communication**
   - In this challenge, you'll be tasked with **hijacking Bluetooth communication** between two ECUs. Once inside, you can control functions such as the engine start/stop or even manipulate the car's dashboard displays.
   - Tools Required: **Linux**

---

### 📢 **Rules and Guidelines**

1. **Tools**: You will be given access to certain tools and hardware (Linux Machine, Wireshark, Arduino etc.), depending on the path you choose. You are also free to use Google, MB GenAI (https://genai.app.corpintra.net/chat/gpt-4o) or Chatgpt at any point of time.
2. **Path**: You have the freedom to switch between paths at any time during the challenge.
3. **Time Limit**: The hackathon will last for **10 hours**. Complete as many challenges as you can in the time provided.
3. **Collaboration**: While the challenges are designed for individual teams, feel free to collaborate and discuss problems with other team members.
4. **Judging**: Submissions will be judged based on **creativity**, **complexity**, and **effectiveness** in solving the challenges.
5. **Safety**: Please ensure that all actions are performed ethically and legally. Avoid damaging any systems or breaching any real-world security without authorization.
6. **Hardware Safety**: Please make sure you do not damage the hardware, for ex. never short the VCC and GND of any microcontroller unit. When in doubt, call for help!

---

### 🚀 **Get Started:**

Once you've selected your path, you will be provided with all necessary instructions, challenges, and tools for your chosen set. Remember, time is of the essence, so make your choice wisely.

Good luck, Agent. The future of the vehicle's security rests in your hands!

---

*Presented by: Your Hackathon Team*

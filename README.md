# SpectreSec
SOC -Chatbot
SpectreSec is a cutting-edge SOC tool designed to enhance security operations by providing seamless integration with Twilio for real-time communication. This tool is tailored for security analysts to monitor, analyze, and respond to incidents with agility and precision.

# Features:
- Twilio Integration: Sends alerts via SMS using Twilio's API.
- Real-Time Monitoring: Continuously monitors specified logs and events.
- User-Friendly: Designed with ease of use in mind, ensuring quick setup and deployment.

  ## Installation:

1.  Clone the Repository: 

---    
    git clone https://github.com/Drashta03/SpectreSec.git
    cd SpectreSec

---

2.  Install Dependencies:

---
      pip install -r requirements.txt
---

3.  Set Up Environment Variables: Create a .env file in the root directory and add your Twilio credentials

 ---

      TWILIO_ACCOUNT_SID=your_account_sid
      TWILIO_AUTH_TOKEN=your_auth_token
      TWILIO_PHONE_NUMBER=your_twilio_number
      RECIPIENT_PHONE_NUMBER=your_phone_number

 ---

4.  Run the Tool:

---

       python3 app.py

 
---


  

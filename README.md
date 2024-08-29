# SpectreSec

SpectreSec is a powerful SOC tool designed exclusively for Linux environments. It helps security analysts monitor logs in real-time and sends alerts via Twilio SMS when specific security events are detected. Additionally, it integrates with `ngrok` to expose your local server to the internet securely.

## Features

- **Twilio Integration**: Sends real-time SMS alerts for critical events.
- **Log Monitoring**: Continuously scans logs for potential security threats.
- **Ngrok Integration**: Securely expose local servers to the internet.
- **Linux-Only**: Specifically designed to run on Linux environments.

## Installation

1. **Clone the Repository**:
    ```bash
   git clone https://github.com/Drashta03/SpectreSec.git
   cd SpectreSec

2. **Install Dependencies: Install the required Python packages using pip**:
    ```bash
   pip install -r requirements.txt

3. **Install Ngrok: Download and set up ngrok**:
   
     ```bash
    wget https://bin.equinox.io/c/4VmDzA7iaHb/ngrok-stable-linux-amd64.zip
    unzip ngrok-stable-linux-amd64.zip
    sudo mv ngrok /usr/local/bin/ngrok
4. **Set Up Environment Variables: Create a .env file in the root directory and add your Twilio credentials**:
   
    ```bash
   TWILIO_ACCOUNT_SID=your_account_sid
   TWILIO_AUTH_TOKEN=your_auth_token
   TWILIO_PHONE_NUMBER=your_twilio_number
   RECIPIENT_PHONE_NUMBER=your_phone_number

 Replace the placeholders with your actual Twilio credentials and phone numbers.


## Usage

To start using SpectreSec, first, set up ngrok and then run the app.py script. The tool will monitor specified logs and send SMS alerts to your configured phone number when significant events are detected.

## Running Ngrok

  **Start ngrok to expose your local server**:
  
    ngrok http 5000

## Running SpectreSec

    python3 app.py


## Fun Fact 😒

Even the best security systems are only as strong as their weakest link. Stay sharp, and keep your skills honed!


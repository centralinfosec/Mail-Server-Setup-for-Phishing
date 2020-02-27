# Mail Server Setup for Phishing (PhishServ)

PhishServ is a penetration testing and red teaming tool that automates the setup of a mail server allowing restricted relaying.

## Installation

Clone the GitHub repository
```
git clone https://github.com/centralinfosec/Mail-Server-Setup-for-Phishing /opt/Central-InfoSec/Mail-Server-Setup-for-Phishing
```

## Usage

 - Update the domain, email, and IP in "/opt/Central-InfoSec/Mail-Server-Setup-for-Phishing/createMailServerWithRelay.sh"
 - Create the mail server by running the following commands:
```
chmod +x /opt/Central-InfoSec/Mail-Server-Setup-for-Phishing/createMailServerWithRelay.sh
/opt/Central-InfoSec/Mail-Server-Setup-for-Phishing/createMailServerWithRelay.sh
```

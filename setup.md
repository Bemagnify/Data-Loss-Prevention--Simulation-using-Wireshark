### How to Setup and Run the Project
1. Install XAMPP
Download from: https://www.apachefriends.org/
Install and run Apache server.

2. Create Project Folder

C:\xampp\htdocs\
Create a folder:

dlp-simulation
Add the following PHP files:

1. sensitive_data.php #code in repo
2. receiver.php #code in repo

### Running the Application
Start Apache from XAMPP Control Panel.

Visit in your browser:

http://localhost/dlp-simulation/sensitive_data.php

Click Submit.

### Capturing Sensitive Data with Wireshark
Open Wireshark.

Select your active interface (WiFi or Ethernet).

Start Capture.

Apply Display Filter to search sensitive data:

tcp contains "username="
tcp contains "password="
tcp contains "creditcard="
tcp contains "email="

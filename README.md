# Email-Sender-smtplib-
# Email Sender Script

## Description
This **Python script** allows users to send an email via **Gmail** using the SMTP protocol. It is a simple implementation to send plain-text emails by securely authenticating with the sender's Gmail account using an **App Password**.

---

## Features
- **Send Emails**: Sends plain-text emails to any valid email address.
- **SMTP Authentication**: Uses Gmail's SMTP server for secure email transmission.
- **User Input**: Collects sender's credentials, recipient email, subject, and message from the user.

---

## Requirements
### Prerequisites
1. **Python**: Version 3.x or above.
2. **Required Libraries**: 
   - `smtplib`
   - `email`
   These libraries are part of Python's standard library, so no extra installations are required.

3. **Gmail App Password**:
   - Gmail requires App Passwords for third-party apps.
   - To generate an App Password:
     1. Go to your **Google Account Settings**.
     2. Enable **2-Step Verification**.
     3. Navigate to **Security > App Passwords**.
     4. Generate a 16-character App Password for your script.

---

## How to Use
1. **Save the script**:
   - Copy the code into a file, e.g., `email_sender.py`.

2. **Run the Program**:
   - Open a terminal or command prompt.
   - Navigate to the directory containing the script.
   - Run the program:
     ```bash
     python email_sender.py
     ```

3. **Provide Required Inputs**:
   - Enter your email address (sender's Gmail address).
   - Enter your **App Password** (not your Gmail password).
   - Enter the recipient's email address.
   - Enter the subject of the email.
   - Enter the message you want to send.

4. **Email Sent Confirmation**:
   - If successful, the script will display:
     ```
     Email sent successfully!
     ```

---

## Example Usage
```
Enter your email address: your_email@gmail.com
Enter your App Password: xxxxxxxxxxxxxxxx
Enter the recipient's email address: recipient_email@example.com
Enter the subject of the email: Greetings
Enter the message: Hello! This is a test email.

Email sent successfully!
```

---

## Customization
- **SMTP Server**: The default SMTP server is `smtp.gmail.com`. If you're using a different email provider, modify the `smtp_server` and `smtp_port` variables in the script.
- **Email Content**: The script currently sends plain-text emails. You can modify it to send HTML emails or include attachments using `MIMEText` or `MIMEBase`.

---

## Error Handling
- The script provides basic error messages in case of issues like:
  - Incorrect credentials (email or App Password).
  - Invalid recipient email address.
  - Network or server connectivity issues.

---

## Limitations
- **Gmail Only**: The script is designed for Gmail. For other email providers, you may need to adjust the SMTP server and port.
- **Plain-Text Only**: Currently, the email message supports only plain text.

---

## License
This script is open-source and can be used or modified for personal or educational purposes.

---

Let me know if you have any questions or need help with this script!

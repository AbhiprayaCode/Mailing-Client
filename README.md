# 📧 Python Email Sender

A simple Python script to send emails with attachments using Gmail's SMTP server. This project demonstrates how to automate email sending with Python's built-in `smtplib` and `email` libraries.[pyOpenSci+11GitHub+11Real Python+11](https://github.com/Sven-Bo/automate-sending-emails-using-python/blob/master/README.md?utm_source=chatgpt.com)[GitHub](https://github.com/Akshatbhatnagar908/mail_sending_python?utm_source=chatgpt.com)

* * *

## 🚀 Features

*    Send plain text emails  
*    Attach files (e.g., images, documents)    
*    Utilize Gmail's SMTP server with STARTTLS    
*    Secure password handling via external file[DEV Community+4Wikipedia+4Real Python+4](https://en.wikipedia.org/wiki/README?utm_source=chatgpt.com)    

* * *

## 🛠️ Prerequisites

*    Python 3.x
*    A Gmail account
*    An application-specific password (if 2FA is enabled)   

* * *

## 📂 Project Structure

*    `main.py`: Main script to send the email
*    `password.txt`: Contains your Gmail password or app-specific password    
*    `message.txt`: Email body content
*    `example.png`: File to be attached[UMA Technology+8GitHub+8Wikipedia+8](https://github.com/Akshatbhatnagar908/mail_sending_python?utm_source=chatgpt.com)[GitHub+7Make a README+7UMA Technology+7](https://www.makeareadme.com/?utm_source=chatgpt.com)[pyOpenSci+6GitHub+6pyOpenSci+6](https://github.com/jehna/readme-best-practices?utm_source=chatgpt.com)    

* * *

## ⚙️ Setup & Usage

1. **Clone the Repository**

     `git clone https://github.com/yourusername/python-email-sender.git cd python-email-sender`     

2. **Prepare `password.txt`**
     Create a file named `password.txt` and paste your Gmail password or app-specific password into it. Ensure there's no extra whitespace.

3.  **Write Your Message**

     Edit `message.txt` to include the content you want in the email body.

4.  **Add an Attachment**

     Place the file you wish to attach (e.g., `example.png`) in the project directory.
     
5.  **Run the Script**
          
     `python main.py`     

* * *

## 🔐 Security Note

For enhanced security, especially if you have two-factor authentication (2FA) enabled on your Gmail account, it's recommended to use an [App Password](https://support.google.com/accounts/answer/185833?hl=en) instead of your regular password.

* * *

## 📝 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

* * *

## 🙌 Acknowledgments

Inspired by the need to automate email sending tasks using Python's standard libraries.
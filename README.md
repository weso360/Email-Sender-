
# Thixo Email Sender

This script sends HTML emails to multiple recipients using Python's `smtplib` library.

## What the Code Does

The script performs the following steps:

1. Reads email addresses from a CSV file named `emails.csv`.
2. Configures the SMTP server details (hostname, port, username, password) and email content (sender's email address, subject, HTML body).
3. Connects to the SMTP server using SSL.
4. Iterates through each recipient email address.
5. Constructs an HTML email message with the specified subject and body.
6. Sends the email to each recipient using the SMTP server.
7. Prints a message indicating whether the email was successfully sent or if there was an error.

## Usage

1. Prepare a CSV file named `emails.csv` containing the email addresses of the recipients, with each email address on a separate line.
2. Customize the script with your SMTP server details (`SMTP_SERVER`, `SMTP_PORT`, `SMTP_USERNAME`, `SMTP_PASSWORD`) and email content (`FROM_EMAIL`, `SUBJECT`, `BODY`).
3. Run the script:
   ```
   python script.py
   ```

---

Feel free to customize the README further to include additional details or instructions specific to your project.

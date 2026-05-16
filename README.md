# README — Task 2 (Gmail Email Reader)

```markdown
# Gmail Email Reader

A Spring Boot application that connects with Gmail using Gmail API and fetches the latest 200 emails.

The application displays:
- Sender Name
- Email Subject

---

## Features

- Gmail API integration
- OAuth 2 authentication
- Fetch latest 200 emails
- Display sender and subject
- Spring Boot backend implementation

---

## Technologies Used

- Java 17
- Spring Boot
- Gmail API
- OAuth 2.0
- Maven
- Lombok

---

## Project Structure

src/main/java/com/bxp/gmail_email_reader
│
├── gmail
│   ├── GmailService.java
│   └── GmailRunner.java

---

## Gmail API Setup

1. Create Google Cloud Project
2. Enable Gmail API
3. Configure OAuth Consent Screen
4. Create OAuth Client ID
5. Download credentials.json
6. Place credentials.json inside:

```text

src/main/resources/
________________________________________
Dependencies Used
•	google-api-client
•	google-oauth-client-jetty
•	google-api-services-gmail
________________________________________
Sample Output

FROM : Amazon
SUBJECT : Your Order Has Been Shipped

FROM : LinkedIn
SUBJECT : Java Developer Jobs Recommended For You
________________________________________
How To Run
1.	Configure Gmail API credentials
2.	Place credentials.json in resources folder
3.	Run application
4.	Login to Gmail when browser opens
5.	Allow permissions
6.	Console displays latest 200 emails
________________________________________
Build JAR

./mvnw clean package
Generated JAR file will be inside:

target/
________________________________________
Important Note
Do NOT upload:

credentials.json
tokens/
These contain sensitive OAuth credentials.
________________________________________
Author
POORNA CHANDRA GANESH M ```

# password-checker
This project is a Python-based command-line tool designed to check whether passwords have been compromised in known data breaches. By leveraging the Have I Been Pwned API, the tool ensures users can verify their passwords' security without compromising their privacy.

Key features of the project include:

- API Integration: The program integrates with the Have I Been Pwned API to check whether a given password has been exposed in any public data breaches. By querying the API securely, the tool ensures user privacy is maintained.
- Password Hashing: The program uses SHA-1 hashing to convert passwords into a secure format before transmitting only the first five characters of the hash to the API, preventing the full password from being exposed during the query.
- Efficient Data Parsing: The tool processes the API response efficiently, parsing through hash ranges to check if the given password has been compromised.
- Command-Line Interface: Users can pass multiple passwords through the command line, making it easy to check the security status of several passwords in one go.
- Real-Time Feedback: The tool provides immediate feedback, alerting users whether a password has been found in breaches and recommending whether it should be changed.

This project showcases my ability to integrate external APIs, implement secure password hashing methods, and develop real-time tools that prioritize user security. It also highlights my expertise in Python programming and data processing.

# AES-encrypted-hyperlinks
This program encrypts hyperlinks with a salted AES 256 and produces a data URL that will decrypt and follow the hyperlink provided the correct password is entered.

# Usage
1. Open the html file in a web browser.
2. In the prompt box enter the url in this format:

         RIGHT = https://www.examplesite.com http://www.examplesite.com
         
         WRONG = www.example.com
         
3. Enter a GOOD password.
4. The page will generate a data URL that can be copied into the URL bar and run.

# note
Data urls have been limited by web browsers as they were perceived to be a security threat to people who were unaware that they can run code and can no longer just be clicked.

firefox - Must be copied into url bar

chrome  - Must be copied into url bar OR right-click new-tab

opera   - Must be copied into url bar OR right-click new-tab

IE      - No support

Edge    - Unknown if supported

Safari  - Unknown if supported



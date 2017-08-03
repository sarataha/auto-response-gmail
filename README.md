# Automated response for Gmail
 
 A simple automated response tool for Gmail. The tool responds to emails based on the sender.
 
 Used:
 * Python
 * Selenium

 Required:
 
 [chromedriver](https://chromedriver.storage.googleapis.com/index.html?path=2.31/)
 
 You need to edit the following lines with your own information
 
 Add the path to your chromedriver
 ```
 chromedriver = r'<Path to Chrome Driver>'
 ```
 
 Add the name of the sender
 ```
 SENDER = '<SENDER NAME>'
 ```
 
 Add your Gmail details
 ```
 GMAIL_USER = '<Your Gmail ID>'
 GMAIL_PASSWORD = '<Your Gmail ID>'
 ```
 
 Customize the automated email
 ```
 MESSAGE = 'I will get back to you soon. \n Thanks'
 ```
 
 Run
 ```
 python response.py
 ```
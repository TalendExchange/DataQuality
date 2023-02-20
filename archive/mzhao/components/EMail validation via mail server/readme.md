## <img src='./logo.jpg' width='40' height='40'>EMail validation via mail server

### Overview
This Java UDI check emails by sending a SMTP request to mail server. the code sample can be found at: http://www.rgagnon.com/javadetails/java-0452.html
### Images




#### Release Notes

##### 5.2.0M4 - 2012-08-29 08:47:54
Email validation java user define indicator.
##### 1.1beta - 2012-12-18 11:25:07
new improved beta version.
##### 5.2.2 - 2013-03-01 03:59:43
new version compatible with 5.2.1 and above only.
This version contains parameters for the 
- email of the sender (used for the smtp server check)
- a file path to the list of invalid emails
- a buffer size that gives the number of invalid email address store in memory before they are flushed in the file.

The parameters are the following ones:
EMAIL <set the sender email for tests here>
INVALID DATA FILE /tmp/invalid_email.txt
BUFFER SIZE 400
##### 5.2.1 - 2013-03-01 04:09:31
new version compatible with 5.2.1 and above only.
This version contains parameters for the 
- email of the sender (used for the smtp server check)
- a file path to the list of invalid emails
- a buffer size that gives the number of invalid email address store in memory before they are flushed in the file.

The parameters are the following ones:
EMAIL <set the sender email for tests here>
INVALID DATA FILE /tmp/invalid_email.txt
BUFFER SIZE 400
##### 5.1.3 - 2013-03-01 04:15:12
This version contains parameters for the
- email of the sender (used for the smtp server check)
- a file path to the list of invalid emails
- a buffer size that gives the number of invalid email address store in memory before they are flushed in the file.

The parameters are the following ones:
EMAIL <set the sender email for tests here>
INVALID DATA FILE /tmp/invalid_email.txt
BUFFER SIZE 400

### Compatible
 -  5.1 (obsolete)
 -   5.2 (obsolete)
# scorreia
  <http://scorreiait.wordpress.com/>
  <nospam+scorreia@talend.com>

## <a href='./components/Acronyms/readme.md'><img src='./components/Acronyms/logo.jpg' width='40' height='40'> Acronyms</a>
 :warning: Compatibility not known

identify text like "T.R.T." or "A.I.D.S."
will not match "SNCF" or "A.I"
<img src='./components/Acronyms/sample.jpg'>

## <a href='./components/Correctly Encoded Characters/readme.md'><img src='./components/Correctly Encoded Characters/logo.jpg' width='40' height='40'> Correctly Encoded Characters</a>
 :warning: Compatibility not known

Finds out any badly encoded character
<img src='./components/Correctly Encoded Characters/sample.jpg'>

## <a href='./components/delimited file format/readme.md'><img src='./components/delimited file format/logo.jpg' width='40' height='40'> delimited file format</a>
 :warning: Compatibility not known

check whether each row respect a simple delimited file format with 5 columns
<img src='./components/delimited file format/sample.jpg'>

## <a href='./components/Duplicate Rows/readme.md'><img src='./components/Duplicate Rows/logo.jpg' width='40' height='40'> Duplicate Rows</a>
 :white_check_mark: Compatible with Talend 7.x / 8.x 

this indicator counts the number of duplicate rows. 
It's different from the system indicator called "duplicate count" because it counts the number of duplicate rows, not the number of duplicate values. 
<img src='./components/Duplicate Rows/sample.jpg'>

## <a href='./components/Email Address (with list of top-level domains)/readme.md'><img src='./components/Email Address (with list of top-level domains)/logo.jpg' width='40' height='40'> Email Address (with list of top-level domains)</a>
 :warning: Compatibility not known

Check the validity of email addresses.
<img src='./components/Email Address (with list of top-level domains)/sample.jpg'>

## <a href='./components/email_indicator/readme.md'><img src='./components/email_indicator/logo.jpg' width='40' height='40'> email_indicator</a>
 :white_check_mark: Compatible with Talend 7.x / 8.x 

SQL like clause to demo the UDI drill down feature on email columns
<img src='./components/email_indicator/sample.jpg'>

## <a href='./components/Empty Text/readme.md'><img src='./components/Empty Text/logo.jpg' width='40' height='40'> Empty Text</a>
 :warning: Compatibility not known

Identify values with only whitespace characters.
Will matches values with only whitespace characters. Regexp class: [:space:]
<img src='./components/Empty Text/sample.jpg'>

## <a href='./components/FR Phone Number (parenthesis allowed)/readme.md'><img src='./components/FR Phone Number (parenthesis allowed)/logo.jpg' width='40' height='40'> FR Phone Number (parenthesis allowed)</a>
 :white_check_mark: Compatible with Talend 7.x / 8.x 

match French phone numbers in several format:
matches:
0033 1 47 25 00 00
+33 1 47 25 00 00
(33) 1 47 25 00 00
0033147250000
01-47-25-00-00
01 47 25 00 00
Does not match
0147 250 000
<img src='./components/FR Phone Number (parenthesis allowed)/sample.jpg'>

## <a href='./components/French date/readme.md'><img src='./components/French date/logo.jpg' width='40' height='40'> French date</a>
 :warning: Compatibility not known

matches French DateTime (DD/MM/YYYY or DD/MM/YYYY HH:MM:SS)

Matches  \t 12/01/2002 | 12/01/2002 12:32:10 
Non-Matches \t 32/12/2002 | 12/13/2001 | 12/02/06

<img src='./components/French date/sample.jpg'>

## <a href='./components/French phone number/readme.md'><img src='./components/French phone number/logo.jpg' width='40' height='40'> French phone number</a>
 :warning: Compatibility not known

Check the validity of FR phone numbers
Matches French phone numbers starting with 01, 02, 03, 04, 05, 06, 08 09 (e.g. 01-23-45-67-83 or 01.23.45.67.83 or 0123456783
<img src='./components/French phone number/sample.jpg'>

## <a href='./components/French Social Security number/readme.md'><img src='./components/French Social Security number/logo.jpg' width='40' height='40'> French Social Security number</a>
 :warning: Compatibility not known

Matches  \t
181049520156962 | 1 81 04 95 201 569 62 | 1 81 04 95 201 569
Non-Matches \t
1 81049520156962 | 181049520156962fds | 1810495201569ds
<img src='./components/French Social Security number/sample.jpg'>

## <a href='./components/French VAT number/readme.md'><img src='./components/French VAT number/logo.jpg' width='40' height='40'> French VAT number</a>
 :warning: Compatibility not known

VAT Numbers format verification (France) with support for optional member state definition.
Matches FRAB 123456789 | L7 123456789 
Non-Matches  \t 
FRAB123456789 | L7 L23456789

<img src='./components/French VAT number/sample.jpg'>

## <a href='./components/Frequency table of hours/readme.md'><img src='./components/Frequency table of hours/logo.jpg' width='40' height='40'> Frequency table of hours</a>
 :white_check_mark: Compatible with Talend 7.x / 8.x 

This indicator helps to analyze the most frequent day hours that appear in date time columns.
<img src='./components/Frequency table of hours/sample.jpg'>

## <a href='./components/Gender/readme.md'><img src='./components/Gender/logo.jpg' width='40' height='40'> Gender</a>
 :warning: Compatibility not known

Classic gender descriptor regular expression. 
Matches: F, M, Male, Female, male, female. 
Non-matches: mail, A, S

<img src='./components/Gender/sample.jpg'>

## <a href='./components/Hex Color Codes/readme.md'><img src='./components/Hex Color Codes/logo.jpg' width='40' height='40'> Hex Color Codes</a>
 :warning: Compatibility not known

Check hex codes used for HTML or CSS

Matches valid 3 or 6 character hex codes used for HTML or CSS. Matches fff | #990000 | #cc3366 | #AAAAAA Non-Matches #5555 | #ZJK000 | CDCDCDCD

<img src='./components/Hex Color Codes/sample.jpg'>

## <a href='./components/Home Row Text (Random Text)/readme.md'><img src='./components/Home Row Text (Random Text)/logo.jpg' width='40' height='40'> Home Row Text (Random Text)</a>
 :warning: Compatibility not known

Search random sequences with keys from the home row
<img src='./components/Home Row Text (Random Text)/sample.jpg'>

## <a href='./components/hotmail email/readme.md'><img src='./components/hotmail email/logo.jpg' width='40' height='40'> hotmail email</a>
 :warning: Compatibility not known

filters email from hotmail.com
<img src='./components/hotmail email/sample.jpg'>

## <a href='./components/Initial(s)/readme.md'><img src='./components/Initial(s)/logo.jpg' width='40' height='40'> Initial(s)</a>
 :warning: Compatibility not known

matches initials like "T.R.T" or "A.I.D.S." or "A" or "I."
<img src='./components/Initial(s)/sample.jpg'>

## <a href='./components/Initials/readme.md'><img src='./components/Initials/logo.jpg' width='40' height='40'> Initials</a>
 :warning: Compatibility not known

A regex to identify text composed of initials only
<img src='./components/Initials/sample.jpg'>

## <a href='./components/IP Address/readme.md'><img src='./components/IP Address/logo.jpg' width='40' height='40'> IP Address</a>
 :warning: Compatibility not known

Matches: IP addresses such as 10.62.268.9, 212.27.28.10
Non-matches: 345.2.2.3, 123.1.1.34.4

<img src='./components/IP Address/sample.jpg'>

## <a href='./components/ISO Week Number Frequency/readme.md'><img src='./components/ISO Week Number Frequency/logo.jpg' width='40' height='40'> ISO Week Number Frequency</a>
 :white_check_mark: Compatible with Talend 7.x / 8.x 

Computes the ISO week number frequency of a given date.

<img src='./components/ISO Week Number Frequency/sample.jpg'>

## <a href='./components/Length Range Frequency/readme.md'><img src='./components/Length Range Frequency/logo.jpg' width='40' height='40'> Length Range Frequency</a>
 :white_check_mark: Compatible with Talend 7.x / 8.x 

get length ranges of data.

group data according to their length range. 
Ranges are the following: 
data of length < 10
data of length < 20
data of length < 30
data of length >= 30
null data 
<img src='./components/Length Range Frequency/sample.jpg'>

## <a href='./components/Names with unicode characters/readme.md'><img src='./components/Names with unicode characters/logo.jpg' width='40' height='40'> Names with unicode characters</a>
 :warning: Compatibility not known

<img src='./components/Names with unicode characters/sample.jpg'>

## <a href='./components/Not Trimmed Text/readme.md'><img src='./components/Not Trimmed Text/logo.jpg' width='40' height='40'> Not Trimmed Text</a>
 :warning: Compatibility not known

This indicator computes the ratio of untrimmed text data (data which contain whitespace either at the beginning or at the end). 
<img src='./components/Not Trimmed Text/sample.jpg'>

## <a href='./components/Numeric/readme.md'><img src='./components/Numeric/logo.jpg' width='40' height='40'> Numeric</a>
 :warning: Compatibility not known

Matches all numbers
<img src='./components/Numeric/sample.jpg'>

## <a href='./components/Order of Magnitude/readme.md'><img src='./components/Order of Magnitude/logo.jpg' width='40' height='40'> Order of Magnitude</a>
 :warning: Compatibility not known

measure the order of magnitude of numerical data
<img src='./components/Order of Magnitude/sample.jpg'>

## <a href='./components/phone_area_code_freq/readme.md'><img src='./components/phone_area_code_freq/logo.jpg' width='40' height='40'> phone_area_code_freq</a>
 :white_check_mark: Compatible with Talend 7.x / 8.x 

Area codes of American phone numbers
<img src='./components/phone_area_code_freq/sample.jpg'>

## <a href='./components/Properties keys/readme.md'><img src='./components/Properties keys/logo.jpg' width='40' height='40'> Properties keys</a>
 :warning: Compatibility not known

Matches keys of java properties files.
<img src='./components/Properties keys/sample.jpg'>

## <a href='./components/Random email/readme.md'><img src='./components/Random email/logo.jpg' width='40' height='40'> Random email</a>
 :warning: Compatibility not known

detect random emails
<img src='./components/Random email/sample.jpg'>

## <a href='./components/Random Text/readme.md'><img src='./components/Random Text/logo.jpg' width='40' height='40'> Random Text</a>
 :warning: Compatibility not known

A pattern to match random text such as "mskjfdlmnjg" that sometimes appears in free text fields.
<img src='./components/Random Text/sample.jpg'>

## <a href='./components/Regular Text/readme.md'><img src='./components/Regular Text/logo.jpg' width='40' height='40'> Regular Text</a>
 :white_check_mark: Compatible with Talend 7.x / 8.x 

match regular text

matches regular text such as "hello Jean-Baptiste".
does not match text with any special character such as "# num", "test;"
<img src='./components/Regular Text/sample.jpg'>

## <a href='./components/Repeated Character/readme.md'><img src='./components/Repeated Character/logo.jpg' width='40' height='40'> Repeated Character</a>
 :warning: Compatibility not known

will find data such as "aaa"
<img src='./components/Repeated Character/sample.jpg'>

## <a href='./components/Sample Standard Deviation/readme.md'><img src='./components/Sample Standard Deviation/logo.jpg' width='40' height='40'> Sample Standard Deviation</a>
 :white_check_mark: Compatible with Talend 7.x / 8.x 

This indicator computes the sample standard deviation of any numerical column
<img src='./components/Sample Standard Deviation/sample.jpg'>

## <a href='./components/Standard Deviation (rounded)/readme.md'><img src='./components/Standard Deviation (rounded)/logo.jpg' width='40' height='40'> Standard Deviation (rounded)</a>
 :warning: Compatibility not known

computes the standard deviation (rounded to an integer).

<img src='./components/Standard Deviation (rounded)/sample.jpg'>

## <a href='./components/Starts with blank/readme.md'><img src='./components/Starts with blank/logo.jpg' width='40' height='40'> Starts with blank</a>
 :warning: Compatibility not known

detects data starting with blank characters
<img src='./components/Starts with blank/sample.jpg'>

## <a href='./components/Starts with spaces/readme.md'><img src='./components/Starts with spaces/logo.jpg' width='40' height='40'> Starts with spaces</a>
 :warning: Compatibility not known

detects whitespaces at the begining of a data
<img src='./components/Starts with spaces/sample.jpg'>

## <a href='./components/Temperature in Celsius/readme.md'><img src='./components/Temperature in Celsius/logo.jpg' width='40' height='40'> Temperature in Celsius</a>
 :white_check_mark: Compatible with Talend 7.x / 8.x 

Check that a given number is a valid temperature in Celsius.
<img src='./components/Temperature in Celsius/sample.jpg'>

## <a href='./components/test parser rule/readme.md'><img src='./components/test parser rule/logo.jpg' width='40' height='40'> test parser rule</a>
 :warning: Compatibility not known

this is a test only
<img src='./components/test parser rule/sample.jpg'>

## <a href='./components/Text/readme.md'><img src='./components/Text/logo.jpg' width='40' height='40'> Text</a>
 :white_check_mark: Compatible with Talend 7.x / 8.x 

Identify values with only whitespace characters.
Will matches values with only whitespace characters. Regexp class: [:space:]
<img src='./components/Text/sample.jpg'>

## <a href='./components/Trimmed/readme.md'><img src='./components/Trimmed/logo.jpg' width='40' height='40'> Trimmed</a>
 :white_check_mark: Compatible with Talend 7.x / 8.x 

This indicator computes the ratio of untrimmed text data (data which contain whitespace either at the beginning or at the end). 
<img src='./components/Trimmed/sample.jpg'>

## <a href='./components/Tweets/readme.md'><img src='./components/Tweets/logo.jpg' width='40' height='40'> Tweets</a>
 :white_check_mark: Compatible with Talend 7.x / 8.x 

get information from tweets.
Extract the date/time,  user, hashtags, referenced users and urls from Twitter messages.
<img src='./components/Tweets/sample.jpg'>

## <a href='./components/udi_average_yearly_income/readme.md'><img src='./components/udi_average_yearly_income/logo.jpg' width='40' height='40'> udi_average_yearly_income</a>
 :white_check_mark: Compatible with Talend 7.x / 8.x 

parses $50K - $70K and return the average value
<img src='./components/udi_average_yearly_income/sample.jpg'>

## <a href='./components/Unaccented Words/readme.md'><img src='./components/Unaccented Words/logo.jpg' width='40' height='40'> Unaccented Words</a>
 :white_check_mark: Compatible with Talend 7.x / 8.x 

<img src='./components/Unaccented Words/sample.jpg'>

## <a href='./components/US Phone number/readme.md'><img src='./components/US Phone number/logo.jpg' width='40' height='40'> US Phone number</a>
 :warning: Compatibility not known

Helps to filter US telephone numbers
Matches  \t(604) 789-0136 | +123-45678-908 
Non-Matches \t01.12.23  



<img src='./components/US Phone number/sample.jpg'>

## <a href='./components/US_customers_count/readme.md'><img src='./components/US_customers_count/logo.jpg' width='40' height='40'> US_customers_count</a>
 :white_check_mark: Compatible with Talend 7.x / 8.x 

Indicator to count the number of 'USA' values in country columns
<img src='./components/US_customers_count/sample.jpg'>

## <a href='./components/Variance/readme.md'><img src='./components/Variance/logo.jpg' width='40' height='40'> Variance</a>
 :white_check_mark: Compatible with Talend 7.x / 8.x 

This indicator computes the variance of numeric columns
<img src='./components/Variance/sample.jpg'>

## <a href='./components/Week Frequency/readme.md'><img src='./components/Week Frequency/logo.jpg' width='40' height='40'> Week Frequency</a>
 :warning: Compatibility not known

aggregates Date fields into weeks
<img src='./components/Week Frequency/sample.jpg'>

## <a href='./components/Words/readme.md'><img src='./components/Words/logo.jpg' width='40' height='40'> Words</a>
 :white_check_mark: Compatible with Talend 7.x / 8.x 

<img src='./components/Words/sample.jpg'>

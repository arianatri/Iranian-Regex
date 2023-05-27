

**all useful regexes for Iranian Developers**
ریجکس های پر کاربرد برای برنامه نویسان ایرانی
----------------------

**کد ملی :** 
Iran national Code : 
exactly 10 Numbers from 0-9  

    ^\d{10}$  

----------------------

**پلاک ماشین :**
Iran License Plate:

Matches a string with the format of two Persian letters, a dash, and three to four digits

    ^[آ-ی]{2}-\d{3,4}$

----------------------
**شماره تلقن همراه :**
Iranian Phone Number:
Matches a string with the format of 11 digits starting with 0 and either 9 or 1 as the second digit:

    ^0[91]\d{9}$

----------------------

**کد پستی :**
Iranian Postal Code:
Matches a string with exactly 10 digits:

    ^\d{10}$

----------------------

**شماره کارت ساده :**
Iranian Bank Card Number:
Matches a string with the format of 16 digits:

    ^\d{16}$

شماره کارت با "-" بین هر 4 رقم
Iranian Bank Card Number if you want to add - bettwee each 4 numbers:

    ^\d{4}-\d{4}-\d{4}-\d{4}$



# Hey guys! 👋
I accept all of contributions and please help me build a complete regex dictionary for all programmers in Iran!







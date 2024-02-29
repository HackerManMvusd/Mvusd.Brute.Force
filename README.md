# MVUSD Brute Force
A brute forcing tool to find passwords in the MVUSD school district

If your anti virus or windows defender is triggered its because it does not have a certificate and im not paying for that shit so deal with it and run anyway

No need to download the passwords.txt or the blockedIDS.txt the passwords.txt will be updated anytime anyone finds a password it will be updated and send into they're
The blocked IDS is something only I can change into make those ids protected from the program

## Installation 
Download the program folder. But downloading the release is much better
Run the Mvusd Brute Force.exe keep the data folder in the same directory as it
To input the id/emails you want all you need to do is go into the data/email_list.txt and input them they're

EX:  
123456789  
987654321

NOTE IF YOU PUT A - INFRONT OF AN EMAIL IT WONT READ IT THIS IS SO YOU DONT HAVE TO DELETE THE EMAIL IF YOU DONT WANT IT ANYMORE

EX:  
-123456789  
-987654321

If you have multiple id/emails in they're make sure they are on they're own line 

Only use proxies if you know what your doing im not gonna explain ONLY use http ones if you want to use them tho put them the data/poxy.txt

EX:  
http:127.0.0.1:8080  
http:127.0.0.1:8080  
http:127.0.0.1:8080  

## Settings

When typing for a setting if it is not valid input it will use a default value and if there is no input just enter pressed it will use these  

Run through the error list: If the program has already been ran before and they're is a errors.txt file in the data folder then it will use those instead of the password lists  
DEFUALT: N

Use the proxy list: WIll use http proxies in the data/proxy.txt  
DEFUALT: N

Use cookies: This will send a cookie to Q making sure to send a response back but makes it slower  
DEFAULT: Y

Use one email at time: Instead of running each email at the same time it will find 1 emails password at time  
DEFAULT: N

Run one password file at a time: This will only test passwords in one file at a time not all of them at the same time it will use less threads meaning less cpu resources this will slow it down  
DEFAULT: Y

Enter the amount of attempts before printing it out password: This is the amount of passwords that will be attempted before printing it out to make sure its working this will speed it up a lot  
DEFUALT: 20

Password List Attempts: The amount of threads going to be created this is how many workers will be sending requests to Q. If run one password at a time is N then it will have that many workers for all of them  
DEFAULT: 1

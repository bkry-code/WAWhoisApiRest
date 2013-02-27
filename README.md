WAWhoisApiRest
==============

Rest API for WHOIS.

Open source code.

-------- Code status information --------

CODE
 1 : unexpected POST data
 2 : Invalid TLD
 3 : Available
 4 : Taken

-------- POST data --------

To check the WHOIS of a domain, you need to send to the API the domain (domail + tld without "www").

POST string name : "domain".
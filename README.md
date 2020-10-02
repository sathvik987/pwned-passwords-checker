 ## This python3 script uses 'Have I Been Pwned' api to check whether the given passwords are part of passwords which are previously exposed in data breaches. In order to protect the value of the source password being searched for, k-Anonymity model is used which allows a password to be searched for by partial hash. This allows the first 5 characters of a SHA-1 password hash to be passed to the API. So this is one of the most secured way to check pwned password.

1. Clone this repo
2. Run this script in a terminal. (python checkmypassword.py)


 
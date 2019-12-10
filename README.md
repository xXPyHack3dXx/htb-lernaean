# Lernaean
Solution to Hack The Box Challenge - Lernaean

### Problem

It's a web that exposes you an admin panel and you must discover the password to gain access. In the explication it says literally "Your target is not very good with computers"...

### Solution

I extracted the common passwords used in the recent years searching in Google, putting it all on a .TXT file. 
Made an application that reads from that file and tries to login on the web using the different password (Brutal Force Attack w/data dictionary).
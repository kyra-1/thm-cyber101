# Use Gobuster To Find Hidden Website Pages
---
gobuster: gobuster -u [url] -w [wordlist] [mode]

command used: ```gobuster -u http://fakebank.thm -w wordlist.txt dir```
The ```Dir``` mode in Gobuster is mainly used to find extra content in a specific target domain or its subdomain. This additional information can include hidden directories or hidden files that can contain sensitive data.   
In ```Dir``` Mode, we can use the option ```"-u"``` to specify the target domain or subdomain you want to dig into the hidden directories and files.     
the ```"-w"``` option will select the wordlist which you wish to use for brute-forcing.

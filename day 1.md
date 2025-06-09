# Use Gobuster To Find Hidden Website Pages
---
gobuster: gobuster -u [url] -w [wordlist] [mode]

command used: ```gobuster -u http://fakebank.thm -w wordlist.txt dir```   
The ```Dir``` mode in Gobuster is mainly used to find extra content in a specific target domain or its subdomain. This additional information can include hidden directories or hidden files that can contain sensitive data.   
In ```Dir``` Mode, we can use the option ```"-u"``` to specify the target domain or subdomain you want to dig into the hidden directories and files.     
the ```"-w"``` option will select the wordlist which you wish to use for brute-forcing.
---
There are many open-source databases out there, like AbuseIPDB, and Cisco Talos Intelligence, where you can perform a reputation and location check for the IP address. Most security analysts use these tools to aid them with alert investigations. You can also make the Internet safer by reporting the malicious IPs, for example, on AbuseIPDB.
---
What is the name of the command replacing ```netstat``` in Linux systems?;
> ss command
 ## Using the ss Command

The ss command is used to dump socket statistics and provides information similar to netstat, but in a simpler and faster manner. Here are some common usages of the ss command:

### Display all sockets
```ss -a```

### Display listening TCP sockets
```ss -lt```

### Display listening UDP sockets
```ss -lu```

### Display all TCP connections
```ss -at```

### Display all UDP connections
```ss -au```

### Display detailed socket information
```ss -e```

### Display socket memory usage
```ss -m```

### Display process using socket
```ss -p```

### Display summary of socket usage
```ss -s```

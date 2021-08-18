# honeycat

A simple honeypot with netcat.

Send in the port number to listen on as the first and only argument to honeycat:

```
bash ./honeycat 80
```

The log is /var/log/honeycat.log and it containers the output of ps auxww and ss -tanu as well as a timestamp.



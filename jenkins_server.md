# Working on the Jenkins server

### Jenkins is running ###

```
root@ip-172-31-2-181:~# systemctl status jenkins
● jenkins.service - Jenkins Continuous Integration Server
     Loaded: loaded (/lib/systemd/system/jenkins.service; enabled; vendor prese>
     Active: active (running) since Thu 2023-01-05 17:14:52 UTC; 34min ago
   Main PID: 468 (java)
      Tasks: 50 (limit: 1143)
     Memory: 404.7M
     CGroup: /system.slice/jenkins.service
             └─468 /usr/bin/java -Djava.awt.headless=true -jar /usr/share/java/>
```

### Configuring Jenkins to copy files to NFS server via SSH ###

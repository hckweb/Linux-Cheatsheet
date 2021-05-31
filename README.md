# Linux-Cheatsheet
## Run a command as an another user

Bash
```bash
sudo runuser pi -c 'cd /home/pi/repo; git pull'
```

C
```c
#include <stdio.h>

system("sudo runuser pi -c 'cd /home/pi/repo; git pull'");
```

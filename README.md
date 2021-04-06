# SacarDatos.bash
Programa que saca *info de permisos, etc* a un **log.txt** en BASH

```

#!/bin/bash
cd /home/li
echo -e `date` >> log.txt; ls -laF >> log.txt ; 
echo -e "#########" >> log.txt

```

Log.txt:

```

lun abril 5 14:00:00 CEST 2021
total 392

drwx------ 20 li  li  12288 abril 27 14:00 ./
drwxr-xr-x  4 root root 496 abril 17 13:04 ../
-rwxrwxrwx  1 li  li    731 abril 27 13:34 10user.sh*
drwx------  3 li  li   4096 abril 21 14:18 .adobe/
-rw-------  1 li  li  24898 abril 27 13:32 .bash_history
-rw-r--r--  1 li  li    220 abril 17 13:04 .bash_logout
-rw-r--r--  1 li  li   3771 abril 17 13:04 .bashrc
drwxrwxr-x  4 li  li   4096 abril 24 13:20 .bluefish/
drwx------ 16 li  li   4096 abril 22 08:46 .cache/
...


```


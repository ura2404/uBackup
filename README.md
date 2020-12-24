# uBackup
Backup script for lot of OS.

## Using
Startup script - backup.
You need to run the script from the start script directory.

For example: 
```
>$ pwd = `pwd`; cd/path/to/script; backup; cd $ pwd
```

Crontab task: 
```
* * * * * cd/path/to/script; bash backup;
```


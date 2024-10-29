# FileMonitoringSystem

## Installation and Startup:

+ Inside the **scripts** folder, run the following commands for installation and startup, respectively: 
  + sudo bash install.sh
  + sudo bash start.sh

## To delete all files
  + sudo bash uninstall.sh
## Accessing logs

+ cat /etc/rsyslog.d/monitord-logs.conf
+ cat /var/log/monitord-logs.log

## Using the Service

+ To designate a file to be monitored:
  + Create a new file or use an existing one
    + In the folder, to add the file to those being monitored, run:
      + /etc/mon -a <path do ficheiro>
        + To check if any monitored files have been altered, use the previously mentioned command to view logs showing which file was changed and the date of the modification
    
+ Check records:
  + cat /etc/monitord-registry.txt

+ To stop monitoring a file:
  + /etc/mon -d <path do ficheiro>

## Shutdown: Terminate the service

+ Inside the **scripts** folder, run the command:
  + sudo bash stop.sh
  
  
  
# Contributors:

[Rui Carvalho](https://github.com/RuiC10)
[Ana Luísa](https://github.com/Analucar)


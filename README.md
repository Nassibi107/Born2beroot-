# BorntoBeroot


# LVM : (Logical Volume manager)

it is an abstration layer between a storge device and file system .

allows the cretion of 'group' of disks or partitions that can be assembled into a single (or multiple filesystems)

>> can be used for nearly any mount point EXCEPT/boot .
>> flexbility -allow for resizing of volumes . // reduce unused space or grow  
>> snapshots -allows for 'point in time' copies of your logical volunme // backup

Example Layout of an LVM Group :

image !!!

 

# What is AppArmor  :

app armor is a deviant-based alternative to SE-LINUX it basically allows you the ability  to restrict access to certain application script or programs to only do certain things or only allowed parts of the system to that program .

>>sudo aa-status  what is appArmor do now ;

>>systmctl status apparmor.

# firewall 

a firewall is a system that is designed to prevent unauthorized access from entring a privte network by filtering the information comes in from the internet.

there tow types :

>>host-based firewall software  firewall that is istalled on a computer .

>>Network-based firewall combination of hardwarw & software .

how firewall can protect me ??

it checks (ip,pressions,destinions,port);

1) pakets filtring ==> (ips,ipr,segment data);
2) state inspection fite wall (the current session)
3) proxy firewall .
4) next-genration-firewall

https://www.youtube.com/watch?v=kDEX1HXybrU;


# ports :
ports logique to detrminion your service at your request (whats do you want ??);
socket (ip && ports);

------------------------------
| 0 -- > 1023 systemes ports; |

| 1024 --> 69151 user port ;  |

| 49159 --> 65535 ;	      |
-------------------------------
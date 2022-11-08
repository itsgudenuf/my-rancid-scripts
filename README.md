# my-rancid-scripts
Rancid scripts I've modified when I couldn't find something already done

# Antaira switches
antrancid - reads the config from a LMX-1002G-SFP-T switch.  uses clogin.  
- supports the normal .cloginrc options  
  
ant18login - specialized expect login script to deal with the LNX-1802GN-T switch  
ant18rancid - For the LNX-1802GN-T  

* These scripts don't handle unknown ssh keys. So connect to the switch once to record the key in known hosts

# Moxa switches
mxlogin - adjusted for the "login as:" prompt.  
- Only tested telnet.  
-  adjusted for no pagenation  
mxrancid - derived from mrancid to drive mxlogin  
-  needed show running-config instead of show config



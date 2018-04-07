# CSU_WK9

I was able to deploy dionaea, suricata, and shockpot honeypot VMs.  The dionaea honeypot began to get attacked immediately after it was stood up.  I did not register any attacks on the other two honeypots, even after I ran NMAP against them from my host machine.  Probably misconfigured them.  

I ran into some issues initally while standing up the mhn-admin box.  I was unable to connect via http after creating the VM and install the MHN admin software.  I ended up having to delete the VM, recreate and reintall.  I think my initial problems may have had somethign to do with setting the firewall rules after creating the VM, though I don't see how.  Was eventually able to connect and deploy honeypots. 

I was able to record 241 attacks against the dionaea box in little over an hour.  

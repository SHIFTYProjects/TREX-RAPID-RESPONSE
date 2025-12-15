# TREX-RAPID-RESPONSE

Powershell incident investigation tool for PC.

I needed a way to investigate a machine I believed was compromised.  There are quite a few applications that require a client to be installed first on the machine.  

There are a bunch of tools from systeminternals that do an excellent job of providing information.  

I wanted it portable and be able to be ran both locally and remotely.  After all scripts are ran, I wanted to be able to disable the machine from the network.


# 12.15.2025  - Major Release Change Update
• Some of the buttons "Can" expose your credentials if Something like Mimikatz is on the suspect Machine.  Those are now either re-writeen to mitigate the risk or highlighted in blue so you are aware of the LOW, but potential risk associated with clicking that button.  
• Added a Universal SID, GUID search at the top.  - Does not use any installed AD modules to query so no installs are needed.  It queries your database for that SID/GUID and "attempts" to give you a result. 


Just download the script.  Rename it to a .ps1 file and run as an admin with powershell.  


For the remote Version - Put in the suspect computer name into the box.

(REMOTE VERSION)


<img width="1022" height="1061" alt="image" src="https://github.com/user-attachments/assets/39bbcc90-6526-4d0b-8fe3-3868a1f584d7" />





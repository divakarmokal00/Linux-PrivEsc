# Linux-PrivEsc
tryhackme.com
https://tryhackme.com/room/linuxprivesc


                                ******************Linux-PrivEsc*************
                                
    1.Make sure you are connected to the TryHackMe VPN or using the in-browser Kali instance before trying to access the Debian VM!
      SSH should be available on port 22. You can login to the "user" account using the following command:
            
                        "ssh user@10.10.73.187"
     
    2. The password for the "user" account is "password321".
        
        The next tasks will walk you through different privilege escalation techniques. After each technique, you should have a root shell. 
        Remember to exit out of  the shell and/or re-establish a session as the "user" account before starting the next task!
        
        
  **************************************Answer the questions below************************************************
                
                1.1. Deploy the machine and login to the "user" account using SSH.       
                ==> No answer needed
                
                1.2. Run the "id" command. What is the result?                         
                ==> uid=1000(user) gid=1000(user) groups=1000(user),24(cdrom),25(floppy),29(audio),30(dip),44(video),46(plugdev)
                
                        user@debian:~$ id
                        uid=1000(user) gid=1000(user) groups=1000(user),24(cdrom),25(floppy),29(audio),30(dip),44(video),46(plugdev)
                        user@debian:~$ 
                        ![image](https://user-images.githubusercontent.com/76117615/125400239-48fbb180-e377-11eb-9ab2-dfa835947e60.png)


                1.3

                        

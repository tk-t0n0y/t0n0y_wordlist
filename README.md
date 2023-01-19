wordlist

 - site wordlist stra...
    - api/v1/
    - /cart/FUZZ.php
    - /admin/(uploads/backups etc)
 
 - site gau++ and own words
   ```ffuf -w js_long.txt -u http://gdc.gov.bd/FUZZ -mc 200,204,301,302,307,401,403,500,405 -e '/',.php,.txt,.db,.php.bak,.html,.md -recursion -recursion-depth 2 -maxtime-job 300```
   
 
 - directories
   - common directory from raft etc 
 
 
 - tecnology
   - Microsoft_ASP_NET
   - PHP
   - Jenkins
   

- 301 content then content type wordlist
  - /sql/ try fuzz.sql
  - if you get /js/ as 302 try java wordlist
  - you get /phpmyadmin/ try php my admin worslit


- file type
  - php
  - html
  - etc
  
  
- universal content file list
  - common filname and data without extension
  - backup
  - sql etc
  
  
  so first 301 wordlist(raft folder) + universal wordlist + tecnology wordlist
  site cusotm + extension wordlist + java wodlist
  
  

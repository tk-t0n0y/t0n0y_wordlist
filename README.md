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
  
  
  - directory 
    - https://wordlists-cdn.assetnote.io/data/manual/raft-large-directories.txt
    - https://github.com/six2dez/OneListForAll/blob/main/dict/dirbuster-dirs_long.txt

- tecnology 
  - https://github.com/iustin24/chameleon/blob/master/config.toml 
  - also https://github.com/six2dez/OneListForAll/tree/main/dict
  - **cms** https://github.com/tk-t0n0y/webapp-wordlists
  
  - 301 got 
    - search 301 after content here https://github.com/six2dez/OneListForAll/tree/main/dict
    
  - universal
    -  https://github.com/six2dez/OneListForAll/blob/main/dict/fuzz_content_long.txt
    - leaky paths
    - robot disallowed
    - https://github.com/six2dez/OneListForAll/blob/main/dict/fuckyou_short.txt + https://github.com/six2dez/OneListForAll/blob/main/dict/fuzz-bo0om_short.txt combination
  
extenaion conten 
 - php look https://github.com/six2dez/OneListForAll/tree/main/dict
 - https://wordlists.assetnote.io/

https://github.com/Karanxa/Bug-Bounty-Wordlists



wget https://raw.githubusercontent.com/six2dez/OneListForAll/main/dict/fuckyou_short.txt
wget https://raw.githubusercontent.com/six2dez/OneListForAll/main/dict/fuzz-bo0om_short.txt 
wget https://raw.githubusercontent.com/six2dez/OneListForAll/main/dict/fuzz_content_long.txt
wget https://raw.githubusercontent.com/six2dez/OneListForAll/main/dict/robotsdisallowed_long.txt
wget https://raw.githubusercontent.com/six2dez/OneListForAll/main/dict/all_content_long.txt 
wget https://raw.githubusercontent.com/six2dez/OneListForAll/main/dict/content_discovery_all_long.txt


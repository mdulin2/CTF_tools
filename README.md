# CTF_tools/ Know How's

## Where to find Info:
* OWASP is fantastic for demonstrations and different types.  
* nullbyte usually gives good demonstrations of attacks if you google them.  
* metaexploit has good descriptions.  
* Just google it until the day is over!  
## SQL Injections:
* The most important thing is to understand the query itsefl! Without this, then there is no point in trying to inject into it.  
* SQLMap is great for cheaking is there are simple issues.  
* MSDat is another tool, that I've never used, but seems great.  
* Pentest Monkey for SQL injections are fantastic. http://pentestmonkey.net/cheat-sheet/sql-injection/mysql-sql-injection-cheat-sheet  
* Payloads include sending files through SMB, writing to a file, stealing information and more.   

## XSS (Cross Site Scripting)
* Mainly, what I use "polyglot" attacks. 
  * These are XSS attacks, that have multiple possible payloads.
* Examples of what I use:
  * https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/XSS%20injection  
* Where these can occur:
  * File uploading, JSON post values, URI based attacks

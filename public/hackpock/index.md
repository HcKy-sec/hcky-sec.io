# Cyber Apocalypse 2021 - Challenges


## AlienPhish

![alien](alienphish1.png)  
<br>
Unzip the downloadable file and view the **slide1.xml.rels** file. Inside is a command with some of the text backwards. Flip the text and decode the base64 for the flag.  
<br>
![alien](alienphish2.png)  
![alien](alienphish3.png)  
<br>
## Authenticator

![auth](authenticator1.png)  
<br>
Open the downloadable file with Ghidra and look through the functions. In the check pin function is a string with a **^9**. Take the string to CyberChef and XOR with a key of 9 to get the flag.  
<br>
![auth](authenticator2.png)  
![auth](authenticator3.png)  
<br>
## BlitzProp
![blitz](blitz1.png)  
<br>
View the website and intecept the traffic with Burp. A hint is given on the song names since AST is capitalized. Check out [AST Injection](https://blog.p6.is/AST-Injection/) for some more info. Insert a command to read the directory the flag is in an then read the flag itself once you have the name.  
<br>
![blitz](blitz2.png)  
![blitz](blitz3.png)

## CAAS

![caas](caas1.png)  
<br>
Have the website request **file:/flag** to read the flag.  
<br>
![caas](caas2.png)

## MiniSTRYplace

![mini](ministry1.png)  
<br>
Viewing the downloadable file tells us that requests with **../** will be replaced with a space. Exploit the LFI vulnerability by putting **..././.../.** before the file to read the flag. 
<br>
![jmini](ministry2.png)  
![mini](ministry3.png)
 


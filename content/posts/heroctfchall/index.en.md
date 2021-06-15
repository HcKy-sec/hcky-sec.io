---
weight: 1
title: "HeroCTF 2021 - Challenges"
date: 2021-04-26T14:00:01+08:00
lastmod: 2021-04-18T26:00:01+08:00
draft: false
author: "HcKy"
authorLink: ""
description: "HeroCTF 2021 - Challenges"
HiddenFromHomePage: true
resources:
- name: "featured-image"
  src: "heroctf.png"

  
tags: [""]
categories: [""]

lightgallery: true
linkToMarkdown: false

toc:
  auto: false
---

## OSINT
### Find Me
![find](findme1.png)  
<br>
Reverse image search the given file. One of the websites states that it is the Portes Mordelaises.  
<br>
![find](findme.png)  
<br>
### Social ID #1
![soc](socialid1.png)  
<br>
Head over to https://tweeterid.com and just put in the HeroCTF handle.  
<br>
![twit](twitter.png)  
### Social ID #2
![soc](socialid21.png)  
<br>
Head over to https://tweeterid.com again and just put in the ID instead.  
<br>  
![soc1](sid22.png)  
### Transfer
![tran](transfer.png)  
<br>
Look up the bitcoin transaction ID and find the wallet the transaction went to.  
<br>
![tran](transfer1.png)
### ProtonDate
![prot](protondate1.png)  
<br>
Look up the email from within Proton Mail and it will show you when the RSA key was created.  
![prot](protondate2.png)  
### Pushhhh
![push](pushhh.png)  
<br>
View the HeroCTF_v2 repository and grab the flag.  
<br>
![push](pushhh1.png)
## Forensics
### We Need You 1
![we](weneedyou1.png)  
<br>
Use the volatility framework to parse through the downloadable memory dump. Use imageinfo to grab the system profile, then hivelist to view the place of the SYSTEM key, then printkey to grab the contents.  
<br>
![we](weneedyou12.png)  
![we](weneedyou13.png)  
### We Need You 2
![we](weneedyou2.png)  
<br>
Grab the NTLM hash from the \Config\DEFAULT key and throw it to an NTLM hash site for the flag.  
<br>
![we](weneedyou22.png)  
![we](weneedyou23.png)  
### We Need You 3
![we](weneedyou31.png)  
<br>
Use the netscan option to view any connections made to the machine.  
<br>
![we](weneedyou32.png)
![we](weneedyou33.png)  
## Other
### Russian
![ru](russian.png)  
<br>
Open all the zip files to get the flag.  
<br>
![russ](russian2.png)  
### Holy Abbot
![ha](holyabbot.png)  
<br>
Decode the file from Ave Maria cipher.  
<br>
![ha](holyabbot2.png)  
### Phono
![phono](phono.png)  
<br>
Download the PhonoPaper app and use it to listen to the downloadable file to hear the flag. 

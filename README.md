# InformationGathering
Information Gathering Techiques

# To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering

## Pen Test Tools Categories:  

Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.
http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.

## OUTPUT:

<img width="940" height="769" alt="image" src="https://github.com/user-attachments/assets/fdc72fcd-b8b6-49de-9d43-788a63068641" />
<img width="940" height="803" alt="image" src="https://github.com/user-attachments/assets/a5f0b90b-22fa-4b76-9af0-9ae1639f81e8" />



## Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of facebook.com.
##output
<img width="940" height="433" alt="image" src="https://github.com/user-attachments/assets/26f2c2a1-c3fc-4395-8f0e-bec8700e8345" />



## Finding Hosting Company
get further detail by using ip2location.com website.
##output
<img width="940" height="451" alt="image" src="https://github.com/user-attachments/assets/fabd6097-67d7-4d8a-b343-b6d464fbae74" />



## History of the website:
Wayback Machine is used to view archived versions of websites from previous years. It helps analyze changes in content, design, and hidden old pages. This is useful for historical website reconnaissance.

## output
https://web.archive.org/

<img width="940" height="498" alt="image" src="https://github.com/user-attachments/assets/84734bb6-ec31-46b5-9723-46f07b8097d3" />



# Webserver Fingerprinting:

## Netcat:

Netcat is a networking utility used to read/write data across network connections. It can connect to web servers manually and grab banners to identify services. It is useful for testing ports and server responses.
sudo nc example.com 80

<img width="940" height="375" alt="image" src="https://github.com/user-attachments/assets/357311bb-8227-4c9f-853c-44076b32d35a" />




## nmap:
Nmap is a powerful network scanner used to discover hosts, open ports, and running services. It also detects operating systems and versions. It is widely used for network mapping and security auditing.

###output

<img width="940" height="256" alt="image" src="https://github.com/user-attachments/assets/00169bc0-822f-406a-b4cd-68ed0c29ad1c" />


## Whatweb
WhatWeb identifies technologies used by a website such as CMS, frameworks, and server software. It detects plugins, analytics tools, and scripting languages. This helps fingerprint the target web server.

### output
<img width="940" height="454" alt="image" src="https://github.com/user-attachments/assets/35e844e3-053d-4363-ac66-4e74f5bea152" />


## httprint
Httprint is a web server fingerprinting tool used to identify web server type and version. It works even when banners are hidden. It is useful for detecting Apache, IIS, Nginx, etc.

### output

<img width="940" height="423" alt="image" src="https://github.com/user-attachments/assets/ce7bfd3b-8fd3-4961-a2aa-90efde9a5ce7" />



# Tracing the Location
Traceroute is used to trace the path packets take from source to destination. It shows intermediate routers and network delays. It helps analyze network routes and locate connectivity issues.

TCP Traceroute:

sudo traceroute -T www.google.com
## output
<img width="940" height="153" alt="image" src="https://github.com/user-attachments/assets/03f069be-6c1d-4c32-8d2f-0d2858ab4043" />



## UDP Traceroute:
sudo traceroute -U www.google.com
## output
<img width="940" height="193" alt="image" src="https://github.com/user-attachments/assets/ac340e28-913b-4b26-8b4e-ac21278c862f" />



## ICMP Traceroute:
sudo traceroute  www.google.com
## output

<img width="940" height="153" alt="image" src="https://github.com/user-attachments/assets/69e90c56-d729-4bbb-8abf-4d89b8ac4656" />





## RESULT:
The information gathering techniques tools/procedure were  identified successfully

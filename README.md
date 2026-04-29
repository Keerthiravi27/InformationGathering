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
<img width="1907" height="1036" alt="Screenshot 2026-04-29 132336" src="https://github.com/user-attachments/assets/79bdb600-13a8-4aad-a531-bd461dba9828" />


## Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of facebook.com.
##output
Whois.com:
<img width="1907" height="1036" alt="image" src="https://github.com/user-attachments/assets/18f4a09d-4bcd-4458-bf97-d74a9e3f3723" />


## Finding Hosting Company
get further detail by using ip2location.com website.
##output

ip2location:
<img width="1892" height="968" alt="image" src="https://github.com/user-attachments/assets/9ee884c7-dd46-4422-9e2b-8e42223bce4f" />

## History of the website:
## output
https://web.archive.org/
<img width="1866" height="1053" alt="image" src="https://github.com/user-attachments/assets/01336954-3562-4eb8-b73c-0fdb35e71071" />
<img width="1911" height="1093" alt="image" src="https://github.com/user-attachments/assets/0a8dbfc8-8921-4194-bc4d-103c9fe06779" />



# Webserver Fingerprinting:

## Netcat:
sudo nc example.com 80
GET / HTTP/1.1
Host: example.com


<img width="920" height="1045" alt="image" src="https://github.com/user-attachments/assets/33d22c4c-ccd0-4ec5-8cb6-bcbacf45c743" />

## nmap:
###output

<img width="920" height="1045" alt="image" src="https://github.com/user-attachments/assets/032a70ce-3d1f-4129-88b1-a91e9997a3f8" />



## httprint
### output

<img width="920" height="1045" alt="image" src="https://github.com/user-attachments/assets/032a70ce-3d1f-4129-88b1-a91e9997a3f8" />




# Tracing the Location
TCP Traceroute:
sudo traceroute -T seattletimes.com
## output
<img width="920" height="1045" alt="image" src="https://github.com/user-attachments/assets/b75eda91-3f91-48c1-a392-6dfd75cb0000" />


## UDP Traceroute:
sudo traceroute -U seattletimes.com
## output
<img width="920" height="1045" alt="image" src="https://github.com/user-attachments/assets/f400b6b2-2003-42c6-aeff-2c8ed8a2a9b5" />


## ICMP Traceroute:
sudo traceroute seattletimes.com
## output

<img width="920" height="1045" alt="image" src="https://github.com/user-attachments/assets/0e0aea60-a949-45e2-a553-918cbadaeaff" />






## RESULT:
The information gathering techniques tools/procedure were  identified successfully

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



## nmap:
###output


## Whatweb
### output


## httprint
### output




# Tracing the Location
TCP Traceroute:
sudo traceroute -T www.google.com
## output


## UDP Traceroute:
sudo traceroute -U www.google.com
## output



## ICMP Traceroute:
sudo traceroute  www.google.com
## output






## RESULT:
The information gathering techniques tools/procedure were  identified successfully

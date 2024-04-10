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

![Screenshot 2024-04-10 090430](https://github.com/manikandan26052004/InformationGathering/assets/121999845/a894ec09-ddfc-4480-accc-65e38c0876f1)

## Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of facebook.com.

## OUTPUT:

![Screenshot 2024-04-10 091905](https://github.com/manikandan26052004/InformationGathering/assets/121999845/9333755d-f9dd-4bfc-9df5-712674d87d60)

## Finding Hosting Company
get further detail by using ip2location.com website.

## OUTPUT:

![Screenshot 2024-04-10 090816](https://github.com/manikandan26052004/InformationGathering/assets/121999845/10e24229-4235-4911-8f48-569b31c9568e)

## History of the website:
## OUTPUT:

https://web.archive.org/


![Screenshot 2024-04-10 091203](https://github.com/manikandan26052004/InformationGathering/assets/121999845/5532ab8f-c4b0-4044-a068-9814fc24ebb6)

# Webserver Fingerprinting:

## Netcat:
sudo nc example.com 80
GET / HTTP/1.1
Host: example.com

## OUTPUT:

![Screenshot 2024-04-10 092235](https://github.com/manikandan26052004/InformationGathering/assets/121999845/844f9771-96dd-4706-93f4-420737313526)

## nmap:
## OUTPUT:

![Screenshot 2024-04-10 092400](https://github.com/manikandan26052004/InformationGathering/assets/121999845/4848d90d-c3b5-438b-8f5b-dce0ef0d1374)

# whatweb:
## OUTPUT:

![Screenshot 2024-04-10 092951](https://github.com/manikandan26052004/InformationGathering/assets/121999845/c110766c-5146-44ba-9961-f351b5b9f3ac)
![Screenshot 2024-04-10 093038](https://github.com/manikandan26052004/InformationGathering/assets/121999845/e15474e6-5287-49ae-991a-84e44a680af7)
![Screenshot 2024-04-10 093148](https://github.com/manikandan26052004/InformationGathering/assets/121999845/54e172d9-bcc4-4339-9939-6ca67baba295)


## httprint;
## OUTPUT:

![318794627-a5cb8b06-319e-43ef-a63a-9c55bedbc7c1](https://github.com/manikandan26052004/InformationGathering/assets/121999845/5d08225f-a0fa-421f-821d-0c014080865d)


# Tracing the Location
# TCP Traceroute:
sudo traceroute -T www.google.com
## OUTPUT:

![Screenshot 2024-04-10 093334](https://github.com/manikandan26052004/InformationGathering/assets/121999845/ef65eac9-997d-49da-97d0-0cbcfd02bbfb)


# UDP Traceroute:
sudo traceroute -U www.google.com
## OUTPUT:

![318795454-88108d16-99d8-4b9d-9ee4-75007ee77bda](https://github.com/manikandan26052004/InformationGathering/assets/121999845/3ca724b4-16af-484e-ba2e-d6ac88043b27)


# ICMP Traceroute:
sudo traceroute  www.google.com
## OUTPUT:

![318795669-a56d530b-732b-4de2-801d-201a8c519521](https://github.com/manikandan26052004/InformationGathering/assets/121999845/208ba069-b7cc-4ea7-80dc-288575a29cb8)



## RESULT:
The information gathering techniques tools/procedure were  identified successfully

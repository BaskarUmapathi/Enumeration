# Enumeration
Enumeration Techniques
```
NAME: BASKAR U
REG NO: 212223220012
```

# Explore Google hacking and enumeration 

# AIM:

To use Google for gathering information and perform enumeration of targets

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various Google hacking keywords and enumeration tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## Pen Test Tools Categories:  

Following Categories of pen test tools are identified:
Information Gathering.

Google Hacking:

Google hacking, also known as Google dorking, is a technique that involves using advanced operators to perform targeted searches on Google. These operators can be used to search for specific types of information, such as sensitive data that may have been inadvertently exposed on the web. Here are some advanced operators that can be used for Google hacking:

site: This operator allows you to search for pages that are within a specific website or domain. For example, "site:example.com" would search for pages that are on the example.com domain.
Following searches for all the sites that is in the domain yahoo.com

![Screenshot 2025-03-28 000030](https://github.com/user-attachments/assets/0a14de4d-da0d-4df6-9377-3c959a2efad7)

filetype: This operator allows you to search for files of a specific type. For example, "filetype:pdf" would search for all PDF files.
Following searches for pdf file in the domain yahoo.com

![Screenshot 2025-03-21 142730](https://github.com/user-attachments/assets/dce5b448-f48f-412f-8193-c9a2a56ea52a)

intext: This operator allows you to search for pages that contain specific text within the body of the page. For example, "intext:password" would search for pages that contain the word "password" within the body of the page.

![Screenshot 2025-03-21 143833](https://github.com/user-attachments/assets/ca68f667-ee70-44b5-8318-54830c5d66f0)

inurl: This operator allows you to search for pages that contain specific text within the URL. For example, "inurl:admin" would search for pages that contain the word "admin" within the URL.

![Screenshot 2025-03-21 143925](https://github.com/user-attachments/assets/f7d5d4a0-9ed3-4847-858a-c9021633149e)

intitle: This operator allows you to search for pages that contain specific text within the title tag. For example, "intitle:index of" would search for pages that contain "index of" within the title tag.

![Screenshot 2025-03-21 144012](https://github.com/user-attachments/assets/51187f90-dcf6-460c-b336-0536aa264010)

link: This operator allows you to search for pages that link to a specific URL. For example, "link:example.com" would search for pages that link to the example.com domain.

![Screenshot 2025-03-21 144100](https://github.com/user-attachments/assets/9ee1fb8f-4a2e-4881-b4ea-9cfbaf44fc58)

cache: This operator allows you to view the cached version of a page. For example, "cache:example.com" would show the cached version of the example.com website.

![Screenshot 2025-03-21 144123](https://github.com/user-attachments/assets/785a4907-8394-4267-a146-fb0801ae4897)
 
#DNS Enumeration


## DNS Recon
provides the ability to perform:
Check all NS records for zone transfers
Enumerate general DNS records for a given domain (MX, SOA, NS, A, AAAA, SPF , TXT)
Perform common SRV Record Enumeration
Top level domain expansion
## OUTPUT:

![Screenshot 2025-03-28 125222](https://github.com/user-attachments/assets/a6de3f50-b2f5-4a06-a773-4444ff854633)

## dnsenum
Dnsenum is a multithreaded perl script to enumerate DNS information of a domain and to discover non-contiguous ip blocks. The main purpose of Dnsenum is to gather as much information as possible about a domain. The program currently performs the following operations:

Get the host’s addresses (A record).
Get the namservers (threaded).
Get the MX record (threaded).
Perform axfr queries on nameservers and get BIND versions(threaded).
Get extra names and subdomains via google scraping (google query = “allinurl: -www site:domain”).
Brute force subdomains from file, can also perform recursion on subdomain that have NS records (all threaded).
Calculate C class domain network ranges and perform whois queries on them (threaded).
Perform reverse lookups on netranges (C class or/and whois netranges) (threaded).
Write to domain_ips.txt file ip-blocks.
This program is useful for pentesters, ethical hackers and forensics experts. It also can be used for security tests.

## OUTPUT:

![Screenshot 2025-03-28 124721](https://github.com/user-attachments/assets/883cbb0d-9914-4fe8-9d53-5533c8be8f6d)


## smtp-user-enum
Username guessing tool primarily for use against the default Solaris SMTP service. Can use either EXPN, VRFY or RCPT TO.


In metasploit list all the usernames using head /etc/passwd or cat /etc/passwd:

select any username in the first column of the above file and check the same

## OUTPUT:

![Screenshot 2025-03-28 124601](https://github.com/user-attachments/assets/9ea3b26f-a06c-45c3-a2ef-e1cea2bbffa2)

## Telnet for smtp enumeration
Telnet allows to connect to remote host based on the port no. For smtp port no is 25
telnet <host address> 25 to connect
and issue appropriate commands
  
## Output
  
![Screenshot 2025-03-28 133807](https://github.com/user-attachments/assets/15ff3553-c10e-4700-abcd-4e96be02811e)

## nmap –script smtp-enum-users.nse <hostname>

The smtp-enum-users.nse script attempts to enumerate the users on a SMTP server by issuing the VRFY, EXPN or RCPT TO commands. The goal of this script is to discover all the user accounts in the remote system.

## OUTPUT:

![Screenshot 2025-03-28 124913](https://github.com/user-attachments/assets/ba1fcc93-349c-4220-894c-b469bd0189ea)

## RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully


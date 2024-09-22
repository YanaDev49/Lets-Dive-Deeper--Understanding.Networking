# 𝑯𝙤𝒘 𝑫𝙉𝑺 𝒘𝙤𝒓𝙠𝒔?! 🤔🚨

![image](https://github.com/user-attachments/assets/0c39275b-cc93-4a6f-9b42-ba6fbdd609b5)

## Understanding DNS Resolution 

DNS resoluion is the process of converting domain names into IP addresses which is done through the DNS Hierarchy and Distribution!

## So What Is The DNS Hierarchy And Distribution?

This refers to how the Domain Name System is structured and how it works to convert text base domain names for example (example.com)
into IP addresses that computers use to communicate! 

![image](https://github.com/user-attachments/assets/70b493a4-b9ff-40b7-ab05-49a4ad25fa38)

This is how DNS actually works from the top to the end.

## Lets Have A Look!
![Let'SHaveALookGillGIF](https://github.com/user-attachments/assets/d28685bc-630a-4c06-9466-7d0cbab47b8f)

## 𝗗𝗡𝗦 𝗥𝗼𝗼𝘁: 𝗧𝗵𝗲 𝗧𝗼𝗽 

The DNS route keeps high level information on where to find the top level domains underneath it!

![image](https://github.com/user-attachments/assets/8f25c780-20bc-43a9-a51e-09d837cefe1c)

## Top Level Domains (TLD)

Top Level Domains are the last part of a website address (domain name), like .com, .org, or .net.

For example in the domain 'www.google.com' the TLD is '.com'

and in the domain 'www.bbc.co.uk' the TLD is '.uk'

Each TLD stores information about domains within the scope, it holds information about the domain in all kinds of variations.

![image](https://github.com/user-attachments/assets/e42ea529-2cb1-4d6b-ab64-6eff8ad86aed)

## Authoritative Name Servers Host 1 +Zones For Domains

These are servers that store the 'official DNS Records' for a domain, like its IP address, email sever information, etc.
When someone tries to visit a website (e.g., www.example.com), the authoritative name server is the one that gives the final answer, such as the IP where 
the site is hosted.

![image](https://github.com/user-attachments/assets/c72dc615-bb22-4f4b-a399-7191b3a35600)


## Analogy!!

![AnalogyAlertGIF](https://github.com/user-attachments/assets/c43ec34f-ffbf-436d-b4d4-316bd103777b)

Lets think of it like a library where authoritative name servers are the librarian who has the official list of all the books (which in hind sight are the domain) and can tell you
exactly where to find them (IP addresses).

## The Actual Domain (google.com)

Each domain has a zone and a zone file (as previously mentioned), this zone is like a team within a department and the zone file is like a detailed list of Records of that domain.
This is where all the specific information like IP addresses, mail servers of the domain are stored.


𝗧𝗵𝗶𝘀 𝗛𝗶𝗲𝗿𝗮𝗿𝗰𝗵𝘆 𝗲𝗻𝘀𝘂𝗿𝗲𝘀 𝘁𝗵𝗮𝘁 𝘄𝗵𝗲𝗻 𝘆𝗼𝘂 𝘁𝘆𝗽𝗲 𝗮 𝘄𝗲𝗯 𝗮𝗱𝗱𝗿𝗲𝘀𝘀 𝗶𝗻𝘁𝗼 𝗮 𝗯𝗿𝗼𝘄𝘀𝗲𝗿,
𝗶𝘁 𝗰𝗮𝗻 𝗾𝘂𝗶𝗰𝗸𝗹𝘆 𝗳𝗶𝗻𝗱 𝘁𝗵𝗲 𝗿𝗶𝗴𝗵𝘁 𝗜𝗣 𝗮𝗱𝗱𝗿𝗲𝘀𝘀 𝘁𝗼 𝗰𝗼𝗻𝗻𝗲𝗰𝘁 𝗻𝗼 𝗺𝗮𝘁𝘁𝗲𝗿 𝘄𝗵𝗲𝗿𝗲 𝗶𝗻 𝘁𝗵𝗲 
𝘄𝗼𝗿𝗹𝗱 𝗮 𝗱𝗼𝗺𝗮𝗶𝗻 𝗶𝘀 𝗵𝗼𝘀𝘁𝗲𝗱.

# DNS Resolution Process 

𝗦𝗼 𝘄𝗵𝗮𝘁 𝗵𝗮𝗽𝗽𝗲𝗻𝘀 𝘄𝗵𝗲𝗻 𝘆𝗼𝘂 𝘁𝘆𝗽𝗲 𝘄𝘄𝘄.𝗴𝗼𝗼𝗴𝗹𝗲.𝗰𝗼𝗺 𝗶𝗻𝘁𝗼 𝘆𝗼𝘂𝗿 𝗯𝗿𝗼𝘄𝘀𝗲𝗿? 🤔🚀📲

## 1.

Lets start off with you being the user typing 'www.google.com' in the browser

![image](https://github.com/user-attachments/assets/a840a512-ad9a-4d03-95da-d123f2541a3d)

## 2.

Your browser will send a request to your DNS Resolver that is local to you 

![image](https://github.com/user-attachments/assets/2d9f2eb8-6a23-44dd-9d7d-bc54819d58a7)

## 3.

The DNS resolver does a query, it recieves a request and starts looking for the IP address by first looking 
into its local cache to see if it knows the IP address

![image](https://github.com/user-attachments/assets/543641b3-fbaa-4e26-a6d8-9146dee477a1)

## 4.

If the DNS resolver does not Recognise the IP. then it moves on to the next step.
The Resolver then queries a root server for the IP address. Bare in mind that the root server does not know the IP address of the main
nut knows where to find the '.com' top level domain server.

![image](https://github.com/user-attachments/assets/505f1881-b8b9-41ae-aa8c-e9cd2cf3bda8)

## 5.

Then we have the TD server. The resolver then queries a .com TD server. a TD server Doesnt know the exact IP address of google.com either, however it knows
which authoritative name server to ask.

![image](https://github.com/user-attachments/assets/60b6cbac-5b8f-42ab-8bd8-47acce0adedb)

## 6. 

The resolver queries the authoritative name server for google.com. This server has a definitive IP address, Then the IP address is returned to your
DNS Resolver. The DNS Resolver then sends the IP address back to your browser. Now that your browser has the IP address, it can connect to the web server at its IP address. Finally your website 
google.com loads!! 🎉🎆🥳🙌

![image](https://github.com/user-attachments/assets/28bd2a7c-b837-4812-a604-0a1e2b36adc3)

And that is the overall process of How DNS works!!

![ThereYouHaveItSheaWhitneyGIF](https://github.com/user-attachments/assets/69f14373-a513-4fce-854b-bbca28163033)

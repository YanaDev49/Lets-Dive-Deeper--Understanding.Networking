# 𝐖𝐞𝐥𝐜𝐨𝐦𝐞 𝐭𝐨 𝐀𝐧 𝐈𝐧𝐭𝐫𝐨𝐝𝐮𝐜𝐭𝐢𝐨𝐧 𝐭𝐨 𝐃𝐍𝐒!
(𝐃𝐨𝐦𝐚𝐢𝐧 𝐒𝐲𝐬𝐭𝐞𝐦 𝐍𝐚𝐦𝐞) 🚀📲

![image](https://github.com/user-attachments/assets/34ae8551-7a2b-4587-9165-acb03fee1d9e)

## 𝐿𝑒𝑡𝑠 𝐷𝑒𝑓𝑖𝑛𝑒 𝑇ℎ𝑒 𝐵𝑎𝑠𝑖𝑐𝑠: 𝑊ℎ𝑎𝑡 𝑖𝑠 𝑎 𝐷𝑜𝑚𝑎𝑖𝑛 𝑁𝑎𝑚𝑒 𝑆𝑦𝑠𝑡𝑒𝑚 𝑎𝑛𝑑 𝑊ℎ𝑎𝑡 𝐷𝑜𝑒𝑠 𝐼𝑡 𝐷𝑜? 🤔

DNS (Domain Name System) allows us humans to keep track of websites and hosts by name instead of an IP address. Its like a contacts list for the internet in the sense that, you dont have to write the full IP address to get access to a website and can just write its name!

For example, lets say that you want to access someones LinkedIn web page. The full URL would look something like this (im going to show you mine):  

![image](https://github.com/user-attachments/assets/e4cacd79-8d0d-4467-8102-43314d0cfbf2)
  
Without A DNS (Domain System Name) you would have to type in the whole IP address to access the website. So to access my linkedIn page, you can simply type 'Aaliyana Adoley Mingle LinkedIn' for a smooth searching experience 👀

## 𝗦𝗼 𝗵𝗼𝘄 𝗱𝗼𝗲𝘀 𝗮 𝗗𝗼𝗺𝗮𝗶𝗻 𝗡𝗮𝗺𝗲 𝗦𝘆𝘀𝘁𝗲𝗺 𝗗𝗼 𝘁𝗵𝗶𝘀? 🤔

![image](https://github.com/user-attachments/assets/d48e388e-4bb5-4fe6-83d9-541f6523dd05)

A DNS translates domain names to an IP address which is why we can jut type the name of the website and it will automatically load. Behind the scenes however, our computer is is working through the network trying to connect servers to our IP address. This simplifies navigation on the internet for its users and is essential for accessing websites and services 


Lets take a closer look at the Components of DNS and how they all play a part in networking:

## What are Name Servers?

![image](https://github.com/user-attachments/assets/0a15433c-71dd-46cd-b757-8c391727518b)

A name server is a specialised server within the Domain Name System that helps translate domain names (like www.example.com) into IP addresses like (192.0.2.1). This process is essential because while users use domain names that are easy to remember, computers and networks use numerical IP addresses to identify each other and route traffic.

![image](https://github.com/user-attachments/assets/d3a01b02-e38f-4b08-ab88-e25194d41fde) 


## So How do Name Servers work?

![HowDoesItWorkRubySundayGIF](https://github.com/user-attachments/assets/49508bdd-b96a-4931-9f30-36c526d41b71)

So when you type a website URL into your browser, the browser needs to know the IP address of the websites server to load the page. Domain names (like example.com) are just labels that are easier for us to nuse but our machines communicate using IP addresses.

So to get the IP address, your browser sends a request, called a DNS query, asking for the IP address corresponding to the domain name.

The name server is the computer or system that holds the information (DNS records) to answer that query. It looks up the domain name in its database and returns the correct IP address to the browser. This is a process known as 'Resolving' the domain name.

## Authoritative and Recursive Name Servers

![image](https://github.com/user-attachments/assets/3002859e-2a7c-4e02-a4ee-73cf4bec7d8e)

Authoritative Name Servers are responsible for storing the actual DNS Records for a specific domain (like example.com). They hold all the essential information about the domain, such as its IP address (A Record), mail servers (MX record), etc.

Recursive Name Servers on the other hand are intermediaries that help your browser by perfomring DNS lookups on your behalf. if they dont have the answer, they query other name servers until they find the correct IP address. Your internet service provider ofthen uses these!!

## what Are Zone Files?

![image](https://github.com/user-attachments/assets/461f4288-c64d-4f2e-80aa-d37aeeba12e7)

Zone files are stored inside your Name Servers and they contain information about the Domain. They help Name Servers answer queries about how to get to a domain if the name server doesnt know the answer directly. Zone files make sure that your Domain System information is in a presentable format which makes it easier to handle DNS records!!

## A Visual Representation of a Zone file ⤵️
![image](https://github.com/user-attachments/assets/058a8815-42cc-44b3-a14d-9affe1c696c1)

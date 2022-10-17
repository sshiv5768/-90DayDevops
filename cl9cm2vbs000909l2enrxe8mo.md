# Day-23 Network Protocols part-1

We discussed the OSI model and each of its layers yesterday. We also look at which protocols are used at which layer. Today, we'll take a more in-depth look into network protocols.

### HTTP: Hyper Text Transfer Protocol
You may have a basic idea about client-server model right! In this model web browser act as client and asks for some sort of data whether it is picture, video or web content. And on the other side server sends that data in the form of response.

![horizontal (10).png](https://cdn.hashnode.com/res/hashnode/image/upload/v1665973797879/le9NDnjsA.png align="left")

I'm explaining this because the abvove entire process makes use of the HTTP protocol. A web browser sends an HTTP request, and a server responds with an HTTP response. There are also various HTTP methods available to request data.

- GET: To read data from the server
- POST: To send data to the server
- DELETE: To delete data from the server

Checkout [this](https://www.tutorialspoint.com/http/http_methods.htm) for more info about HTTP methods.
There is also an extended version of HTTP available, which is known as **HTTPS**. It is secure, fast, and encrypted with [TLS](https://www.cloudflare.com/en-gb/learning/ssl/transport-layer-security-tls/).

### FTP: File Transfer Protocol 🗃️
It is standard protocol that is used to transfer files between computer and server over a Network. In simple term if i say FTP is a language which is used by both computer and server for larger data transfer.

![Servers](https://media.giphy.com/media/WTO8QA0mX2Cfw5vhkp/giphy.gif)
Let's understand it by a simple example. Suppose you a file that you want to make available for others also. Then you will simply put it in FTP server and other can download it from FTP server using FTP protocol.

### SMTP: Simple Mail Transfer Protocol 📨

The SMTP protocol was created to transfer e-mail. It receives incoming emails and transfers them between systems. It is basically used with another protocol known as **POP**(Post Office Protocol). SMTP pushes the mail to the email servers, and POP helps you download that mail from the servers.

![Email](https://media.giphy.com/media/JIX9t2j0ZTN9S/giphy.gif)

A client can transfer an email to another client on the same network or another network through a relay or gateway access available to both networks using SMTP.

### DNS: Domain Name System 🗄️

Have you ever wondered why we only use domain names when searching the internet rather than IP addresses? Because names are easy to remind. That's why domain names are used to fetch particular data from the internet servers. 

![horizontal (11).png](https://cdn.hashnode.com/res/hashnode/image/upload/v1666000353245/65JULvW_V.png align="left")

But who allocate domain name to the particular site and connect it with corresponding server IP address? This process is handled by **DNS**(Domain Name System). It allocates and maps the domain name with corresponding server IP address. 

## Resources 📚
- [Networking Fundamentals](https://youtube.com/playlist?list=PLIFyRwBY_4bRLmKfP1KnZA6rZbRHtxmXi)
- [Network protocols](https://www.manageengine.com/network-monitoring/network-protocols.html)

## Ending Notes 👋
That was all in part-1 for the network protocols. There is still lot more to cover in Network protocols that we will cover in next part. 








# Introductory Networking : TryHackMe Room Walkthrough

Hello everyone, I'm back with another article for you people. 

This is a walkthrough for the room **Introductory Networking** on **[TryHackMe](https://tryhackme.com/)**, I have seen many people on the internet stuck in this room as the writer of the room said it is a beginner level room, but I doubt it as I am also a beginner in Cyber Security with just a month of experience learning from TryHackMe rooms. 

Before this I’ll recommend you guys please complete this room all by yourself because this is what the fun is in TryHackMe rooms. As I said I’m also a beginner, but I found that there are many ways to solve challenges in this room so you can choose your own way or follow me on the go.

**Room Link:- https://tryhackme.com/room/introtonetworking**

<iframe src="https://giphy.com/embed/HyxK9xIodu1mb2yVnN" width="480" height="270" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/teleraptor-concert-microphone-texto-dallas-HyxK9xIodu1mb2yVnN">via GIPHY</a></p>

---

## Task 1 : Introduction
In this task, just get to know the aim of the room and what are the things you're gonna study.

> No answer needed

Let's jump to the next task.

---

## Task 2 :  The OSI Model: An Overview
This task is all about OSI Model. 

According to TryHackMe Room:
> The OSI (Open Systems Interconnection) Model is a standardised model which we use to demonstrate the theory behind computer networking. In practice, it's actually the more compact TCP/IP model that real-world networking is based off; however the OSI model, in many ways, is easier to get an initial understanding from.

The OSI model consists of seven layers:
- Application
- Presentation
- Session
- Transport
- Network 
- Data Link 
- Physical

*Note that layers start from bottom-to-top order, i.e., from Physical to Application layer.*
You can learn all about these layers in detail from the room itself and solve the following questions on your own.

***For the "Which Layer" Questions below, answer using the layer number (1-7)***

**<u>Answer the questions below</u>**

**Question 1:** Which layer would choose to send data over TCP or UDP?
> 4

**Question 2:** Which layer checks received packets to make sure that they haven't been corrupted?
> 2

**Question 3:** In which layer would data be formatted in preparation for transmission?
> 2

**Question 4:** Which layer transmits and receives data?
> 1

**Question 5:** Which layer encrypts, compresses, or otherwise transforms the initial data to give it a standardised format?
> 6

**Question 6:** Which layer tracks communications between the host and receiving computers?
> 5

**Question 7:** Which layer accepts communication requests from applications?
> 7

**Question 8:** Which layer handles logical addressing?
> 3

**Question 9:** When sending data over TCP, what would you call the "bite-sized" pieces of data?
> Segments

**Question 10:** **[Research]** Which layer would the FTP protocol communicate with?

*Hint -> For this, I'd say Google is your best friend. Go and hit a search.*
<iframe src="https://giphy.com/embed/rcmg2ogSBedUs" width="480" height="220" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/grace-helbig-rcmg2ogSBedUs">via GIPHY</a></p>

> 7

**Question 11:** Which transport layer protocol would be best suited to transmit a live video?
> UDP

---

## Task 3 : Encapsulation
This task talks about data encapsulation inside the various networking layers.

Here's a glimpse of it:

<figure align= "center">
  <img src="https://cdn.hashnode.com/res/hashnode/image/upload/v1660543754224/CKRrlLy_f.png" alt="Encapsulation"  />
  <figcaption> Image Credits: TryHackMe Room </figcaption>
</figure>

**<u>Answer the questions below</u>**

**Question 1:** How would you refer to data at layer 2 of the encapsulation process (with the OSI model)?
> Frames

**Question 2:** How would you refer to data at layer 4 of the encapsulation process (with the OSI model), if the UDP protocol has been selected?
> Datagrams

**Question 3:** What process would a computer perform on a received message?
> De-encapsulation

**Question 4:** Which is the only layer of the OSI model to add a trailer during encapsulation?
> Data Link

**Question 5:** Does encapsulation provide an extra layer of security (Aye/Nay)?
> Aye

---

## Task 4 : The TCP/IP Model
This task is all about the TCP/IP Model. You may call it as an older version of OSI Model. This model is also very similar to the OSI Model.

The two models match up something like this:
<figure align= "center">
  <img src="https://muirlandoracle.co.uk/wp-content/uploads/2020/02/image-3.png" alt="TCP-IP/OSI"  />
  <figcaption> Image Credits: TryHackMe Room </figcaption>
</figure>

You can learn all about their history and functions from the room itself.

**<u>Answer the questions below</u>**

**Question 1:** Which model was introduced first, OSI or TCP/IP?
> TCP/IP

**Question 2:** Which layer of the TCP/IP model covers the functionality of the Transport layer of the OSI model **(Full Name)**?
> Transport

**Question 3:** Which layer of the TCP/IP model covers the functionality of the Session layer of the OSI model **(Full Name)**?
> Application

**Question 4:** The Network Interface layer of the TCP/IP model covers the functionality of two layers in the OSI model. These layers are Data Link, and?.. **(Full Name)**?
> Physical

**Question 5:** Which layer of the TCP/IP model handles the functionality of the OSI network layer?
> Internet

**Question 6:** What kind of protocol is TCP?

*Hint -> In comparison, UDP would be connectionless*
> Connection-based

**Question 7:** What is SYN short for?

*Hint -> British Spelling*
> Synchronise

**Question 8:** What is the second step of the three way handshake?
> SYN/ACK

**Question 9:** What is the short name for the "Acknowledgement" segment in the three-way handshake?
> ACK

---

## Task 5 : <mark>[Networking Tools]</mark> Ping
In this task, you're gonna learn about an interesting tool called `ping`.

According to TryHackMe:
> The ping command is used when we want to test whether a connection to a remote resource is possible. 
The basic syntax for ping is `ping <target>`.

Let's ping **Google**

![ping-google.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1660545909754/3XjhvZ2UF.png align="left")
You'll get a lot of data like this. Here you can see that the ping command actually returned the IP address for the Google server that it connected to, rather than the URL that was requested. 

For other commands realted to `ping`, you can use `man ping` and hit enter in your terminal.

**<u>Answer the questions below</u>**

**Question 1:** What command would you use to ping the bbc.co.uk website?
> `ping bbc.co.uk`

**Question 2:** *Ping muirlandoracle.co.uk*
What is the IPv4 address?

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1660547820674/_vTde2fKp.png align="left")
Since, we're searching for IPv4 address, we have to use `-4` before `muirlandoracle.co.uk`.

> 217.160.0.152


***For the following questions, it's time for using `man ping` command.***
<iframe src="https://giphy.com/embed/zcLSzR6aFaK1a" width="480" height="269" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/cat-cute-ping-pong-zcLSzR6aFaK1a">via GIPHY</a></p>


**Question 3:** What switch lets you change the interval of sent ping requests?

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1660547778225/M8YElaKeC.png align="left")
> -i

**Question 4:** What switch would allow you to restrict requests to IPv4?

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1660547640831/nKG-0CbH3.png align="left")
> -4

**Question 5:** What switch would give you a more verbose output?

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1660547797351/CNPWDz9zW.png align="left")
> -v

---

## Task 6 : <mark>[Networking Tools]</mark> Traceroute
In this task, you're gonna learn about an interesting tool called `traceroute`.
The logical follow-up to the ping command is 'traceroute'. Traceroute can be used to map the path your request takes as it heads to the target machine.

**<u>Answer the questions below</u>**

**Question 1:** 
Use traceroute on tryhackme.com

Can you see the path your request has taken?

*Hint:- Use `traceroute tryhackme.com` in your terminal and you'll see 12 hops to get from my router `(_gateway)` to the TryHackMe server at 104.22.54.228*

> No answer needed

***For the following questions, it's time for using `man ping` command.***

**Question 2:** What switch would you use to specify an interface when using Traceroute?

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1660551725383/0u0LNMZjG.png align="left")
> -i

**Question 3:** What switch would you use if you wanted to use TCP SYN requests when tracing the route?

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1660551705042/fOMeOHiVE.png align="left")
> -T

**Question 4:** **[Lateral Thinking]** Which layer of the TCP/IP model will traceroute run on by default (Windows)?

*Hint -> Just **Google** it.*
> Internet

---

## Task 7 : <mark>[Networking Tools]</mark> WHOIS
In this task, you're gonna learn about an interesting tool called `whois`.

**Whois** lookups are very easy to perform. Just use `whois <domain>` to get a list of available information about the domain registration and other useful information about the target domain.

**<u>Answer the questions below</u>**

**Question 1:** **Perform a whois search on `facebook.com`**

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1660553905224/6jbMvtOq6.png align="left")
You'll get a lot of information like this about the domain.

> No answer needed

**Question 2:** What is the registrant postal code for facebook.com?

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1660554097997/T993YuQ54.png align="left")
> 94025

**Question 3:** When was the facebook.com domain first registered (Format: DD/MM/YYYY)?

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1660554048903/deawtfAwR.png align="left")
> 29/03/1997

**Question 4:** **Perform a whois search on `microsoft.com`**

(Note: If you fail to read the above instruction and consequently get the wrong answer for the next question, don't expect a helpful response if you report it as a bug...)

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1660554135120/7ZlEhp2cr.png align="left")
You'll get a lot of information like this against the domain.

> No answer needed

**Question 5:** Which city is the registrant based in?

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1660554237630/Y3-eAvFEI.png align="left")
> Redmond

**Question 6:** **[OSINT]** What is the name of the golf course that is near the registrant address for microsoft.com?

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1660554456785/ZF7C-yFDZ.png align="left")
Let's use the above address info and do a google search.

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1660554584775/dnssLCuSZ.png align="left")
Now let's go to the maps to see the location.

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1660554642436/Cva0jXUfl.png align="left")
Now click on Nearby button and search **Golf Course**. The nearest thing we can see is:

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1660554788095/r_43-dCBD.png align="left")

<iframe src="https://giphy.com/embed/Fka9XXT8NrHv66rQaX" width="480" height="480" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/peacocktv-Fka9XXT8NrHv66rQaX">via GIPHY</a></p>

> Bellevue Golf Course

**Question 7:** What is the registered Tech Email for microsoft.com?

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1660554372023/CtFSs31h4.png align="left")
> msnhst@microsoft.com

---

## Task 8 : <mark>[Networking Tools]</mark> Dig
In this task, you're gonna learn about an interesting tool called `dig`.

According to TryHackMe:
> When you visit a website in your web browser this all happens automatically, but we can also do it manually with a tool called `dig`. Like `ping` and `traceroute`, `dig` should be installed automatically on Linux systems.

> Dig allows us to manually query recursive DNS servers of our choice for information about domains:
`dig <domain> @<dns-server-ip>`

> It is a very useful tool for network troubleshooting.

**<u>Answer the questions below</u>**

**Question 1:** What is DNS short for?
> Domain Name System

**Question 2:** What is the first type of DNS server your computer would query when you search for a domain?
> Recursive

**Question 3:** What type of DNS server contains records specific to domain extensions (i.e. *.com, .co.uk*, etc)*? Use the long version of the name.
> Top-Level Domain

**Question 4:** Where is the very first place your computer would look to find the IP address of a domain?
> Local Cache

**Question 5:** **[Research]** Google runs two public DNS servers. One of them can be queried with the IP 8.8.8.8, what is the IP address of the other one?

<iframe src="https://giphy.com/embed/gLnZ2mo2dGcLK" width="480" height="270" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/madonna-look-it-up-gLnZ2mo2dGcLK">via GIPHY</a></p>

> 8.8.4.4

**Question 6:** If a DNS query has a TTL of 24 hours, what number would the dig query show?
> 86400

---

## Task 9 : Further Reading
It's a wrap up task and you can read more in details on your own. Internet has many doors open for you.

Go and enjoy.

<iframe src="https://giphy.com/embed/fQx7FeYapEpzUDyyfR" width="480" height="270" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/flying-door-in-the-sky-fQx7FeYapEpzUDyyfR">via GIPHY</a></p>

> No answer needed

---

<iframe src="https://giphy.com/embed/LpQrsRA3zOuJNk7KYt" width="480" height="270" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/somegoodnews-we-did-it-wedidit-its-done-LpQrsRA3zOuJNk7KYt">via GIPHY</a></p>

All credits goes to [TryHackMe](https://tryhackme.com) and [MuirlandOracle](https://tryhackme.com/p/MuirlandOracle)

Check my profile on TryHackMe: https://tryhackme.com/p/Susmita.Dey

## Hope this helps you. Thank you for reading, and let's connect!
Thank you for reading my blog. Feel free to subscribe to my [YouTube Channel](https://www.youtube.com/channel/UCsuzc8lqAbgUYo4yzpjtfSw) and connect on [LinkedIn](https://www.linkedin.com/in/susmita-dey-15a15a210/) or [Twitter](https://twitter.com/its_SusmitaDey).
Also, feel free to [support](https://www.buymeacoffee.com/susmitadey) my work.😊

<a href="https://www.buymeacoffee.com/susmitadey" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 20px;width: 20px;" ></a>

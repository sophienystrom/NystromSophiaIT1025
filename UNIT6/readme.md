# Executive Summary
* Include your executive summary here...

This week (week 6) in Intro to IT the main topics of the lab are based on further networking structure and further cybersecurity. Relating to networking, or as it says internet architecture, we are diving into the differences in IP addresses and how to find them using our operating systems command prompt. This week is a true discussion about the fundamentals of the internet, such as URLs, and also a deeper analysis of security (where last week we did encryption, this week is a different type of focus).  

# Internet Architecture
## Internet Protocol
* What is an IP address and what is the difference between IPv4 and IPv6?

An IP address (internet protocol addre ss) are numbers that are assigned to a computer network. Basically, an IP address are how computers can send data to the correct locations at the other end of their conection. You can kind of see it as someone sending mail to a home address, it is specific. IPv4 is the original version of Internet Protocol, the first stable generation. IPv6 is the new and refined generation of Internet Protocol that is supposed to replace the older IPv4 version. IPv4 requires a lot of ass-ons (ICMP) to function properly which is makes it mildly unreliable relating to the explosion of internet usage that has been taking place over the past decade, which IPv6 can handle. IPv6 also offers more efficicent routing with no packet fragmenting, built in network security, and an improved header structure. A big difference between the two is that IPv6 uses a multicast group system and IPv4 uses a broadcrast group system, so basically IPv4 forces each device to look at packets and IPv6 does not. 

* Find the IP address of your computer by typing ipconfig at the command prompt (refer back to the "Operating Systems" module for details.) Take a screenshot of the command without including the IP address to show your success, name the file ipconfig and upload to the lab folder on GitHub.

* What is ICANN and how do they contribute to the global Internet?

ICANN is a non-profit global community that focuses on keeping the internet secure and stable by promoting policy develpment for the internets identifiers. ICANN affects the gloval internet by creating contracts with registries and registrars that define the expansion and growth of a domain. ICANN also helps people understand internet governance and promotes conversation about topics like internet security and the digital divide. They want to allow users of the internet to have a say in how the internet is run. 

# TCP/IP
#### Review the first article and answer these questions:
* What is the responsibility of TCP/IP?

The responsibility of TCP/IP is to govern the connections between computer systems which use the internet. TCP/IP can be used to govern public or private connections. IP itself delivers packets of info from device to device, IP doesn't handle packet ordering or error checking though. The job of TCP is just that, packet ordering and error checking.

* Explain how the client-server model applies to TCP/IP

The client-server model refers to computers connected in a communication network where servers manage the database and clients gain access through that server. Relating to TCP/IP the client server model applies since TCP/IP is the standard why for clients and servers to exchange data packets. Client-server applications use TCP/IP to communicate basically. 

#### Review the second article and answer these questions:
#### Review the section of the article aligning the post office with protocol stacks.

* Why are layers important to changing technology?

Layers are important to changing technology because they allow the approach to be more flexible (since there is more than one protocol stack). Layers are able to be changed without actually effected other layers, information passed in a different way will not actually change or affect the data package. 

* What types of applications run on the "application" layer?

Applications that run on the application layer are responsible for having protocols that focus on communication across an IP network. For example, the FTP or file transfer protocol transfers files between computers and networks. 

# Internet Security
#### Watch the video and answer these questions:
* What is HTTP and how does it support the client-server model?

HTTP is the protocol used to view web pages, it is the largest used protocols to recieve web server information. HTTP supports the client server model since the browser must send an HTTP request to the server for data exchange to occur. Web servers reply to w web browser using an HTTP response message. As you can tell, HTTP is key in the client-server model when dealing with internet relation. 

* Explain the protocols that secure HTTP uses to protect data.

HTTPS is HTTP with a security feature. Basically HTTPS encrypts all data that is being transferred so it is impossible to read. They do this by using SSL (secure sockets layer) which is a protocol that uses a public key encryption to secure data. Basically the server asks the website to certify their ID and the SSL certificate is trusted by the computer browser, the web server will then allow the exchange of data. TLS (transport layer security) is another secure protocol. 

#### Review the following article: Securing Your Web Browser
* Why should you secure your browser?

Not securing ones web browser can lead to a handful of issues. For one, spyware or hackers can steal you personal information such as youre home address, phone number, or credit card information. If you do not secure your web browser you are more at risk for software attacks or hacks which can cause random web addresses to lag out your computer. 

* Explain one of the risks described in the article.

By not securing your browser a big risk comes with hackers availability to your client-side systems AKA computer. Hackers can steal or look at files, even use your computer to attack others, or even render your computer incapable of working the way it should. If you just leave your browser unsecured it would be very easy for one to get into your computers database. 

# Internet Programming
Upload screenshots of your html, css and result
#### Answer these questions

* Who was Tim Berners-Lee and why did he create the W3C?

Tim Berners-Lee is the creator of the World Wide Web (or WWW) circa 1989. W3C is a web standards organization that develops technology specifications and guidelines which lead the web to its full potential. He launched W3C to further the reach and future of the WWW to benefit the world. 

* Pick a "standard" of your choice and explain why it is important.

The standard of my choice relates to web design and applications. Web design and application standards focus on the building of web pages (like HTML) and includes info on the imprtance of making pages accessible to all people- such as those with disabilities or those who are international. This is important because the web should be able to be accessed by all regardless of who or where they are, this goes along with furthuring the future of the web.

* Explain how XML differs from HTML.

HTML is the language used for the structure of web pages. HTML allows people to publish online documents, retrieve info, design forms, and include sounds and video clips in documents. Basically, HTML lets web owners to structure their page and to design it. XML on the other hand is HTML using a XML syntax, instead of the normal markup syntax. XML also allows other language transforming content to be used along with it. The biggest difference between the two is that HTML is based off of presenting data and XML is used for storing data or transferring it. 

# URLs and File Paths
Match the following terms / definitions under the heading and explain how they are related by providing an example of all of the pieces of a URL: Terms: scheme, domain, top level domain, default page, parameters, anchor Definitions/examples: .edu, no file path provided, result of search, https, www.amazon.com, specific location on a page.

* What is your understanding of difference between Absolute and Relative File Paths. What would you use in your website? Why?

An absolute file path is a type of path where the path is complete from the start of the file system from the directory. The absolute path provides a full listing of the locations of a file on a computer, it has the complete location but not the drive. A relative file path is one where the location is listed where it is relative to the current directory (which translated back to the parent directory), not including the domain name. Personally I would use a relative path because I would be able to change my domain name but the links I would originally have would still be able to work with no need to modify them. Absolute paths ALWAYS have the domain name, which may make it easier for one to be sure of the site, but I personally see that as a lower hand to the relative file path. 

* Explain the purpose and use of file compression.

File compression is used to make large files or data packets compressed so they can be easily managed, take up less space, and speed up transferring. The uses of file compression (and benefits) are listed in that first definition sentence. Compressing files just makes it easier to store and also can lower retrieval time in regards to your own computer. 

# Conclusion
* Include your conclusion here...

In this weeks lab I learned a lot about the build of a website/URL and the importance of security on the internet. What I found really cool about this lab is that I have just started realizing how many sites actually use HTMLS over a normal HTML. For example, I see both github and Microsoft Support use a secure browser over the general unsecured one. I never really understood how URLs and websites were adapated and created so this lab was really informing on that. I loved getting to look further into IP addresses and how they can be used. 

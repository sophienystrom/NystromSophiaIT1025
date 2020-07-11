# Executive Summary
* Explain the goal for this lab

This week in intro to IT (week 5) we are diving into ideas relating to cybersecurity, encryption factors, and very in depth on networking and the main ideas revolving around the topic. An interesting part of this lab is an introduction to using the application LucidChart which will allow us to create charts for computer programming. I am personally excited to learn about the different aspects of networking, since I truly do not have a lot of knowledge on it myself. All in all we are focusing on the big topucs of: LucidChart introduction, networking ideals relating to data transmission and toplogy issues, and basic cybersecutiy ideals like authentication. 


# LucidChart
Create a new blank diagram (ignore message boxes to upgrade) and create a flowchart for a computer program that asks for a number and then 

* prints "Big" if the number is greater than 10
* prints "Small" if the number is less than 10. Use the following resource (or one of your choice) as a guide: https://www.tutorialspoint.com/programming_methodologies/programming_methodologies_flowchart_elements.htm Add a textbox to the chart with your name
* Download your chart as a jpg file and name it: DecisionFlowchart and upload the file to your GitHub lab folder

* Share your experience using Lucidchart in a paragraph (3-4 lines)

Using lucid chart for the first time was quite intersting. I have never seen or used the application before but it was nice to see the computer science programming application it had, amongst other things. I feel that lucid chart can be used not just for programming but also for the scientific process and the forming of hypothetical theories. In short, LucidChart is very easy to use and I enjoyed making the simple flowchart for our assignment!

#Networking
##Intro to Networking
Data Transmission

Match the following words with their definitions

Words: Packet Packet-Switching IP Address DNS Protocol

Definitions to match: Set of rules to allow devices to communicate Unit of data Unique identifying number Technology that allows packets of data to be routed based on destination address Directory of IP address common names. (For example 54.239.26.214 might be the IP address of amazon.com)

Packet-Switching: technology that allows packets of data to be routed based on destination address
Packet: Unit of data 
IP Address: Unique identifying number 
protocol: set of rules to allow devices to communicate
DNS: Directory of IP address common names

## Network Hardware
* Explain the benefit of a switch over a hub.

A switch is used to connect various network segments usually at a layer 2 data link. A hub connects various ethernet devices together (like a string) by having multiple ports where all in the LAN see the data packets that arrive. Switches are better than hubs because switches transmit data to a SPECIFIC network while hubs transmit data to all devices in its network. For large networks switches are also better because switches can cut out heavy networking traffic, it is less congested, even though hubs provide more ports for extension.

* Explain the benefit of a router over hubs and switches.

Routers are usually connected to more than two networks (e.g two LANs) in the gateway of where the networks actually connect. Routers determine the best paths for packet forwarding and comunicate using protocol to do so. Routers are better than hubs because hubs have really no way of seperating which port frame they are sending data to. Routers are better than switches because routers let you share a single IP address amount multiple networks (this goes as a plus over hubs as well). Routers can be used in different networks (not just LAN) such as MAN and WAN, which is also a plus. 


## Network Topology
* Explain: Single point of failure and the topologies that experience this issue.

A single point of failure is a risk that can cause an entire system to malfunction due to a small flaw in design or configuration. This could be a software failure or a discreptancy in programming. For example, apple maps had one small programming issue which caused the entire application to be unreliable. The topologies that experience this issue are bus topologies which can cause a network failure if there are missing terminators (signal reflection) or if a computer is missing. Another topology would be the ring topology, which connects all computers with a single 'line'. If any of the computers went down or a cable went down all data transferring would stop. 

* Compare the Infrastructure Topology and Wireless Mesh. Which do you think is better and why?

Infrastructure topology uses wireless and wired devices (physically connected by cables). The wireless access point is bridge for laptops, tablets, and phones to be a part of the topology. Infrastruture topologies are able to have multiple access points. Wireless mesh connect devices by cables but interconnectly are wireless. a wireless access point is connected to a switch but the other access points are not connected at all, the data is relayed from access point to access point until they go to a switch. I personally believe that a wireless mesh topology is better because even though it is more expensive and complex to set up the redundancy is very reliable and the constant communication between access points to eachother and the switch make this type of topology network very useable and make it so one does not have to worry about single point failures stopping data flow. 


# Cybersecurity and Encryption
* Imagine you are part of the Amazon.com online chat. Explain how each component of the security triad would impact your job

Confidentiality in the security triad refers to the protection of information which allows only those who are supposed to see it to view it without any extra information being learned. This could impact ones job in an amazon.com online chat because it would bar one from giving information to an unauthorized user. For example, if someone is asking about specific account information (such as a password or address) without giving any authentication of if they are that person. 
Integrity in the security triad refers to the guarantee that information has not been altered or messed with and truly shows what it is supposeed to. This could impact ones job in an amazon.com online chat because one could accidentally change account information without meaning to or even get bribed or convinced to put specific information on ones account that gives them an upperhand on the site due to a data change. 
Availability in the security triad refers to the ability of information to be accessed by anyone with the correct authorization to do so in a certain timeframe. This can impact ones job in an amazon.com online chat because someone may have placed an order they need to cancel and to do so they would need to reach an amazon worker, therefore one would have to be available at all times to help those when they need assistance in data accessing. 


* Identify three daily tasks that require authentication. Explain how each one could be converted to multi-factor authentication

Three daily tasks that require authentication are: Using a passcode to open your phone, unlocking a car door with a key, or swiping a work ID keycard to get into a building. 
Unlocking a phone can be changed to multi-factor authentication by requiring facial recognition (newer phones) or a fingerprint along with a passcode.
Opening a car could be changed to multi-factor authentication by not only requiring the key to physically be in the door lock but also the actual wireless unlock button to be pressed (if applicable). 
Getting into a work building can be changed to multi-factor authentication by not only requiring a key card to get in, but also requiring a call in over through a PA to confirm name, voice, and desired location or even a front desk employee sign in.

* Explain ACL and RBAC. What are the advantages and disadvantages of each?

ACL or access-control list is a list of permissions attached to an object that specifies which users in a system have specific access to it. Every file has access right info on it. The pros of this is that it is easy to check what users have access and all in all it is an easy expression of permissions. The downside to ACL is that it is really difficult to give users permission or remove permissions on a multitude of files since the lists are on every single file.
RBAC or role-based access-control restricts access in a network based on roles that indivisual users have. The pro to RBAC is that it lets employees or other users have access to the exact information they need to do their job, they only have the access rights to specific information. The downside to RBAC is that priviledges are assigned to users but not to operations within the network itself. Another downside coul dbe that you cannot restrict access of certain data. 

* Explain the interaction of ciphertext, a public key and a private key

A public key maages identity and security in internet ommunications by using algorithms that protect identities and data from being accessed by unauthorized users (guards from cyber attack). Public keys use a string of random numbers for encryption that can only be deciphered by the associated private key. A private key is a decryption key used to decrypt private encrypted text for users to view. Ciphertext is the encrypted form of a text after a public key encrypts a file. So basically, public keys encrypt text to ciphertext and then a private key derypts that ciphertext to normal text. 

* Explain why we need public key cryptography.

Public key cryptography makes it very simple for authorization and access to encrypted files. For other versions of cryptography one has to give the description key to the recipient, but with a public key the reipient already HAS the private key they will use. Public key cryptography ensures confidentiality and privacy within communication. This type of cryptography can also verify identities. In the end it not only confirms the triad of cybersecurity but it is generally easier and more secure than some other forms of cryptography. 

## Cryptography
* Type a message in the "Caesar Cipher Exploration box and turn the wheel to encrypt your message. Then explain the encryption here:

I typed: computer science is interesting
encrypted message: jbtwbaly ziplujl pz pualyzlazapun
basically, the encryption alters the original text so it is not readable or viewable to a unauthorized user. Encryption can add random letters and numbers and rewrite the message in a way where you can't understand what it says unless you have the key to unlock it. 

* Type a message in the "Frequency Fingerprint Exploration" box and a) Explain the result. b) Would it be different for different languages?

The message I typed was: never ever again will I work a Friday shift by myself.
My results showed that I mostly used the letters E, R, A, and I and had a lower frequency with other letters in the sentence. 
It would definitely be different in a different language. Languages around the world play with vowels and constanants in a way that is not the same as the English language. My message or "fingerprint" was very skewed, since it was the purpose of encryption relating to it would try to flatten that frequency. Languages have a differed frequency when it comes to letter usage. For example, if it were in Russian I would expect a heavy frequency of constanants while if it were in Arabic I would expect a number of vowels. 

* What is a "Polyalphabetic cipher?" Type a message in the "Polyalphabetic Exploration" box as well as a shift word. Explain the result.

A polyalphabetic cipher encrypts a message by using a shift word to find alphabetic placement (number in alphabet). Those numbers are repeated through the entire message and the letters are shifted depending on the number below it. To decrypt the message one has to subtract the shifts. A flatter frequency makes it harder to decrypt the message, a difference in letter frequency show that there is a leak in information. The longer the shift word the stronger the cipher

The message I typed: Lucidchart is a cool website
shift word used: hippopotamus 
encryption: tdsysswusg di i leea mtvtvox

I used a longer shift word so therefore my encryption has been shifted multiple times by the alphabetical numbers of the word hippopotamus. As I explained above the frequency of my encrypted message should not be very skewed, although in my example it sort of is. 

# Brute Force
* What is Brute-Force and how does it relate to Kerckhoffs's principle?

Brute-Force is a cryptoanalytic technique that tries every possible decryption key for a cipher. Kerckhoff's principle states that a cipher should still be secure even if everyone understands how it works and if someone has the ciphertext. Brute-Force relates to Kerckoff's principle because it shows how not all ciphers are reliable in secret information encryption and therefore not secure. They relate since Kerckhoff's principle talks about being secure even with knowledge of the cipher. 


# Conclusion
* Summarize how this lab was useful to you and what you learnt that really interested you!

In this weeks lab I learned an absolute ton about cybersecurity and networking. Cybersecurity has always been a main interest of mine and it was very interesting to get an in depth understanding about how it works in different ways. I truly loved learning about cryptography, and the aspect of the lab where we explored encrypting messages was probably my favorite part. I really had no clue that there were so many different versions of network topology and how for some it is so easy for a network to fall. The introduction to LucidChart was also nice, although I will be honest it was not my favorite part of the lab. All in all I am really happy with what I learned and I'm excited to see what it on the agenda for next weeks lab!

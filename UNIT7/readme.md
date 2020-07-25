# Executive Summary
* Talk about what the goal of this lab is !

In week 7 of Intro to IT for Computer Programmers the topics we are covering get increasingly more in depth of informational technology. Main topics (as seen as bold headers) include object oriented concepts, basic catgeories for data and structures query languages, and IT/computer ethics. In the object orientation concept we will be looking over the creation of class charts and the what details fit into them (features, actions, etc). Data in this weeks lab covers two main topics: relational data and big data- which will both be looked over in depth with categories within themselves further telling them apart and explaining them. Structured Query Language will also be covered and mildly ties into our cybersecurity lesson from last week and the week before. Another topic in this weeks lab that we will take a deeper look into is ethics concerning computers and networking. An interesting part of this lab will be the explanation of another computer organization and what they do in regards to computer ethics around the world. In short, this week we are going over new topics relating to charting programming, understanding data, cybersecurity, and morality. 

# Object Oriented Programming
* Create a class (using paper and pencil or using the Microsoft whiteboard app) for the following: a) Phone b) House c) Employee
* Identify the features (In the video for the Car class, we identified the properties as Year, Make Model etc)
* Identify the actions (In the video a) for the Car class, we identified the methods as Drive, Park, Start etc)
* Then upload a screenshot of your diagram to github for each of the above classes.

# Data, Information and Knowledge
## Relational Data
* What is the difference between data, information and knowledge?

Data are the bits of information that generally do not have a set context. Data can be quantitative- numeric, can be measurements or amounts- or qualitative- characteristic, can be features of descriptions. An example of quantitative data could be: 13 inches by 12 inches (there is no context) and an example of quantitative data could be: grey and fluffy.
Information is basically data but with context. For example, using our quantitative data example one could transform that into quantitative information by saying: The box to pack the headset is 13 inches by 12 inches. To convert out qualitative data example to qualitative information we could say: The little bunny was grey and fluffy. As you can see, information is applied data which makes it more in depth and specific. 
Knowledge defined simply is the grouping of bundles of information which makes one informed on a topic. Knowledge can help people in conversation, decision making, or even the scientific process. For example, knowledge regarding our quantitative/qualitative information could go as follows if we were given more: The box to pack the headset is 13 inches by 12 inches, the box is made out of blue cardboard with a grey fluffy bunny on the front, and has a detailed explanation of the headset on the back. With all of this information one is knowledgeable of the box that the headset will be packed in. 

data fragments --> specified --> information --> groups of information --> knowledge 

* If you were creating a database for a small company and two tables you identify are customers and orders explain the following: (be sure to use the example in the chapter as a guide - customers and orders would be like clubs and events) 
a) What would be the primary key in the customers and orders table?

In the customers table the primary key should be a customer ID. Giving a customer ID to each buyer will allow them to have a unique and personal numerical addresser that is linked to their account. Using an ID as a primary key is feasible because it will be a one-of-a-kind identifier and will not overlap with other's information. For example, using names as a primary key is not a good idea because 1. many names are frequent and can be the same and 2. names can be legally changed! An ID will be for the companies organizational use and will automatically be assigned to customers when they put in information for orders. In the orders table the primary key should be an order ID affiliated with the specific order a buyer is purchasing. Having the order ID as the primary key will allow the managers of the orders in different ways. For example, a manager can confirm that a product is associated with the correct ID. 

b) How would the customers and orders table be related?

The customers and orders table would be related because both would have the customer ID to connect the two's data/information, you could say the orders foreign key relates the tables. If one sees an order that has an issue all they would have to do is find the associated order ID on the orders table and then the customer ID which will be down the line. Vice versa, if one was wondering what specific orders one has purchased in the past or future all they would need to do it find the customer ID on the orders table (which may show up more than once) which will go across to the specific order itself. Customers purchase orders which are displayed on the orders table. 

c) What would be the foreign key in the orders table?

The foreign key in the orders table would be the customer ID from the customers table. The foreign key relates the primary key of the main table to the second table and in our case the customers table is the main table and the orders table is the secondary table. Very basically, the foreign key is the main relation between the tables (you can sort of see that explanation in the above question). If one is looking at the order table and wants to know the customer's info they can use the ID on their table to go to the customers table. If one is looking at the customers table and wants to know a customer's order they can use the customer ID to go to the orders table. 

d) The orders table would likely have a date field. Explain why it is important to properly define the data type of a field.

It would be important to define the data type of a field for two main reasons: storage space and functions. If you define a data field and allow it to have a maximum of characters over how many you actually need then regardless of using less than the max, every single time you have a data input in that field you will be storing the FULL amount of data bits pertaining, which add up. For example, a general date field is in mm/dd/yyyy format which is only 10 characters. If, per se, someone defined this data field to allow 25 characters then everytime a new date is added 25 bits are stored, which is an extreme waste of space since you only need 10. Defining the data type in relation to actual function is also an extremely important reason to do it properly. Data types tell what you are allowed to do with associated data. For example, the date field in the orders table should be defined as a date/time data field because this will allow the format to be interpreted correctly as a date or time, whilst if the date field was labeled as a object you would not even be able to type any format because the function of an object data field is to allow photo/file attachments. In our case (the orders table) the date field will be extremely important in proper shipping/organization and having the wrong data type can mess up the formatting and therefore not only the storage - making it less efficient - but also the character text itself.  

# Big Data
* Briefly describe the four "Vs" of big data

The four V's of data goes as follows: volume, variety, veracity, and velocity. 

Volume basically refers to the "big" aspect of big data and the fact that data is always growing and being stored, tons and TONS of data/bits/information are generated every year at an exponential rate. Volume explains how data is getting "big" and calls for the need for new complex data saving software in the technology field. 

Variety points to two main units of big data, which are structured and unstructured. Structured data is data with specific "rules" (per se). An example of this could be how dates have a certain formatting or how when dealing with money the text is always solely numerical. Structured data is the traditional data style and usually is made sense of easily. Unstructured data is data that does not follow a meta model (rules). Examples of unstructured data are voicemails, audio memos, or photos. Unsutructured data is a large idea in Big Data because it is what is strived to be understood since it does not fit as nicely as structured data.

Veracity refers to the fact that there may or may not be discreptancies in data, espcially when you are dealing with a enormous number of it. Veracity really bases off how trustworthy these big data packs are and the acknowledgment one has to make that not all of it will be 100% accurate. 

Velocity relating to data is the amount of data that is constantly coming in that has to be processed. Data is ALWAYS incoming, imagine how much gets stored in one day from credit cards, online applications, photos, etc. Velocity is the speed of data processing and since there are over 19 billion network connections in the world this is a growing topic and concept regarding big data. 

* What types of technology have driven the increased need for big data?



# Structured Query Language (SQL)
* Explain RDBMS and how it relates to SQL and the purpose of SQL
* Pick two related tables from the diagram provided in the "module - SQL" and explain the relationship between them a) which is the primary key? b) which is the foreign key?
* Using W3Schools, try out a a) select statement a) where clause and upload screenshots of the results.
* Explain how SQL injections are a security threat and what can be done to reduce the issue.
# Ethical and Legal Implications of Information Systems
## Code of Ethics
* Explain the purpose of a "code of ethics" and why the ACM created a code for the computing discipline.
* Explain the difference between a code of ethics and AUP (acceptable use policies.)
* Pick a site of your choice and read the AUP. Select a policy of interest and report your findings (include a link to the site in your report.)
# Intellectual Property
* From the chapter follow the link to the WIPO. What is the purpose and importance of the WIPO?
* Using links in the chapter explain how a copyright is obtained and the benefit of registering for a copyright with the US Copyright Office. Explain why it might be important to copyright the svg image you created.
* If the svg image you created became an item that identifies a source of goods or services, explain the role of a trademark in defining the intellectual property.
# Information Collection
* Explain how COPPA, FERPA and HIPPA restrict the collection of information on the Internet.
# Conclusion
* Include what you have learnt from this lab

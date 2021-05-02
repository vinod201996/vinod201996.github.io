PUBLIC HOTSPOT. 

***Abstract***

Public Hotspot  is one of the fastest growing segments of Smart City solutions which solves the problem of poor internet connectivity provided by service providers. Everyday each one of us faces difficulty in receiving a proper internet connectivity. The solution to this is provided by smart city solutions which aims at achieving a city wide free Wi-Fi for the citizens. This whitepaper provides a beginner’s overview of what a smart parking solution is, its typical components and technologies along with a real life example of one such implementation of public hotspot in a restaurant. Read Further..

**Introduction**

`                `In today’s modern world everyone needs an internet connection. Life without internet is unimaginable. From a survey conducted across the globe Internet users have passed the mark of 4 Billion, this means over half the world’s population is online. An average American spends 6hrs on the internet. Due the concept of smart cities, most of the developed cities have Free Wi-Fi and it has become has become easier to get access to internet anywhere. According to a survey, it is found that nearly 78% of people use free Wi-Fi and about  72% among those prefer going to places which provide free Wi-Fi. For this reason, developing cities or towns where the concept of free Wi-Fi has not taken roots, various institutions, shops, malls , cafes have opted for there own public hotspots. A public hotspot provides internet access to the users through authentication of the users.

`               `A public hotspot can prove beneficial for the providers in many ways. According to a statement by a Restaurant owner, it was stated that the number of customers were increased when a public hotspot was introduced inside a Restaurant. As people are using social media to a great extent, a free access to internet adds a cherry on the top. 

![Public-FINAL.jpg](Aspose.Words.d602b339-726a-4b7d-b80b-7e5973802b7c.001.jpeg)

A public hotspot can be set up as marketing platform to showcase the new products and services introduced by the company. Such an advertising platform can prove profitable for the organization as a bunch of people will use their free Wi-Fi.  

![maxresdefault.jpg](Aspose.Words.d602b339-726a-4b7d-b80b-7e5973802b7c.002.jpeg)

**Architecture**

Public Wi-Fi hotspot uses a Wireless router which creates an access point for users to connect. A wireless router is an networking device which sends data packets between computer networks. Router acts as medium between users and the central network through which the authentication is carried out. 

![otp.jpg](Aspose.Words.d602b339-726a-4b7d-b80b-7e5973802b7c.003.jpeg)

The design is detailed as follows:

1. **Wi-Fi Router**  

The functions of Wi-Fi router is as follows:

1. Creates an Access point for users to connect.
1. Connects to web server and displays the authentication page received from the web server to the user.
1. **Web server** 

The functions of Web server are as follows:

1. To host an authentication page for users.
1. To notify OTP generator to generate and send an OTP to the user.
1. To send the entered OTP for verification.
1. Save the data incoming from the user.
1. Providing Internet access to verified user.
1. **OTP Generation & Verification**

The function of this block is as follows:

1. Generate an OTP.
1. Send it to SMS Gateway.
1. Verify the OTP sent to user with the OTP entered by the user.
1. **SMS Gateway** 

The function of this block is as follows:

1. To send the OTP received from OTP generator via SMS to the user entered mobile number.

**How does a Public Hotspot Work?**

- Users in the locality of the hotspot connect to the network through their mobile phones or any other devices.
- When a new user connects to the Wi-Fi router, an authentication page is called from the web server and is displayed to the user. On this page user has to enter his credentials such as name, email, mobile number etc.
- After the user enters all the required credentials and submits it Wi-Fi router sends this data to web server.
- The web server notifies the OTP generator to generate an OTP.
- The generated OTP is sent to SMS gateway which forwards the OTP to the user entered mobile number. 
- User enters the OTP on the authentication page for verification and submits it.
- The user entered OTP is sent to web server which forwards it to OTP verification module to get it compared to the OTP generated and sent.
- ` `Once the OTP is verified, OTP generation & verification module sends a confirmation to the web server.
- The web server then grants the internet access to the user and stores the data of the user.
- The data from the user is stored for 24hrs only. Past which user has to go through the same process again.



**Technologies to realize a public hotspot**

The technologies used to realize public hotspot are considered based on various factors such as infrastructure, type of deployment(Indoor/Outdoor), cost considerations, features required etc. 

For the designated blocks the technical information is displayed as follows:

|**Modules**|**Technology Used**|
| :- | :- |
|Wi-Fi Router|Router is chosen on the basis of open source software it can support. Generally TP-Link routers are preferred.|
|Software used inside the router|Open source software like Openwrt, DDWRT, Tomato etc can be used.|
|Web server|Paid servers like Hostinger can be used. Or local server can be created using Xampp.|
|OTP generation & Verification|OTP generation and verification code could be written in Java or any other language.|
|SMS Gateway|SMS service providers like textlocal, Bhashsms can be used. |

`                        `The most important technology used in creating a public hotspot is the Open source software used inside a router. A router has a pre-installed operating system which is called as a stock firmware. The stock  firmware has limited functions. The open source software provides a bunch of functions which helps to realize a public hotspot. Every open source software has a list of hardware devices on which it supported. It is advised to purchase the router in accordance with table of hardware and the infrastructure at which it is required. 

**Conclusion**
**
`           `As the demand for internet increases the necessity of a public hotspot will increase. In the process of urbanization, most of the cities and townships are on the verge of being developed and having a city wide free Wi-Fi is one step towards it. The process of setting up a free Wi-Fi will depend on various factors such as the area of the city, deployment, software, router types and much more. The further improvement of a public hotspot can be done by acknowledging the user feedback and implementing the corrections required to provide a fast and a free internet access.




# <span style="color:#CD5C5C	">OSI Layers </span> 
* ###  Summary
* ###  Introduction
* ### Application layer
* ### Presentation layer
* ### Session layer
* ### Transport layer
* ### Network layer
* ### Data-link layer
* ### Physical layer
* ### References 
<p>

---
</p>

##  Summary
<p>There are 7 layers in the OSI reference model and they are represented as below.</p>

<img src="https://www.tutorialspoint.com/assets/questions/images/192829-1531475190.png" alt="OSI Model"/>

<br/>

<p>

OSI model is designed to understand how data is transferred between two computers. Consider there are two computers connected via LAN but both the computers are using different operating systems, then how these two computers are going to communicate with each other?
To establish better communication between two networks or computers, 7 layered Open Systems Interconnection (OSI) model was proposed by International Organization for Standardization (ISO) in 1984.
</p>

<br/>

---

##  Introduction
<p>
OSI layers are the package of protocols and perform certain actions. A network protocol is a set of rules and conventions which govern the communication between two devices on a network.
Before the OSI-model was introduced, many network devices or computers were having issues with connection and unable to work with one another due to the lack of a set of common standards or protocols.
<br/>

The OSI-model is not just a seven layered model to make networks suitable; it’s also one of the **BEST** ways to make people learn about networks.</p>

<br/>

---

##  Application Layer
<p>The top layer of the OSI-model is called the Application layer. It is implemented by the network applications like Chrome, Firefox, etc.
These applications make the data that is transferred over the network.
This layer also serves as an application to access the network and display the received information to the user.

There are four functions of the Application layer:
* ####  Network Virtual Terminal
* ####  FTAM-File transfer access and management
* ####  Mail Services
* ####  Directory Services 
</p>
<br/>

---
##  Presentation Layer
<p>The Presentation layer it's also known as the Translation layer.
The data from the application layer is converted into the required format to transmit over the network.

There are three functions of the presentation layer:

* ####  Translation
* ####  Encryption/ Decryption
* ####  Compression
</p>
<br/>

---
##  Session Layer 
</p>The Session layer is responsible for the establishment of connection, maintenance of sessions, authentication, and also ensures security. It is also known as the software layer.

There are three functions of the Session layer:

* ####  Session establishment, maintenance, and termination
* ####  Synchronization
* ####  Dialog Controller
</p>
<br/>

---
##  Transport Layer 
<p>It takes data from the Network layer and provides services to the Application layer. The data in the Transport layer is referred to as Segments. It is responsible for end-to-end message delivery.

The Transport layer has two functions:

* ####  Segmentation and Reassembly
* ####  Service Point Addressing
</p>
<br/>

---
##  Network Layer 
<p>
The Network layer deals with the transmission of data from one host to the other host located elsewhere.
It also finds the shortest path for packet routing, for a faster approach to the user.

There are two functions of the Network layer:

* ####  Routing
* ####  Logical Addressing
</p>
<br>

---
##  Data Link Layer (DLL)
<p>It deals with message delivery between nodes. It ensures that the transmission is error-free.

DLL is divided into two sub-layers:
* ####  Logical Link Control (LLC)
* ####  Media Access Control (MAC)

There are five functions of DLL:
* ####  Framing
* ####  Physical addressing
* ####  Error control
* ####  Flow Control
* ####  Access control
</p>
<br/>

---
##  Physical Layer
<p>It is the 1st layer of the OSI-model. It deals with the physical connection between the devices. In the physical layer, information is stored in the form of bits.

There are four functions of the Physical layer:
* ####  Bit synchronization
* ####  Bit rate control
* ####  Physical topologies
* ####  Transmission mode
</p>
<br/>

---
##  References
* #### [YouTube - TechTerms](https://www.youtube.com/watch?v=vv4y_uOneC0)

* #### [OSI Reference Model v1.31 – Aaron Balchunas ](https://www.routeralley.com/guides/osi.pdf)

* #### [GeeksForGeeks](https://www.geeksforgeeks.org/layers-of-osi-model/)

* #### [Tutorials Point](https://www.tutorialspoint.com/The-OSI-Reference-Model)

<br/>

---

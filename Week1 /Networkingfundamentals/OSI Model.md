#Week 1 - DAy 1 -OSI MODEL
Hi Cyberlearners ! 🚀  
Today we’re diving into one of the most important foundational concepts: **The OSI Model**. Whether you're just starting out or brushing up, this guide is for YOU :)

**WHY OSI MODEL**
Stands for Open system Interconnect Model
Back in a day, two devices made by two different companies cannot talk to each other (cannot connect).
for example -Imagine you have a printer from one manufacturer and a computer from another, and they need to exchange data — how would they talk?
Here comes - **OSI MODEL**

**WHAT WAS PROBLEM BEFORE**
Before the OSI Model, devices had their own unique protocols (languages), and because there was no universal standard, companies had to design everything in their own proprietary ways. 
This led to incompatibility and a huge mess in the world of networking.
 for example- Have you ever tried to charge your Iphone with android cable? it doesnot work ? it's not compatiable?
 Early year, netwrorks were same like this.
 
**SOLUTION**
Networking Models
 |       |
OSI     TCP/IP
 |       |
7Layers  5Layers
 
OSI                                    TCP/IP
 |                                      |
Application Layer                    Application Layer
Presentation Layer                   Transport Layer
Session Layer                        Network Layer
Transport Layer                      Data Link layer
Network Layer                        Physical Layer
Data Link layer
Physical Layer

Each layer defines protocol or standards  we use when computers connect.
Think of it like a **layered cake** 🍰 — each layer adds something to help deliver your message.

##  The 7 Layers (Top to Bottom)

| Layer | Name           | Function (Simple)                                   | Mnemonic Word           |
|-------|----------------|-----------------------------------------------------|-------------------------|
| 7     | Application    | User interface: HTTP, FTP, SMTP                     | All                     |
| 6     | Presentation   | Translates, encrypts, and compresses data           | People                  |
| 5     | Session        | Manages sessions/connections                        | Seem                    |
| 4     | Transport      | Ensures reliable delivery (TCP/UDP)                 | To                      |
| 3     | Network        | IP addressing & routing (IP, routers)               | Need                    |
| 2     | Data Link      | MAC addressing, switching, error detection          | Data                    |
| 1     | Physical       | Hardware: cables, signals, network cards            | Processing              |


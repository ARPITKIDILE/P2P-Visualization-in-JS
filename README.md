# P2P FILE TRANSFER
## A Visualization of Peer to Peer(P2P) file transfer.

*************************************
### *Description*: 

*Implementation of a BitTorrent-like file transfer application. The application will run on top of
UDP, and you will need to implement a reliability and congestion control protocol (similar to TCP) for the application.
The application will be able to simultaneously download different parts, called “chunks”, of a file from different
servers.*

```
In Computer Networking, P2P is a file sharing technology, allowing the users to access mainly the multimedia files like videos, music, e-books, games etc. The individual users in this network are referred to as peers. The peers request for the files from other peers by establishing TCP or UDP connections.

A project to demonstrate Computer Networks(CN) concepts.
```
*****************************************
### *Technology stack*:

JavaScript(JS),HTML,CSS
*****************************************

### *Working*: 
```
1. Now whenever a requesting peer comes in, it sends its query to the server.
2. Since the server has all the information of its peers, so it returns the IP addresses of all the peers having the requested file to the peer.
3. Now the file transfer takes place between these two peers.
4. The major problem with such an architecture is that there is a single point of failure. If the server crashes, the whole P2P network crashes.
5. Also, since all of the processing is to be done by a single server so a huge amount of database has to be maintained and regularly updated.
```
**************************************

### *Running the code*:

```
a. Download the repository.
b. The code can be run in any browser(preferably Chrome)

Also you can run the .exe file for demo.

1.Initially the network consists of four clients and one server.

2.Considering file is divided in four parts(Blue,green,red,yellow)

3.Initially clicking on step1 green and yellow packets are transferred to two clients.

4.On clicking step2 the two clients who have green and yellow packets share the packets with other two clients.

5.In this way all clients have two parts of the file green packet and yellow packet.

6.On clicking on step3 red and blue packets are transferred to two clients.

7.On clicking step4 the two clients who have red and blue packets share the packets with other two clients.

8.In this manner each client gets complete file in the form of four packets.
```
***************************************

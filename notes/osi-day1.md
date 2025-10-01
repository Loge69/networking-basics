Open System interconnection was introduced to make
the communication standardize between different vendors
in the old times.they are basically rules or protocols.
Concepts:
1. each layer is a set  of protocols or rules.
2. when sending data it moves from application ,presentation ,session, transport , network ,data link, physical laer and when recieving the protocol check is in vice versa direction.
3. MAC addresses are twelve alphanumeric no.
>APPLICATION LAYER:
 These rules and protocols that govern how software applications interact with network services.

>PRESENTATION LAYER:
 takes the data from application layer translate it into machine language, compress it, encryption decryption.

>SESSION LAYER:
 these are the rules that manages authentication, authorization, it tracks data packets and there types meaning session management.

> TRANSPORT LAYER:
 these protocols controls reliability of communication 
 segmentation(the data recieved from upper layer is divided into data units called segments each segment has source and destination port no.(to the correct application) and sequence no.(order of the data units)),
 flow control(amount or speed of data being transmitted),
 error control(if segment failed to recieve it automatically request only that segment),
 connection(TCP there is a feedback slower then UDP) and
 connectionless(UDP there is no feedback faster than ) Tx.

>NETWORK LAYER:
 these protocols works for the transmission of recieved data segments from one computer to another located in different networks
 logical addressing is done in network layer.
 Logical Addressing(ip addressing network layer assigns senders and recievers ip address to a segment to form an ip packet used to make the data reach the right destination )
 Routing(data packets from source to destination on the logical addressing format of ipv4 or ipv6)
 Path determination(finding the best path for data to transfer from sender to reciever protocols suchs as OSPF BGP IS-IS)

>DATA LINK:
 these protocols works for the physical addressing (MAC addresing to form a frame(the data unit in data link layer is called frame) 
 MAC is assignment by vendors to a NIC card to transfer data through local media(cables, fibre-optics etc) here media is not the data being transferred but the physical links between the  NIC CARD or networks)
 uses FRAMING(Controls how data is placed and recieved from the media, every stop will decapsulate the packet encapsulate 
               it again and to the further stop the further stop does the same until it reaches the final destination )
      Media access control( if two or more devices sends data at the same time it can corrupt the data thats why it keeps an eye on the media to be free also known as CSMA carrier sense messsage multiple access)
      error detection(Tail of each frame contains bits that are used to detect errors in the recieved frame)

>PHYSICAL LINK:
          Till now data has been segmented by transport layer.
          Turned into packets by network layer.
          Frtamed by Data link layer.
          which is a sequnce of 0's and 1's.
 physical layer converts these sequences into signals (radia or electrical depending on the type of media) amd vice versa converts signals into sequences. 



# Bridges in CN:
- used to connect **2 LAN**, suppose in one side of bridge is connected with Ring and other may be connected with Bus 
- it worked in Physical and Datalink layer(so it can read MAC addrss so can work forwarding at a particular node)
![image](https://user-images.githubusercontent.com/77873383/173211234-7e622ee2-c1e7-4f45-a741-2b1cca12620c.png)

``` Suppose M1 wants to send to M6 so it will be send by a packet containing
Source Mac and destination MAC
```
![image](https://user-images.githubusercontent.com/77873383/173211267-f13ba009-8606-4e99-8b18-b712e5ca0f30.png)

- MAC adress be checked by Bridges then forwarding occurs
This Checks done by - **Static** and **Dynamic**

![image](https://user-images.githubusercontent.com/77873383/173211314-bb87ccaa-373c-4533-ab59-977e190faa3e.png)

### Static:
done using a table(MAC,PORT)

![image](https://user-images.githubusercontent.com/77873383/173211371-3a7d3dda-7c95-4357-94b3-344f9d5c8629.png)

By checking MAC if in same port -> **Not forwarding** else forwad to next port to the destination.



## Dynamic
- start with empty table

# DO LATER😥😥

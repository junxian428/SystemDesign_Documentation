# SystemDesign_Documentation


Divide and conquer methodology

-> Break the system into 3 parts, Frontend, Backend, Frontend(Hardware)

Frontend (VueJS)

Backend (Java Spring + MySQL)

Frontend (Hardware) - Raspberry Pi & PLC

______________________________________________________________________________________________________________________________________________

Version 1 ( 17/7/2023)

![Untitled Diagram drawio (6)](https://github.com/junxian428/SystemDesign_Documentation/assets/58724748/b4f38a67-76d3-4226-aed5-9a917f06d2ac)

Note:

Item API is depending on Dashoard API (due to user_id) 

-> If the dashboard API is not started, then Item API will crushed also...


VUEJS Frontend

Login.vue

![image](https://github.com/junxian428/SystemDesign_Documentation/assets/58724748/cbaa5e0c-347d-462a-aff1-63c140caffb0)

Home.vue

![image](https://github.com/junxian428/SystemDesign_Documentation/assets/58724748/d6f7875b-4416-4385-b9f5-ac965638c4a5)

Item.vue

![image](https://github.com/junxian428/SystemDesign_Documentation/assets/58724748/cad54b3a-0c63-47c0-b9b3-2a580e5dae00)

Monitor.vue

![image](https://github.com/junxian428/SystemDesign_Documentation/assets/58724748/85565948-8eaa-4ab5-baba-0126b112952f)


___________________________________________________________________________________________________________________________

(Plans System Design Phrase 2)


![Untitled Diagram drawio (7)](https://github.com/junxian428/SystemDesign_Documentation/assets/58724748/c84bd55e-0556-4301-a492-2012ac476395)


Kafka

My simple example :

https://github.com/junxian428/Spring_WebSocket_Kafka_Producer_to_NodeJS_Consumer

Since 

We can post request to the backend server, then we need encryption to prevent the device only send to device

I guess we can send base on "permanent token"

Then permanent token have the link with user_id


_____________________________________________________________________________________________________________________________________





Version 2




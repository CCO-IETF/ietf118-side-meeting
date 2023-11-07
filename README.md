# CCO (Collective Communication Optimizations) Side Meeting in IETF 118

**Time: 14:30-16:00 Thursday (Nov 9, 2023), Prague (CET)**, 16:00-16:30 as buffer time 
  - UTC 13:30 - 15:00
  - CET (UTC+1) 14:30 - 16:00
  - CST (UTC+8) 21:30 - 23:00
  - PST (UTC-8) 05:30 - 07:00
  - EST (UTC-5) 08:30 - 10:00

**Location: Palmovka 1/2**

**Remote Access Link:  https://ietf.webex.com/meet/ietfsidemeeting2**

Information also available on side meeting wiki: https://wiki.ietf.org/meeting/118/sidemeetings#meeting-thursday

Organizers: Kehan Yao (yaokehan@chinamobile.com), Yizhou Li (liyizhou@huawei.com) 

## Agenda
1.	Admin 
2.	Use cases, problem space and requirements: kehan Yao (China Mobile) 
3.	Challenges in hardware offloading of collective operations: Alex Margolin (Hebrew University of Jerusalem)
4.	Signaling In-Network Computing operations (SINC): David Lou (Huawei) 
5.	In Network Compute: Surendra Anubolu (Broadcom) 
6.	Open Discussions

## Introduction
Collective communication plays a key role in high performance computing and the modern distributed AI training workloads such as recommender systems and natural language processing.
It involves a group or groups of processes participating in collective operations like AllReduce or AllGather. The communication model can be one-to-all, all-to-one or all-to-all and is usually realized by a sequence of unicast messages. Communication and computation is coordinated among a group of processes. 

In-network computing, in recent years, has been being discussed to improve the overall performance in terms of the bandwidth consumed and/or latency when collective communications are used. Designing the network assissted collective communication primitives to execute one or some key steps in the process and/or to provide the more efficient group communication model are drawing some special attentions as the ways for collective communication optimizations (CCO). They also impose some challenges and requirements for both the network transport and forwarding, and co-design of protocols and distributed learning frameworks.

Therefore, we are organizing a side meeting CCO in IETF 118. The primary goals are to introduce and discuss the challenges, requirements and new technologies to optimize collective communication with in-network computing in use, and to explore the standardization opportunities in IETF. Your participation is welcome. We hope to foster the open discussions to stimulate the innovative engineering work in this area. No immediate conclusion is expected to be made at the end of the side meeting. 


# CCO (Collective Communication Optimizations) Side Meeting in IETF 118

## Time: 14:30-16:00 Thursday (Nov 09 2023) , after the 1st afternoon session 
  - UTC 13:30 - 15:00
  - CET (UTC+1) 14:30 - 16:00
  - CST (UTC+8) 21:30 - 23:00
  - PST (UTC-8) 05:30 - 07:00
  - EST (UTC-5) 08:30 - 10:00

Information also available on side meeting wiki: https://wiki.ietf.org/meeting/118/sidemeetings#meeting-thursday

## Location: Palmovka 1/2
## Remote Access:  https://ietf.webex.com/meet/ietfsidemeeting2 

## Agenda
1.	Admin [8: 8/90] 
2.	Problem statement, use cases and requirements: kehan Yao (China Mobile) [20: 28/90] 
     - slides:
     - drafts:
       - [draft-yao-tsvwg-cco-problem-statement-and-usecases](https://datatracker.ietf.org/doc/draft-yao-tsvwg-cco-problem-statement-and-usecases/)
       - [draft-yao-tsvwg-cco-requirement-and-analysis](https://datatracker.ietf.org/doc/draft-yao-tsvwg-cco-requirement-and-analysis/)
3.	TBD [20 : 48/90]
     - slides: TBD
4.	Signaling In-Network Computing operations (SINC): David Lou (Huawei Technologies) [20: 68/90]
     - slides:
     - drafts:
       - [draft-lou-rtgwg-sinc](https://datatracker.ietf.org/doc/draft-lou-rtgwg-sinc/)
       - [draft-lou-rtgwg-sinc-deployment-considerations](https://datatracker.ietf.org/doc/draft-lou-rtgwg-sinc-deployment-considerations/)
5.	TBD [17: 85/90]
     - slides: TBD
6.	Wrap up [5 : 90/90]


## Introduction
Collective communication plays a key role in high performance computing and the modern distributed AI training workloads such as recommender systems and natural language processing.
It involves a group or groups of processes participating in collective operations like AllReduce or AllGather. The communication model can be one-to-all, all-to-one or all-to-all and is usually realized by a sequence of unicast messages. Communication and computation is coordinated among a group of processes. 

In-network computing, in recent years, has been being discussed to improve the overall performance in terms of the bandwidth consumed and/or latency when collective communications are used. Designing the network assissted collective communication primitives to execute one or some key steps in the process and/or to provide the more efficient group communication model are drawing some special attentions as the ways for collective communication optimizations (CCO). They also impose some challenges and requirements for both the network transport and forwarding, and co-design of protocols and distributed learning frameworks.

Therefore, we are organizing a side meeting CCO in IETF 118. The primary goals are to introduce and discuss the challenges, requirements and new technologies to optimize collective communication with in-network computing in use, and to explore the standardization opportunities in IETF. Your participation is welcome. We hope to foster the open discussions to stimulate the innovative engineering work in this area. No immediate conclusion is expected to be made at the end of the side meeting. 


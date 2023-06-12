# Solution to labs of the MIT 6.824 distributed system 


- Implement Raft, an distributed consensus algorithm designed as an alternative to the Paxos family of algorithms.
- Based on the framework and test cases provided by the course, I designed and developed the core logic detailed in the Raft paper with techniques of channel, multi-thread and wait-group in the golang.
- The biggest challenge in this kind of consensus algorithm is that every thread, as a participant in this consensus group, will assume both roles and update their state and internal datas according to the signals from others and time.

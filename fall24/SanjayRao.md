## Title:  Principled data-driven ML-based approaches for Networked Systems 
 
**Speaker:**  Sanjay Rao, Purdue University
 
### Abstract:

Data-driven and ML-based approaches offer exciting potential for diverse networking problems ranging from traffic engineering to Internet video delivery.  Harnessing the potential requires dealing with the dynamic nature of network environments (e.g., topology evolution, traffic shifts), and handling new scenarios not seen in training data (e.g., unseen failures). Further, while it is common to drive design based on offline data collected from operationally deployed systems, the adaptive nature (e.g., adjust bit rates, reroute traffic, switch CDNs) of networked systems introduces biases that must be accounted for. 

In this talk, I will argue that tackling these challenges requires going beyond “off-the-shelf” ML,
and adopting a cross-disciplinary approach that bridges networking and ML. I will present two recent works to illustrate. First, I will present Harp, a neural model for traffic engineering in Wide Area Networks which is capable of handling variations in topology including those not observed in training. Harp is explicitly designed to be robust to certain input transformations, and aligned to network optimization algorithms. Second, I will present Veritas, a system for answering what-if questions (e.g., predict performance if a new design were used) in the context of adaptive bit rate (ABR) video streaming. A key challenge that Veritas tackles is answering such what-if questions without access to randomized control trials (RCTs) using a causal reasoning framework.

 
### Bio:

Sanjay G. Rao is a Professor in the School of Electrical and Computer Engineering at Purdue University, where he leads the Internet Systems Laboratory. His research spans network synthesis/design/verification, and Internet video distribution. He received a B.Tech in Computer Science and Engineering from the Indian Institute of Technology, Madras, and the Ph.D from the School of Computer Science, Carnegie Mellon University. He has been a Visiting Researcher at Google, AT&T Research and Princeton University. He is a recipient of the NSF Career award, has won the ACM SIGMETRICS Test of Time Award for his work on End System Multicast (peer-to-peer video streaming), and is an ACM Distinguished Member. He has served on the Technical Program Committees of conferences including ACM Sigcomm, Usenix NSDI, and ACM Sigmetrics, has served as the Area technical program chair of IEEE Infocom, and has been an Associate Editor for the IEEE/ACM Transactions on Networking.

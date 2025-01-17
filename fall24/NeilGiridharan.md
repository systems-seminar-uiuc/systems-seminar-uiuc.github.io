## Autobahn: Seamless high speed BFT

**Abstract:** 

Today’s practical, high performance Byzantine Fault Tolerant (BFT) consensus protocols operate in the partial synchrony model. 
However, existing protocols are inefficient when deployments are indeed partially synchronous. 
They deliver either low latency during fault-free, synchronous periods (good intervals) or robust recovery from events that interrupt progress (blips). 
At one end, traditional, view-based BFT protocols optimize for latency during good intervals, 
but, when blips occur, can suffer from performance degradation (hangovers) that can last beyond the return of a good interval. 
At the other end, modern DAG-based BFT protocols recover more gracefully from blips, but exhibit lackluster latency during good intervals. 
To close the gap, this work presents Autobahn, a novel high-throughput BFT protocol that offers both low latency and seamless recovery from blips. 
By combining a highly parallel asynchronous data dissemination layer with a low-latency, partially synchronous consensus mechanism, 
Autobahn (1) avoids the hangovers incurred by traditional BFT protocols 
and (2) matches the throughput of state of the art DAG-based BFT protocols 
while cutting their latency in half, matching the latency of traditional BFT protocols.
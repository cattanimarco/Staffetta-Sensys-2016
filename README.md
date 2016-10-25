Staffetta code from paper "STAFFETTA: SMART DUTY-CYCLING FOR OPPORTUNISTIC DATA COLLECTION" published as Sensys 2016

More info: 
http://cattanimarco.com/2016/07/19/staffetta/

Abstract:
Recent opportunistic routing protocols address the problem of efficient data collection in dynamic wireless sensor networks, where the radio is duty cycled to save energy and the topology changes due to link dynamics and node mobility.
Unlike traditional approaches that maintain a routing structure (e.g., a tree), opportunistic schemes forward packets to the first neighbor that wakes up, thereby reducing latency and energy consumption and increasing the robustness to network dynamics.
Notwithstanding the many advantages, this paper argues that existing opportunistic protocols do not fully exploit the synergy between duty cycling and routing in that all nodes wake up with the same fixed frequency. 
Instead, we present Staffetta, a duty-cycle scheduling mechanism that dynamically adjusts each node’s wake-up frequency in a distributed fashion, such that nodes closer to the sink are more active than nodes at the edge of the network. The resulting activity gradient effectively biases the forwarding choices of opportunistic mechanisms towards the sink, as the time to find an awake neighbor is shorter in the direction of the sink. We implement Staffetta in Contiki, and evaluate it in combination with three different opportunistic routing mechanisms on two testbeds. 
Our results show that, across the board, Staffetta reduces packet latency by an order of magnitude while halving the energy consumption at minimal overhead. In some cases the impact is even more profound. Compared to using ORW alone, adding Staffetta can lead to network lifetimes that are six times longer and end-to-end packet deliveries that are 450 times faster. In other words, by smart duty cycling, Staffetta improves opportunistic data collection basically for free.

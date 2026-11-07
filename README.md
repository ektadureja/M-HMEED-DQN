**Overview**
This repository presents Dynamic Reinforced Mobility-Located Clustering (DRMLC), a Python-based framework integrating Modified HEED (M-HEED) clustering, Deep Q-Network (DQN) reinforcement learning, mobility-aware cluster-head selection, and hierarchical routing to improve energy efficiency and network lifetime in Mobile Wireless Sensor Networks (MWSNs).

**Implementations**
Ratio Mode: Implements non-recursive, energy-aware clustering and cluster-head-based routing.
Recursive Mode: Incorporates hierarchical clustering and super-cluster-head-based multi-level data forwarding.

Both implementations support adaptive clustering and evaluate network lifetime, Packet Delivery Ratio (PDR), residual energy, and routing performance.

**Research Contributions**
The proposed DRMLC methodology combines mobility-aware clustering with DQN-based adaptive decision-making. The research also introduces overhead-inclusive energy accounting for centralized learning and control signalling.

The associated paper reports 1,944 rounds of network lifetime, 0.9987 PDR, and approximately 6.2% control-signalling energy overhead in Recursive Mode. These are reported research results rather than independently reproduced notebook outputs.

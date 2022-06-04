
# Spectrum Based Trafﬁc Classiﬁcation in Wireless Network using Deep Hybrid Neural Network
+ The repository contains code for trafﬁc classiﬁcation at layer 7 in wireless network radio stack using deep hybrid cneural network incorporating a deep convolutional network with a recurrent network. 
+ Paper: "Spectrum Based Trafﬁc Classiﬁcation in Wireless Network using Deep Hybrid Neural Network"



## Abstract
In recent years, trafﬁc classiﬁcation (TC) represents
an important issue in managing and optimizing the wireless network
capacity. With the growth of numerous wireless technologies,
it has become more challenging to develop an efﬁcient TC
system. Deep learning (DL) based architecture provides feasible
solution in today’s complex and modern scenarios where even
trafﬁc is encrypted. Traditional TC using DL based architecture
exploits the byte/protocol representation of the packet at the link
layer (L2) or above on the same radio network domain. It limits
the efﬁcacy of the TC systems in wireless networks using shared
spectrum. Therefore, designing TC based on spectrum band
generated physical layer (L1) packet using DL based architecture
has received signiﬁcant research attention more recently. In this
article, we propose a deep hybrid neural network that incorporates
a deep convolutional network with a recurrent network to
classify trafﬁc at layer 7 (L7) (e.g., application characterization
and application identiﬁcation) of the radio network stack using
L1 packets. The proposed network can capture spatio-temporal
feature correlation and use multiscale feature map to avoid
vanishing gradient problem. From the simulation, it is seen
that the proposed classiﬁer can achieve 98.25% accuracy and
86.28% accuracy for the task of application characterization and
application detection, respectively. Simulation results unveil that
our proposed network is very promising for classifying trafﬁc at
L7 using the L1 packet.
## Dataset
[IDLAB-UA Dataset for Traffic Classification using Spectrum Data](https://zenodo.org/record/5208201#.YpsMUHZByUk): This dataset contains IQ values of physical layer (L1) packets associated with WLAN transmission and the set of labels that associated each of the packets to properties/features at different radio stack layer (from L1 to L7) and published by [link](https://ieeexplore.ieee.org/document/9626148). 
## How to cite
## References
To preprocess the data, some codes are taken from [Traffic Classification directly on spectrum data](https://github.com/miguelhdo/tc_spectrum).
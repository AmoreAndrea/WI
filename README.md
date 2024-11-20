GOAL: implement a machine-learning classiﬁer able
to dis6nguish what kind of ac6vity a user is performing with his/her
smartphone/laptop by sniﬃng traﬃc in monitor mode. The system should perform
the following operations:
a. Sniﬀ traﬃc in monitor mode from a known MAC address
b. extract statistical features from the traﬃc every W seconds. The following
traﬃc features can be extracted: number of packets up/down, average and
variance of the packet size, average and variance of the inter-arrival packet
times etc.
c. use a pre-trained machine-learning classiﬁer of your choice to recognize the
user activity among at least the following: idle, web browsing, YouTube
streaming.

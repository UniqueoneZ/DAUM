# DAUM
This is the official code repository for the paper “Distillation-Accelerated Uncertainty Modeling for Multi-Objective RTA Interception.”

DAUM is a model that integrates multi-objective learning and uncertainty modeling for joint optimization. It is primarily designed for pre-filtering requests in Real-Time Auction (RTA) interception. By leveraging both the predicted scores and their corresponding confidence levels in real time, DAUM filters out traffic with low predicted scores and high model confidence, thereby improving data quality in real-time environments. The overall architecture of DAUM is illustrated in the figure below:

![](image/overall_structure.jpg)

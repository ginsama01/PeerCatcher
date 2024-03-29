# A More Efficient System for Peer-to-Peer Botnet Detection

This is the experimental source code for paper "A More Efficient System for Peer-to-Peer Botnet Detection", which is presented at ICIIT 2023 and is published at the ACM Proceedings.
## Getting Started

These instructions will give you a copy of the project up and running on
your local machine for development and testing purposes. See deployment
for notes on deploying the project on a live system.

### Prerequisites

Requirements for the software and other tools to build, test and push
- [JDK 1.8](https://www.oracle.com/java/technologies/javase/javase8-archive-downloads.html)
- [IntelliJ Idea (Optional)](https://www.jetbrains.com/idea/download/#section=linux)


## Dataset

Dataset for experiment is available on [KAGGLE](https://www.kaggle.com/datasets/crys2508/p2p-botnet-detection-dataset)

### Sample flows input

    14.15.3.143	udp,180.137.2.57,127,143
    14.15.3.143	udp,95.21.15.56,127,108
    14.15.3.143	tcp,70.31.12.35,87,91
    14.15.3.143	tcp,188.153.6.62,90,79
    14.15.3.143	udp,109.186.3.157,177,93
    14.15.3.143	udp,222.83.8.62,86,85


## Deployment

Recommend using IntelliJ Idea to deploy

- Reload project in *pom.xml* to import library through maven
- Download the data and set the correct path in file *PeerCatcherConfig*
        
      public static String ROOT_LOCATION = "data/";

- Set value for system parameters and run


## Authors

- **Nguyen Quang Huy** - *University of Engineering and Technology - VNU*
- **Dang Trung Kien** - *University of Engineering and Technology - VNU*
- **Nguyen Dai Tho** - *University of Engineering and Technology - VNU*

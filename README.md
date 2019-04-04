# Datagraviti: 
## A Data Marketplace based on Hyperledger Fabric
This repository contains the root repository of the data marketplace initiative.

Datagraviti is a decentralized data marketplace based on Hyperledger Fabric, a blockchain framework implementation hosted by The Linux Foundation. The purpose of the developed data marketplace is to ensure data exchange in a decentralized setting between data providers and consumers organized into a consortium. The data marketplace is permissioned, enterprise grade, decentralized data exchange platform for data professionals and industry consortiums who value control and privacy.  

The platform takes the most of Hyperledger Fabric by implementing a chaincode (smart contract) that enforce data ownership and protect privacy in data exchange. It uses an overlay of decentralized severs built on top of Hyperledger Fabric to ensure data cataloging, data storage and data stream delivery. The platform is also provided with a portal to be used by end users to browse, search, buy, sell and consume data (in different forms). 

The platform should be operated by a consortium of data players who are willing to exchange and monetize data including not only selling and buying but also processing data.

## Architecture overview
<img src="images/architecture.png" width="1000">

## Datagraviti detailed services

### Environment Setup

We used Hyperldger Fabric as an underlying blockchain infrastructure to support the data marketplace.
In this use case, we were inspired by the open source community deployment tutorials to deploy Fabric on top of Kubernetes.
Specifically, we followed [this tutorial](https://github.com/IBM/blockchain-network-on-kubernetes#4-deploy-hyperledger-fabric-network-into-kubernetes-cluster).
The new deployment artifacts and scripts that we created are in this repository:
[data-marketplace-hyperledger-fabric](https://github.com/lgsvl/data-marketplace-hyperledger-fabric).

### Hyperledger Chaincode
...add description and link to chaincode repo
- [Data marketplace chaincode](https://github.com/lgsvl/data-marketplace-chaincode)

### Chaincode REST interface
... add description and link to chaincode rest
- [Data marketplace chaincode REST](https://github.com/lgsvl/data-marketplace-chaincode-rest)

### File-based data delivery service
... add description and link to repo
- [Data marketplace file delivery](https://github.com/lgsvl/data-marketplace-file-delivery)

### Stream-based data delivery service
... add description and link to repo
- [Data marketplace stream delivery](https://github.com/lgsvl/data-marketplace-stream-delivery)

### Data marketplace Facade service
... add description and link to repo
- [Data marketplace facade](https://github.com/lgsvl/data-marketplace-facade)

### Data marketplace ElasticSearch Feeder
... add description and link to repo
- [Data marketplace ElasticSearch Feeder](https://github.com/lgsvl/data-marketplace-esearchFeeder)

### Web Portal
... add description and link to repo
- [Data marketplace portal](https://github.com/lgsvl/data-marketplace-portal)

### CI/DC pipeline
... add description and link to repo
- [Data marketplace CI/CD pipeline](https://github.com/lgsvl/data-marketplace-pipeline)

### Contribution
To contribute, follow the guidelines in [Contribution guide](contribution-guide.md)

### Support
For any questions, suggestions, or issues, use Github.

### List of Contributors
[Samir Tata](https://www.linkedin.com/in/samirtata/), LG Electronics \
[Mohamed Mohamed](https://www.linkedin.com/in/mohamedmohamedphd/), LG Electronics \
[Gina Kang](https://www.linkedin.com/in/gina-baek-9161bb30/), LG Electronics \
[Faisal Mohammad](https://www.linkedin.com/in/faisalmohammad27/), LG Electronics \
[James Hazen](https://www.linkedin.com/in/jim-hazen-204a741/), LG Electronics \
[Jacob Song](https://www.linkedin.com/in/jacob-song-1bb2301/), LG Electronics \
[Angela Lau](https://www.linkedin.com/in/angelal/), LG Electronics \
[Jae Young Jung](https://www.linkedin.com/in/designerjae/), LG Electronics \
[Lily Hu](https://www.linkedin.com/in/lilyhusf/), LG Electronics 

### License
Copyright 2018, 2019 LG Electronics.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

![MedBlocks Logo](https://i.imgur.com/Dx4LfC2.png)

# Implementation of sidharthramesh's MedBlocks
For a school iSTEM project, I wanted to learn about BlockChain. One of the impediments to such a task is the lack of documentation online. In this project I have replaced certain dependencies on BigChain with alternatives (MongoDB), and written new schemas so the service completely interfaces with a different database. Despite the database not being entirely centralized, it shares the essential concept of 'transactions' on the chain, with references to non-centralized data sources (the IPFS).

## Installation

1. Install Docker and docker-compose
2. Clone the repository
3. Build docker image
```
docker-compose build .
```
4. Run image
```
docker-compose run server
```
5. Test version
```
# python medblocks.py --version
```


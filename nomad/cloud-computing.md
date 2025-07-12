# Cloud Computing 

> "The cloud is not just someone else's computer"

## Overview

**Reasons**
- Powerful/enterprise grade hardware: Consumers do not have acess to pentabyes, Xenon cpu with hundrens of cores.

- Enterpise grade software: Advanced filesystem such as zfs scale well with more compute resources, Server farms can benefits from ecnomomies of scale, especially well, e.g pooling computing and other resouces such as storage. ZFS enables this well.

- Reccuring costs: electicity, component wear, etc are all variable costs, and workers to maintain the farms. Cloud computing is a service not just infastrucutre.

Uptime: Serviers are always one, RAID, servers across the world sophisticaed managmnet systems is far more robust than copiing files to a hdd in the same location.


## Modern Approach

## Cloud


## Local 

**Compunter Role**
- A compunter is not a storage device, it is mean to maniputate data, not store it.
- A compunter should only hold the data it is going to work on, preform the maniputate and then push it to a cloud storage server.
- The cloud has special properies, universal, stateless etc, Local compunters should focus on doing work for the cloud.

### Examples 

**Desktop Compunter**
- Most local compute realsically 
- Optimized for stabilty and user egonomcis
- Still should behave as an emphemal client, it has not speical properies which elevevate it from a table. It is still sustepalca to failure, breakage, data loss etc. Also some preventative mesures to exist such as RAID levels and btrfs snapshots, They are a defense against the incoveince of buying new hardwasing and running a few reinstall scripts, not a guard against data loss.

**Laptop**
- Generally inferior to a desktop computer in all aspects except portabiltiy. Once again should be used as a thin client to do work, and push to cloud. Laptopss can work well with desktop since they are less resticive than smaller form facors (tablets, wearables, smartphones) ssh rlcone, network shares, `~/public/syncthing`  

**Smartphone**
- Worst user egnomcis, using microphone for dictation seems more ideomatic compared to typeing. Seems only useful as a netowring/commuication/media client device compared to a tool to do real work. A wearable might make more sense since it can do payments, dication, bluetooth.

**Exernal drives**
1. Holding media,
2. btrfs parition `bttrfs send || btrfs recive`. Acts as a second backup with is air gapped

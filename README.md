# OneKube
Zero trust peer-to-peer global scale computing for long lasting processes and functions.

## Idea
OneKube comes as a single binary for datacenters and IoT as well. Service Mesh is not just a pile up complexity but natively incorporated as P2P network. Clustering is a workload concern, as such the nodes do not need consensus or leader election, thus being able to massive scale-out.

Decoupling the the P2P network from the clustering,  coordination from the clustering offers a major advantage in scaling and continuous lifecycle. Networking is fully replaced by transport based connectivity.

Just deploy to join the P2P network to participate. The underlying protocol naturally prefers nodes that are been alive for longer over newer entrants. As soon workload is deployed, consensus is deployed as sidecar to the pods. Stateless workload doesn't need any state management. This encourages stateless and zero trust based microservices.

## Architecture

![OneKube Binary](OneKube.png)

## Service Mesh


## API
Must be K8s compliant so that everybody can move on.

## Building Blocks
* P2P: [https://libp2p.io/](https://libp2p.io/)
* Workload Clustering: [https://github.com/libp2p/go-libp2p-raft](https://github.com/libp2p/go-libp2p-raft)
* Container runtime: [https://containerd.io/](https://containerd.io/)
* Kubernetes: [https://kubernetes.io/](https://kubernetes.io/)
* Lightweight Kubernetes: [https://k3s.io/](https://k3s.io/)
* Example P2P Database: https://github.com/orbitdb

## Prototype
WIP

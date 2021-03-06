# KubeZilla Community Collaborative Project

   ![image](https://github.com/collabnix/kubezilla/blob/master/images/kubezilla.png)

We are aiming to build a largest Kubernetes Community Cluster and target to showcase it on OSCONF Kochi Day.

## Contribution Proposal

  1. Create a pull request if you're interested to contribute your FREE Cloud instance(AWS/Azure/GCP/DO).
  2. You can even contribute Your Raspberry Pi too if you know how to connect it to this cluster.
  3. Please also include your full name, Twitter's handle *and* your company name.
  4. Please note that the node's specification for this run is **XGB of RAM with X vCore**.
  We're sorry that 512MB will be not enough for our testing.
  
  
  ## What's mininum requirements of a node?
  
- Rancher 
- Ubuntu 16.04+
- Debian 9+
- CentOS 7
- Red Hat Enterprise Linux (RHEL) 7
- Fedora 25+
- HypriotOS v1.0.1+
- Container Linux (tested with 1800.6.0)
- 2 GB or more of RAM per machine (any less will leave little room for your apps)
- 2 CPUs or more
- Full network connectivity between all machines in the cluster (public or private network is fine)
- Unique hostname, MAC address, and product_uuid for every node. See here for more details.
- Certain ports are open on your machines. See here for more details.
- Swap disabled. You MUST disable swap in order for the kubelet to work properly.
- TCP	Inbound	10250	open for Kubelet API	
- TCP	Inbound	30000-32767 open for NodePort Services

## Contributors


| Name          | Company       | Number of Nodes<br>Expected to Contribute |
| ------------- |:-------------:|:-----------------------------------------:|
| [@ajeetsraina](https://twitter.com/ajeetsraina) | Collabnix | 10 |
[@anmolnagpal](https://twitter.com/anmol_nagpal) | CloudDrove Inc. | 15 |
[@cube8021](https://twitter.com/cube8021) | Rancher Labs | 5 |
| [Your Name](https://twitter.com/yourid) | Your Company Name| 8 |


## Beginner's Guide
If you're an individual and it's your first time joining KubeZilla, we encourage you to *not* contribute more than 50 nodes.




## Goals
- This is the 1st collaborative project powered by Collabnix Slack community to form 100+ nodes
- This is being planned on the latest Kubernetes version
-  Networking; We will be creating a large subnet /20 and trying to assign, as many as possible, IP addresses to each container on each node distributedly. We expect to have around ~1k IP addresses assigned and the workload application should be working fine.
- Once 100+ K8s cluster is setup, we will be running an application to see the performance
- We will be using Prometheus as well as Grafana for visualisation

## Results
All experimental results will be provided publicly for all of you to analyze, write blogs,
or even used as information for further development of your own commercial projects. Please feel free to use it.

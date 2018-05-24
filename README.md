
<!---
Copyright IBM Corp. 2018, 2018
--->

# IBM Cloud Private Installer

The IBM Cloud Private Medium Deployment Terraform template and inline modules will provision several virtual machine, install prerequisites and install the IBM Cloud Private product within you vmWare Hypervisor enviroment.

This template will install and configure the IBM Cloud Private in an HA topology.

The components of a IBM Cloud Private deployment include:

- NFS Server (1 Node)
- Management Node (1 Node)
- Master Nodes (1 Node)
- Proxy Nodes (1 Ndode)
- Worker Nodes (3 Nodes)
- Vulnerabilty Node (1 Node)


![IBM Cloud Private HA Topology](./ICP-Architecture.jpg)
<p align="center">Image 1: IBM Cloud Private HA Node Topology></p>


For more infomation on IBM Cloud Private Nodes, please reference the Knowledge Center: <https://www.ibm.com/support/knowledgecenter/en/SSBS6K_2.1.0/getting_started/architecture.html>

## System Requirements

### Hardware requirements

IBM Cloud Private nodes must meet the following requirements:
<https://www.ibm.com/support/knowledgecenter/en/SSBS6K_2.1.0/supported_system_config/hardware_reqs.html>

# Bitbucket Cluster

## Overview
The Bitbucket cluster consists of three nodes configured for high availability.

## Steps
1. Provision 3 VMs using Terraform.
2. Install Bitbucket on each node.
3. Configure HAProxy to distribute traffic among the nodes.
4. Verify synchronization between nodes.
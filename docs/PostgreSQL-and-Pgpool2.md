# PostgreSQL and Pgpool2

## Overview
The PostgreSQL cluster is managed by Pgpool2 for load balancing and connection pooling.

## Steps
1. Provision 2 VMs for PostgreSQL using Terraform.
2. Install PostgreSQL on each VM and configure replication.
3. Install Pgpool2 on a dedicated VM.
4. Test failover and connection pooling.
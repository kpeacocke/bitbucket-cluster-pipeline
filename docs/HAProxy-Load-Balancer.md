# HAProxy Load Balancer

## Overview
HAProxy is used to distribute traffic among Bitbucket nodes.

## Steps
1. Install HAProxy on a dedicated VM.
2. Configure HAProxy to route traffic to Bitbucket nodes.
3. Enable health checks to detect and exclude unhealthy nodes.
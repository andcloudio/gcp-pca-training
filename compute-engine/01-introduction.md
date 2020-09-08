# Compute Engine

## Links

https://cloud.google.com/hosting-options

https://cloud.google.com/compute/vm-instance-pricing

https://cloud.google.com/compute

https://cloud.google.com/compute/docs/sustained-use-discounts

https://cloud.google.com/compute/docs/instances/instance-life-cycle

## startup script for nginx

```bash
apt-get update && apt-get install nginx -y
systemctl enable nginx
systemctl start nginx
```

## shutdown script 

```bash
systemctl stop nginx
```

## Compute Engine

- Deploying VM images

- consists on vCPU, Memory, Persistent Disks, Network

- Sizes - Predefined & Custom

- Predefined - General Purpose, Memory Optimized, CPU Optimized 

- Persistent Disks - Local SSD, PD-Standard, PD-SSD

- Network - default network, auto mode subnet, Private IP address and External IP.

- Firewall - default implicit allow ICMP, SSH, RDP

- Life cycle - Provisioning, Staging, Running, Repairing, Stopping, Terminated

- Connect to instance via ssh


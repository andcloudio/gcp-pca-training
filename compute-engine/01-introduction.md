# Compute Engine

## Links

https://cloud.google.com/hosting-options

https://cloud.google.com/compute/vm-instance-pricing

https://cloud.google.com/compute

https://cloud.google.com/compute/docs/sustained-use-discounts

https://cloud.google.com/compute/docs/instances/instance-life-cycle

## startup script for nginx
apt-get update && apt-get install nginx -y
systemctl enable nginx
systemctl start nginx

## shutdown script 
systemctl stop nginx

## Compute Engine

- Deploying VM images

- consists on vCPU, Memory, Persistent Disks, Network

- Sizes - Predefined & Custom

- Predefined - Shared core, Standard, High mem, High cpu, Mega memory, Ultra memory 

- Persistent Disks - PD-Standard, PD-SSD

- Network - default network, auto mode subnet, Private IP address and External IP.

- Firewall - default implicit allow ICMP, SSH, RDP

- Life cycle - Provisioning, Staging, Running, Stopping, Terminated

- Flexible billing - per second, automatic sustained use discount.

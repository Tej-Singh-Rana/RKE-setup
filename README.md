# RKE-setup
## Rancher Labs (Rancher)

Rancher has two Kubernetes distributions - RKE and K3s. RKE stands for "Rancher Kubernetes Engine" and entirely runs on containers.

K3s is Lightweight Kubernetes. Easy to install, half the memory and all in a binary less than 100 MB.

> Authentication Proxy > Cluster Controller > Cluster Agent > Node Agent > Authorized Cluster Endpoint

## Rancher Kubernetes Engine :-
- Download RKE binary from the RKE GitHub repository's releases.[here](https://github.com/rancher/rke/releases)
- Changed the name of binary to rke.
- Move rke into the /usr/bin/ directory to activate into the terminal.
> Note :- Different-different distribution has different location so move it according to that.
- Make it executable by changing permissions of the file. chmod +x /usr/bin/rke.
- After successfully installed and configured check it into the terminal.
```code

$ rke --version

```
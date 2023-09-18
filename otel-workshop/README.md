# Open Telemetry K8s workshop

## Step 1 - Prerequisites
- Hypervisor installation (VMWare, Hyper-V, Qemu,...)
- Ubuntu20.04 64bit (desktop or server) - 40gb disk, 8GB RAM
- Installation [Docker, Kind, Kubectl](https://github.com/dt-wv/k8s/tree/main/workshop/README.md)
- Access internet

## Step 2 - Easytravel application deployment
`$ sudo su -`  
`curl -LO https://raw.githubusercontent.com/dt-wv/easyTravel/main/k8s.yaml`   
`# kubectl apply -f k8s.yaml`

## Step 3 - Opentelemetry operator and collector installation

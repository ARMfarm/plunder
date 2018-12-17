# Plunder Usage

When using `plunder` there are a few things that you will need to ensure that a configuration exists for, these things are:

- Service configuration (IP Addresses, adapter names, service enablement)
- Deployment configuration (MAC Addresses, Package managment, networking)
- Provisioning configuration (File transfer, remote command execution)

Most of the configuration required will be automatically generated by `plunder` through the use of the `plunder config` sub command. 

### Service
The services such as DHCP and TFTP etc.. are the basic requirement in order to bootstrap a **blank** bare-metal server or new virtual machine. 

Service configuration overview and usage is located [here](./service.md).

### Deployment
Once a **blank** server boots it will need an Operating System (+ packages) installing, along with setting up networking and credentials. 

Deployment configuration overview and usage is located [here](./deployment.md).

### Provisioning
Once a server has been deployed it is on to provisioning that server for a particular use case, such as a docker swarm cluster or a kubernetes platform

A Provisioning overview with usage is located [here](./provisioning.md).
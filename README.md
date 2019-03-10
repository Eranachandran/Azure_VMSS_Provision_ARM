# Azure_VMSS_Provision_ARM
Provisioning a Ubuntu, Centos and Redhat Virtual Machine Scale Sets (Public IP Per Instance=False) using ARM Template

Provisioning a

    "Ubuntu-17.10",
    "Ubuntu-18.04-LTS",
    "RHEL-7.5",
    "RHEL-7.6",
    "Centos-7.3",  
    "Centos-7.5" 
Virtual Machine Scale Sets (Public IP Per Instance=False) using ARM Template

New Virtual Network,Virtual Subnet,Network Security Group will be created.

In this Newly Created VMSS, the instances should taken SSH by using LoadBalancer's Public IP and Port 50001.After login into the VM in Scaleset we can login in to the other virtual machines in scaleset by Particular VM'S Private IP and Port 22

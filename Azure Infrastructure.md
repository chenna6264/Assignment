# Internship Assignment
## overview
     This project includes the deployment of an azure-based web application infrastructure. The setup includes:
     - **Three Virtual Machines (VMs)** running Apache to serve different responses naming as Server1,Server2,Interview
     - **Azure Application Gateway** for load balancing.
     - **Path-based routing** to direct requests to  /server2, and /interview.
     - **Azure Private DNS** (`dvstech.com`) for name resolution of the servers.


## Architecture
The following diagram illustrates the infrastructure:
![Architecture Diagram](infra)
     


## Create Virtual Network (VNet) and Subnets
   * Sign in to the Azure portal
   * Navigate to "Virtual Networks"
   * Click "Create"
   * Configure:
    - Name: Server1-vnet
    - Address space: 10.0.0.0/16
    - Subscription and Resource Group: 
    - Location: Choose a region with 3 availability zones

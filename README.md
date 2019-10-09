# AZ-300 study guide materials 

Skills measured: 
+ [Deploy and configure infrastructure](#deploy-and-configure-infrastructure-25-30)
+ [Implement workloads and security](#implement-workloads-and-security-20-25)
+ [Create and deploy apps](#create-and-deploy-apps-5-10)
+ [Implement authentication and secure data](#implement-authentication-and-secure-data-5-10)
+ [Develop for the cloud and for Azure storage](#develop-for-the-cloud-and-for-azure-storage-20-25)


## Deploy and configure infrastructure (25-30%)

#### Analyze resource utilization and consumption
+ [configure diagnostic settings on resources](https://docs.microsoft.com/en-us/azure/azure-monitor/platform/diagnostic-settings)
+ [create baseline for resources]()
+ [create and rest alerts]()
+ [analyze alerts across subscription]()
+ [analyze metrics across subscription]()
+ [create action groups]()
+ [monitor for unused resources]()
+ [monitor spend]()
+ [report on spend]()
+ [utilize Log Search query functions]()
+ [view alerts in Azure Monitor logs]()

#### Create and configure storage accounts
+ [configure network access to the storage account](https://docs.microsoft.com/en-us/azure/storage/common/storage-network-security)
+ [create and configure storage account](https://docs.microsoft.com/en-us/azure/storage/common/storage-quickstart-create-account?tabs=azure-portal)
+ [generate shared access signature](https://docs.microsoft.com/en-us/azure/storage/common/storage-sas-overview)
+ [install and use Azure Storage Explorer](https://docs.microsoft.com/en-us/azure/vs-azure-tools-storage-manage-with-storage-explorer?tabs=windows)
+ [manage access keys](https://docs.microsoft.com/en-us/azure/storage/common/storage-network-security)
+ [monitor activity log by using Azure Monitor logs](https://docs.microsoft.com/en-us/azure/storage/common/storage-metrics-in-azure-monitor)
+ [implement Azure storage replication](https://docs.microsoft.com/en-us/azure/storage/blobs/storage-create-geo-redundant-storage?tabs=dotnet)

#### Create and configure a Virtual Machine (VM) for Windows and Linux ([Windows](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/quick-create-portal),[Linux](https://docs.microsoft.com/en-us/azure/virtual-machines/linux/quick-create-portal))
+ configure high availability ([Windows](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/tutorial-availability-sets),[Linux](https://docs.microsoft.com/en-us/azure/virtual-machines/linux/tutorial-availability-sets))
+ configure monitoring, networking, storage, and virtual machine size
  + Windows
    + [Monitoring](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/tutorial-monitor)
    + [Networking](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/tutorial-virtual-network)
    + [Storage](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/tutorial-manage-data-disk)
    + [VM size](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/sizes)
  + Linux
    + [Monitoring](https://docs.microsoft.com/en-us/azure/virtual-machines/linux/tutorial-monitor)
    + Networking ([Virtual Network creation for Linux VM](https://docs.microsoft.com/en-us/azure/virtual-machines/linux/tutorial-virtual-network), [Manage Networking](https://docs.microsoft.com/en-us/azure/virtual-network/quick-create-cli?toc=%2Fazure%2Fvirtual-machines%2Flinux%2Ftoc.json))
    + Storage ([Create/Manage Disks](https://docs.microsoft.com/en-us/azure/virtual-machines/linux/tutorial-manage-disks), [Manage Storage](https://docs.microsoft.com/en-us/azure/virtual-machines/linux/attach-disk-portal))
    + [VM size](https://docs.microsoft.com/en-us/azure/virtual-machines/linux/sizes)
+ deploy and configure scale sets ([Windows](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/tutorial-create-vmss), [Linux](https://docs.microsoft.com/en-us/azure/virtual-machines/linux/tutorial-create-vmss))

#### Automate deployment of Virtual Machines (VMs)
+ [modify Azure Resource Manager template]()
+ [configure location of new VMs]()
+ [configure VHD template]()
+ [deploy from template]()
+ [save a deployment as an Azure Resource Manager template]()
+ [deploy Windows and Linux VMs]()

#### Implement solutions that use virtual machines (VM)
+ Provision VMs
  + Windows ([Portal](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/quick-create-portal), [Powershell](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/quick-create-powershell), [CLI](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/quick-create-cli))
  + Linux ([Portal](https://docs.microsoft.com/en-us/azure/virtual-machines/linux/quick-create-portal), [Powershell](https://docs.microsoft.com/en-us/azure/virtual-machines/linux/quick-create-powershell), [CLI](https://docs.microsoft.com/en-us/azure/virtual-machines/linux/quick-create-cli))
+ create Azure Resource Manager templates ([Portal](https://docs.microsoft.com/en-us/azure/azure-resource-manager/resource-manager-quickstart-create-templates-use-the-portal), [VS Code](https://docs.microsoft.com/en-us/azure/azure-resource-manager/resource-manager-quickstart-create-templates-use-visual-studio-code?tabs=CLI), [Visual Studio](https://docs.microsoft.com/en-us/azure/azure-resource-manager/vs-azure-tools-resource-groups-deployment-projects-create-deploy))
+ configure Azure Disk Encryption for VMs ([Windows](https://docs.microsoft.com/en-us/azure/security/azure-security-disk-encryption-windows), [Linux](https://docs.microsoft.com/en-us/azure/security/azure-security-disk-encryption-windows))

#### Create connectivity between virtual networks
+ [create and configure VNET peering](https://docs.microsoft.com/en-us/azure/virtual-network/virtual-network-manage-peering)
+ create and configure VNET to VNET ([Portal](https://docs.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-howto-vnet-vnet-resource-manager-portal), [Powershell](https://docs.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-vnet-vnet-rm-ps), [CLI](https://docs.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-howto-vnet-vnet-cli))
+ [verify virtual network connectivity](https://docs.microsoft.com/en-us/azure/virtual-network/virtual-network-configure-vnet-connections)
+ create virtual network gateway ([Portal](https://docs.microsoft.com/en-us/azure/vpn-gateway/create-routebased-vpn-gateway-portal), [Powershell](https://docs.microsoft.com/en-us/azure/vpn-gateway/create-routebased-vpn-gateway-powershell), [CLI](https://docs.microsoft.com/en-us/azure/vpn-gateway/create-routebased-vpn-gateway-cli))

#### Implement and manage virtual networking
+ [configure private and public IP addresses, network routes, network interface, subnets, and virtual network](https://docs.microsoft.com/en-us/azure/virtual-network/manage-virtual-network)

#### Manage Azure Active Directory (AD)
+ [add custom domains](https://docs.microsoft.com/en-us/azure/active-directory/fundamentals/add-custom-domain)
+ configure [Azure AD Identity Protection](https://docs.microsoft.com/en-us/azure/active-directory/identity-protection/enable), [Azure AD Join](https://docs.microsoft.com/en-us/azure/active-directory/devices/device-management-azure-portal), and [Enterprise State Roaming](https://docs.microsoft.com/en-us/azure/active-directory/devices/enterprise-state-roaming-enable)
+ [configure self-service password reset](https://docs.microsoft.com/en-us/azure/active-directory/authentication/howto-sspr-deployment)
+ [implement conditional access policies](https://docs.microsoft.com/en-us/azure/active-directory/conditional-access/concept-conditional-access-policies)
+ [manage multiple directories](https://docs.microsoft.com/en-us/azure/active-directory/users-groups-roles/licensing-directory-independence)
+ [perform an access review](https://docs.microsoft.com/en-us/azure/active-directory/governance/create-access-review)

#### Implement and manage hybrid identities
+ [install and configure Azure AD Connect](https://docs.microsoft.com/en-us/azure/active-directory/hybrid/how-to-connect-install-express)
+ configure [AD federation](https://docs.microsoft.com/en-us/azure/active-directory/hybrid/how-to-connect-fed-management) and [AD single sign-on](https://docs.microsoft.com/en-us/azure/active-directory/hybrid/how-to-connect-sso-quick-start)
+ [manage Azure AD Connect](https://docs.microsoft.com/en-us/azure/active-directory/hybrid/how-to-connect-post-installation)
+ manage AD Connect [password sync](https://docs.microsoft.com/en-us/azure/active-directory/hybrid/how-to-connect-password-hash-synchronization) and [writeback](https://docs.microsoft.com/en-us/azure/active-directory/hybrid/how-to-connect-device-writeback)

## Implement workloads and security (20-25%)

#### Migrate servers to Azure
+ [migrate by using Azure Site Recovery]()
+ [migrate using P2V]()
+ [configure storage]()
+ [create a backup vault]()
+ [prepare source and target environments]()
+ [backup and restore data]()
+ [deploy Azure Site Recovery agent]()
+ [prepare virtual network]()

#### Configure serverless computing
+ [manage a Logic App resource]()
+ [manage Azure Function app settings]()
+ [manage Event Grid]()
+ [manage Service Bus]()

#### Implement application load balancing
+ [configure application gateway and load balancing rules]()
+ [implement front end IP configurations]()
+ [manage application load balancing]()

#### Integrate on-premises network with Azure virtual network
+ [create and configure Azure VPN Gateway]()
+ [create and configure site to site VPN]()
+ [configure Express Route]()
+ [verify on-premises connectivity]()
+ [manage on-premises connectivity with Azure]()

#### Manage role-based access control (RBAC)
+ [create a custom role]()
+ [configure access to Azure resources by assigning roles]()
+ [configure management access to Azure]()
+ [troubleshoot RBAC]()
+ [implement RBAC policies]()
+ [assign RBAC roles]()

#### Implement Multi-Factor Authentication (MFA)
+ [enable MFA for an Azure tenant]()
+ [configure user accounts for MFA]()
+ [configure fraud alerts]()
+ [configure bypass options]()
+ [configure trusted IPs]()
+ [configure verification methods]()
+ [manage role-based access control (RBAC)]()
+ [implement RBAC policies]()
+ [assign RBAC Roles]()
+ [create a custom role]()
+ [configure access to Azure resources by assigning roles]()
+ [configure management access to Azure]()

## Create and deploy apps (5-10%)

#### Create web apps by using PaaS
+ [create an Azure App Service Web App](https://docs.microsoft.com/en-us/azure/app-service/app-service-web-get-started-dotnet)
+ [create documentation for the API](https://docs.microsoft.com/en-us/aspnet/core/tutorials/getting-started-with-swashbuckle?view=aspnetcore-3.0&tabs=visual-studio)
+ [create an App Service Web App for containers](https://docs.microsoft.com/en-us/azure/app-service/containers/quickstart-docker)
+ [create an App Service background task by using WebJobs](https://docs.microsoft.com/en-us/azure/app-service/webjobs-create)
+ [enable diagnostics logging](https://docs.microsoft.com/en-us/azure/app-service/troubleshoot-diagnostic-logs)

#### Design and develop apps that run in containers
+ [configure diagnostic settings on resources]()
+ [create a container image by using a Docker file](https://docs.microsoft.com/en-us/azure/app-service/containers/tutorial-custom-docker-image)
+ [create an Azure Kubernetes Service](https://docs.microsoft.com/en-us/azure/aks/kubernetes-walkthrough)
+ [publish an image to the Azure Container Registry](https://docs.microsoft.com/en-us/learn/modules/build-and-store-container-images/)
+ [implement an application that runs on an Azure Container Instance](https://docs.microsoft.com/en-us/learn/modules/run-docker-with-azure-container-instances/)
+ [manage container settings by using code]()

## Implement authentication and secure data (5-10%)

#### [Implement authentication](https://docs.microsoft.com/en-us/azure/active-directory/develop/)
+ [implement authentication by using certificates, forms-based authentication, tokens, or Windows-integrated authentication]()
+ [implement multi-factor authentication by using Azure AD](https://docs.microsoft.com/en-us/azure/active-directory/authentication/howto-mfa-getstarted)
+ [implement OAuth2 authentication](https://docs.microsoft.com/en-us/azure/active-directory/develop/v1-protocols-oauth-code#register-your-application-with-your-ad-tenant)
+ [implement Managed identities for Azure resources Service Principal authentication](https://www.pluralsight.com/courses/microsoft-azure-resources-managed-identities-implementing)

#### Implement secure data solutions
+ [encrypt and decrypt data at rest and in transit]()
+ [encrypt data with Always Encrypted]()
+ [implement Azure Confidential Compute and SSL/TLS communications]()
+ [create, read, update, and delete keys, secrets, and certificates by using the KeyVault API]()

## Develop for the cloud and for Azure storage (20-25%)

#### Develop solutions that use Cosmos DB storage
+ [create, read, update, and delete data by using appropriate APIs]()
+ [implement partitioning schemes]()
+ [set the appropriate consistency level for operations]()

#### Develop solutions that use a relational database
+ [provision and configure relational databases]()
+ [configure elastic pools for Azure SQL Database]()
+ [create, read, update, and delete data tables by using code]()

#### Configure a message-based integration architecture
+ [configure an app or service to send emails, Event Grid, and the Azure Relay Service]()
+ [create and configure Notification Hub, Event Hub, and Service Bus]()
+ [configure queries across multiple products]()

#### Develop for autoscaling
+ [implement autoscaling rules and patterns (schedule, operational/system metrics, code that addresses singleton application instances)]()
+ [implement code that addresses transient state]()

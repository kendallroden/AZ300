# AZ-300 study guide materials 

Skills measured: 
+ [Deploy and configure infrastructure](#deploy-and-configure-infrastructure-25-30)
+ [Implement workloads and security](#implement-workloads-and-security-20-25)
+ [Create and deploy apps](#create-and-deploy-apps-5-10)
+ [Implement authentication and secure data](#implement-authentication-and-secure-data-5-10)
+ [Develop for the cloud and for Azure storage](#develop-for-the-cloud-and-for-azure-storage-20-25)
 
Additional Links: 
+ [Study Notes for the AZ-300 exam](https://github.com/toddbadams/az300)
+ [Pluralsight course](https://www.pluralsight.com/paths/microsoft-azure-architect-technologies-az-300)
+ [A Cloud Guru course](https://acloud.guru/learn/az-300-architect-technologies-2019)
+ [Udemy course](https://www.udemy.com/course/70534-azure/)
  
## Deploy and configure infrastructure (25-30%)

Hands-on Training: 
+ [OPENedX Course:Deploy and Configure Infrastructure](https://courses.microsoft.com/courses/course-v1:ELMS+AZ-300.1+2019_T2/course/)
+ [Packt Exam Guide](https://github.com/PacktPublishing/Microsoft-Azure-Architect-Technologies-Exam-Guide-AZ-300)

#### Analyze resource utilization and consumption
+ [configure diagnostic settings on resources](https://docs.microsoft.com/en-us/azure/azure-monitor/platform/diagnostic-settings)
+ [create baseline for resources](https://docs.microsoft.com/en-us/azure/azure-monitor/platform/alerts-dynamic-thresholds)
+ [create and test alerts](https://docs.microsoft.com/en-us/azure/azure-monitor/platform/alerts-metric)
+ [analyze alerts across subscription](https://docs.microsoft.com/en-us/azure/azure-monitor/platform/alerts-unified-log)
+ [analyze metrics across subscription](https://docs.microsoft.com/en-us/azure/azure-monitor/platform/data-platform)
+ [create action groups](https://docs.microsoft.com/en-us/azure/azure-monitor/platform/action-groups)
+ [monitor for unused resources](https://docs.microsoft.com/en-us/azure/advisor/advisor-overview)
+ [monitor spend](https://docs.microsoft.com/en-us/azure/billing/billing-getting-started)
+ [report on spend](https://docs.microsoft.com/en-us/azure/billing/billing-understand-your-bill)
+ [utilize Log Search query functions](https://docs.microsoft.com/en-us/azure/azure-monitor/log-query/log-query-overview)
+ [view alerts in Azure Monitor logs](https://docs.microsoft.com/en-us/azure/azure-monitor/platform/alert-management-solution)
+ [visualize diagnostics data using Azure Monitor Workbooks](https://docs.microsoft.com/en-us/azure/azure-monitor/app/usage-workbooks)

#### Create and configure storage accounts
+ [configure network access to the storage account](https://docs.microsoft.com/en-us/azure/storage/common/storage-network-security)
+ [create and configure storage account](https://docs.microsoft.com/en-us/azure/storage/common/storage-quickstart-create-account?tabs=azure-portal)
+ [generate shared access signature](https://docs.microsoft.com/en-us/azure/storage/common/storage-sas-overview)
+ [implement Azure AD authentication for storage
](https://docs.microsoft.com/en-us/azure/storage/common/storage-auth-aad)
+ [install and use Azure Storage Explorer](https://docs.microsoft.com/en-us/azure/vs-azure-tools-storage-manage-with-storage-explorer?tabs=windows)
+ [manage access keys](https://docs.microsoft.com/en-us/azure/key-vault/key-vault-ovw-storage-keys)
+ [monitor activity log by using Azure Monitor logs](https://docs.microsoft.com/en-us/azure/storage/common/storage-metrics-in-azure-monitor)
+ [implement Azure storage replication](https://docs.microsoft.com/en-us/azure/storage/blobs/storage-create-geo-redundant-storage?tabs=dotnet)
+ [implement Azure storage account failover](https://docs.microsoft.com/en-us/azure/storage/common/storage-disaster-recovery-guidance)

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
+ implement dedicated hosts (https://docs.microsoft.com/en-us/azure/virtual-machines/windows/dedicated-hosts)
+ deploy and configure scale sets ([Windows](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/tutorial-create-vmss), [Linux](https://docs.microsoft.com/en-us/azure/virtual-machines/linux/tutorial-create-vmss))

#### Automate deployment of Virtual Machines (VMs)
+ modify Azure Resource Manager template ([Portal](https://docs.microsoft.com/en-us/azure/azure-resource-manager/resource-manager-quickstart-create-templates-use-the-portal), [VS Code](https://docs.microsoft.com/en-us/azure/azure-resource-manager/resource-manager-quickstart-create-templates-use-visual-studio-code?tabs=CLI), [Visual Studio](https://docs.microsoft.com/en-us/azure/azure-resource-manager/vs-azure-tools-resource-groups-deployment-projects-create-deploy))
+ [configure location of new VMs](https://docs.microsoft.com/en-us/azure/azure-resource-manager/resource-group-authoring-templates#resources)
+ [configure VHD template](https://docs.microsoft.com/en-us/azure/marketplace/cloud-partner-portal/virtual-machine/cpp-deploy-json-template)
+ deploy from template ([Portal](https://docs.microsoft.com/en-us/azure/azure-resource-manager/resource-group-template-deploy), [CLI](https://docs.microsoft.com/en-us/azure/azure-resource-manager/resource-group-template-deploy-cli), [Powershell](https://docs.microsoft.com/en-us/azure/azure-resource-manager/resource-group-template-deploy))
+ [save a deployment as an Azure Resource Manager template](https://docs.microsoft.com/en-us/azure/azure-resource-manager/manage-resources-portal)
+ deploy Windows and Linux VMs ([Windows](https://azure.microsoft.com/en-us/resources/templates/101-vm-tags/), [Linux](https://azure.microsoft.com/en-us/resources/templates/101-vm-simple-linux/))

#### Create connectivity between virtual networks
+ [create and configure VNET peering](https://docs.microsoft.com/en-us/azure/virtual-network/virtual-network-manage-peering)
+ create and configure VNET to VNET ([Portal](https://docs.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-howto-vnet-vnet-resource-manager-portal), [Powershell](https://docs.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-vnet-vnet-rm-ps), [CLI](https://docs.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-howto-vnet-vnet-cli))
+ [verify virtual network connectivity](https://docs.microsoft.com/en-us/azure/virtual-network/virtual-network-configure-vnet-connections)
+ create virtual network gateway ([Portal](https://docs.microsoft.com/en-us/azure/vpn-gateway/create-routebased-vpn-gateway-portal), [Powershell](https://docs.microsoft.com/en-us/azure/vpn-gateway/create-routebased-vpn-gateway-powershell), [CLI](https://docs.microsoft.com/en-us/azure/vpn-gateway/create-routebased-vpn-gateway-cli))

#### Implement and manage virtual networking
+ [configure private and public IP addresses, network routes, network interface, subnets, and virtual network](https://docs.microsoft.com/en-us/azure/virtual-network/manage-virtual-network)
+ [create and configure Network Security Groups and Application Security Groups](https://docs.microsoft.com/en-us/azure/virtual-network/security-overview)

#### Manage Azure Active Directory (AD)
+ [add custom domains](https://docs.microsoft.com/en-us/azure/active-directory/fundamentals/add-custom-domain)
+ configure [Azure AD Identity Protection](https://docs.microsoft.com/en-us/azure/active-directory/identity-protection/overview-identity-protection), [Azure AD Join](https://docs.microsoft.com/en-us/azure/active-directory/devices/azureadjoin-plan), and [Enterprise State Roaming](https://docs.microsoft.com/en-us/azure/active-directory/devices/enterprise-state-roaming-enable)
+ [configure self-service password reset](https://docs.microsoft.com/en-us/azure/active-directory/authentication/howto-sspr-deployment)
+ [implement conditional access policies](https://docs.microsoft.com/en-us/azure/active-directory/conditional-access/concept-conditional-access-policies)
+ [manage multiple directories](https://docs.microsoft.com/en-us/azure/active-directory/users-groups-roles/licensing-directory-independence)
+ [perform an access review](https://docs.microsoft.com/en-us/azure/active-directory/governance/create-access-review)

#### Implement and manage hybrid identities
+ [install and configure Azure AD Connect](https://docs.microsoft.com/en-us/azure/active-directory/hybrid/how-to-connect-install-express)
+ configure [federation](https://docs.microsoft.com/en-us/azure/active-directory/hybrid/how-to-connect-fed-management) and [single sign-on](https://docs.microsoft.com/en-us/azure/active-directory/hybrid/how-to-connect-sso-quick-start)
+ [manage Azure AD Connect](https://docs.microsoft.com/en-us/azure/active-directory/hybrid/how-to-connect-post-installation)
+ troubleshoot [password sync](https://docs.microsoft.com/en-us/azure/active-directory/hybrid/how-to-connect-password-hash-synchronization) and [writeback](https://docs.microsoft.com/en-us/azure/active-directory/hybrid/how-to-connect-device-writeback)

#### Implement solutions that use virtual machines (VM)
+ Provision VMs
  + Windows ([Portal](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/quick-create-portal), [Powershell](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/quick-create-powershell), [CLI](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/quick-create-cli))
  + Linux ([Portal](https://docs.microsoft.com/en-us/azure/virtual-machines/linux/quick-create-portal), [Powershell](https://docs.microsoft.com/en-us/azure/virtual-machines/linux/quick-create-powershell), [CLI](https://docs.microsoft.com/en-us/azure/virtual-machines/linux/quick-create-cli))
+ create Azure Resource Manager templates ([Portal](https://docs.microsoft.com/en-us/azure/azure-resource-manager/resource-manager-quickstart-create-templates-use-the-portal), [VS Code](https://docs.microsoft.com/en-us/azure/azure-resource-manager/resource-manager-quickstart-create-templates-use-visual-studio-code?tabs=CLI), [Visual Studio](https://docs.microsoft.com/en-us/azure/azure-resource-manager/vs-azure-tools-resource-groups-deployment-projects-create-deploy))
+ configure Azure Disk Encryption for VMs ([Windows](https://docs.microsoft.com/en-us/azure/virtual-machines/extensions/azure-disk-enc-windows), [Linux](https://docs.microsoft.com/en-us/azure/security/azure-security-disk-encryption-windows))
+ [implement Azure Backup for VMs] (https://docs.microsoft.com/en-us/azure/backup/backup-azure-vms-introduction)

## Implement workloads and security (20-25%)

#### Migrate servers to Azure
+ [~~migrate using P2V~~](https://docs.microsoft.com/en-us/azure/site-recovery/physical-azure-disaster-recovery)
+ [migrate servers using Azure Migrate](https://docs.microsoft.com/en-us/azure/site-recovery/migrate-tutorial-on-premises-azure)
+ [~~configure storage~~](https://docs.microsoft.com/en-us/azure/site-recovery/tutorial-prepare-azure)
+ [~~create a recovery services vault~~](https://docs.microsoft.com/en-us/azure/backup/backup-sql-server-database-azure-vms#create-a-recovery-services-vault)
+ [~~prepare source~~](https://docs.microsoft.com/en-us/azure/site-recovery/physical-azure-set-up-source)
+ [backup and restore data](https://docs.microsoft.com/en-us/azure/backup/backup-azure-recovery-services-vault-overview)
+ [~~deploy Azure Site Recovery agent~~](https://docs.microsoft.com/en-us/azure/site-recovery/vmware-physical-mobility-service-overview)
+ [~~prepare virtual network~~](https://docs.microsoft.com/en-us/azure/site-recovery/tutorial-prepare-azure#set-up-an-azure-network)

#### Configure serverless computing
+ create and manage objects
+ [manage a Logic App resource](https://docs.microsoft.com/en-us/azure/logic-apps/https://docs.microsoft.com/en-us/azure/azure-functions/functions-how-to-use-azure-function-app-settings)
+ [manage Azure Function app settings](https://docs.microsoft.com/en-us/azure/azure-functions/functions-how-to-use-azure-function-app-settings)
+ [manage Event Grid](https://docs.microsoft.com/en-us/azure/event-grid/)
+ [manage Service Bus](https://docs.microsoft.com/en-gb/azure/service-bus-messaging/)

#### Implement application load balancing
+ configure application gateway
+ [~~configure application gateway and load balancing rules~~](https://docs.microsoft.com/en-us/azure/load-balancer/load-balancer-overview)
+ [~~implement application gateway front end IP configurations~~](https://docs.microsoft.com/en-us/azure/load-balancer/load-balancer-multivip-overview)
+ [~~troubleshoot application gateway loadbalancing~~](https://docs.microsoft.com/en-us/azure/application-gateway/overview)
+ [configure Azure Front Door service](https://docs.microsoft.com/en-us/azure/frontdoor/)
+ [configure Azure Traffic Manager](https://docs.microsoft.com/en-us/azure/traffic-manager/)

#### Integrate on-premises network with Azure virtual network
+ create and configure Azure VPN Gateway ([Portal](https://docs.microsoft.com/en-us/azure/vpn-gateway/create-routebased-vpn-gateway-portal), [CLI](https://docs.microsoft.com/en-us/azure/vpn-gateway/create-routebased-vpn-gateway-cli), [PowerShell](https://docs.microsoft.com/en-us/azure/vpn-gateway/create-routebased-vpn-gateway-powershell))
+ create and configure site to site VPN ([Portal](https://docs.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-howto-site-to-site-resource-manager-portal), [CLI](https://docs.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-howto-site-to-site-resource-manager-cli), [PowerShell](https://docs.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-create-site-to-site-rm-powershell))
+ [configure Express Route](https://docs.microsoft.com/en-us/azure/expressroute/expressroute-howto-circuit-portal-resource-manager)
+ [configure Virtual WAN] (https://docs.microsoft.com/en-us/azure/virtual-wan/virtual-wan-about)
+ [verify on-premises connectivity](https://docs.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-validate-throughput-to-vnet)
+ [manage on-premises connectivity with Azure](https://docs.microsoft.com/en-us/office365/enterprise/connect-an-on-premises-network-to-a-microsoft-azure-virtual-network)

#### Implement Multi-Factor Authentication (MFA)
+ [enable MFA for an Azure tenant](https://docs.microsoft.com/en-us/azure/active-directory/authentication/howto-mfa-getstarted#enable-azure-multi-factor-authentication)
+ [configure user accounts for MFA](https://docs.microsoft.com/en-us/azure/active-directory/authentication/howto-mfa-userstates)
+ [configure fraud alerts](https://docs.microsoft.com/en-us/azure/active-directory/authentication/howto-mfa-mfasettings#fraud-alert)
+ [configure bypass options](https://docs.microsoft.com/en-us/azure/active-directory/authentication/howto-mfa-mfasettings#one-time-bypass)
+ [configure trusted IPs](https://docs.microsoft.com/en-us/azure/active-directory/authentication/howto-mfa-mfasettings#trusted-ips)
+ [configure verification methods](https://docs.microsoft.com/en-us/azure/active-directory/authentication/howto-mfa-mfasettings#selectable-verification-methods)

#### Manage role-based access control (RBAC)
+ [create a custom role](https://docs.microsoft.com/en-us/azure/role-based-access-control/custom-roles)
+ configure access to Azure resources by assigning roles ([Portal](https://docs.microsoft.com/en-us/azure/role-based-access-control/role-assignments-portal), [CLI](https://docs.microsoft.com/en-us/azure/role-based-access-control/role-assignments-cli), [PowerShell](https://docs.microsoft.com/en-us/azure/role-based-access-control/role-assignments-powershell), [REST](https://docs.microsoft.com/en-us/azure/role-based-access-control/role-assignments-rest)))
+ [configure management access to Azure](https://docs.microsoft.com/en-us/azure/active-directory/users-groups-roles/directory-admin-roles-secure)
+ [troubleshoot RBAC](https://docs.microsoft.com/en-us/azure/role-based-access-control/troubleshooting)
+ [implement RBAC policies](https://docs.microsoft.com/en-us/azure/role-based-access-control/overview)
+ [assign RBAC roles](https://docs.microsoft.com/en-us/azure/role-based-access-control/rbac-and-directory-admin-roles)

## Create and deploy apps (5-10%)

#### Create web apps by using PaaS
+ [create an Azure App Service Web App](https://docs.microsoft.com/en-us/azure/app-service/app-service-web-get-started-dotnet)
+ [create documentation for the API](https://docs.microsoft.com/en-us/aspnet/core/tutorials/getting-started-with-swashbuckle?view=aspnetcore-3.0&tabs=visual-studio)
+ [create an App Service Web App for containers](https://docs.microsoft.com/en-us/azure/app-service/containers/quickstart-docker)
+ [create an App Service background task by using WebJobs](https://docs.microsoft.com/en-us/azure/app-service/webjobs-create)
+ [enable diagnostics logging](https://docs.microsoft.com/en-us/azure/app-service/troubleshoot-diagnostic-logs)

#### Design and develop apps that run in containers
+ configure diagnostic settings on resources
+ [create a container image by using a Docker file](https://docs.microsoft.com/en-us/azure/app-service/containers/tutorial-custom-docker-image)
+ [create an Azure Kubernetes Service](https://docs.microsoft.com/en-us/azure/aks/kubernetes-walkthrough)
+ [publish an image to the Azure Container Registry](https://docs.microsoft.com/en-us/learn/modules/build-and-store-container-images/)
+ [implement an application that runs on an Azure Container Instance](https://docs.microsoft.com/en-us/learn/modules/run-docker-with-azure-container-instances/)
+ manage container settings by using code

## Implement authentication and secure data (5-10%)

#### [Implement authentication](https://docs.microsoft.com/en-us/azure/active-directory/develop/)
+ implement authentication by using certificates, forms-based authentication, tokens, or Windows-integrated authentication
  + [Certificates](https://docs.microsoft.com/en-us/azure/active-directory/authentication/active-directory-certificate-based-authentication-get-started)
  + [Forms-Based](https://social.technet.microsoft.com/wiki/contents/articles/3669.azure-active-directory-solutions-for-developers.aspx)
  + [Tokens](https://docs.microsoft.com/en-us/azure/active-directory/develop/v1-protocols-oauth-code)
  + [Windows-integrated](https://docs.microsoft.com/en-us/aspnet/web-api/overview/security/integrated-windows-authentication)
+ [implement multi-factor authentication by using Azure AD](https://docs.microsoft.com/en-us/azure/active-directory/authentication/howto-mfa-getstarted)
+ [implement OAuth2 authentication](https://docs.microsoft.com/en-us/azure/active-directory/develop/v1-protocols-oauth-code#register-your-application-with-your-ad-tenant)
+ [implement Managed identities for Azure resources Service Principal authentication](https://www.pluralsight.com/courses/microsoft-azure-resources-managed-identities-implementing)

#### Implement secure data solutions
+ encrypt and decrypt data at rest and in transit([best practices](https://docs.microsoft.com/en-us/azure/security/fundamentals/data-encryption-best-practices),[encryption at rest](https://docs.microsoft.com/en-us/azure/security/fundamentals/encryption-atrest))
+ [encrypt data with Always Encrypted](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-always-encrypted-azure-key-vault)
+ implement Azure Confidential Compute and SSL/TLS communications([confidential compute](https://azuremarketplace.microsoft.com/en-us/marketplace/apps/microsoft-azure-compute.confidentialcompute?tab=Overview))
+ create, read, update, and delete keys, secrets, and certificates by using the KeyVault API([client samples](https://www.microsoft.com/en-us/download/details.aspx?id=45343),[api reference](https://docs.microsoft.com/en-us/azure/key-vault/key-vault-manage-with-cli2),[key vault learning module](https://docs.microsoft.com/en-us/learn/modules/manage-secrets-with-azure-key-vault/))

## Develop for the cloud and for Azure storage (20-25%)

#### Develop solutions that use Cosmos DB storage
+ create, read, update, and delete data by using appropriate APIs([local emulator](https://docs.microsoft.com/en-us/azure/cosmos-db/local-emulator), [microsoft learn](https://docs.microsoft.com/en-us/learn/modules/build-cosmos-db-app-with-vscode/))
+ [implement partitioning schemes](https://docs.microsoft.com/en-us/learn/modules/monitor-and-scale-cosmos-db/)
+ [set the appropriate consistency level for operations](https://docs.microsoft.com/en-us/azure/cosmos-db/how-to-manage-consistency)

#### Develop solutions that use a relational database
+ provision and configure relational database([.NET](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-design-first-database-csharp),[SSMS](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-design-first-database])
+ [configure elastic pools for Azure SQL Database](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-elastic-pool)
+ [implement Azure SQL Database managed instances](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-managed-instance)
+ [create, read, update, and delete data tables by using code](https://docs.microsoft.com/en-us/learn/paths/work-with-relational-data-in-azure/)

#### Configure a message-based integration architecture
+ [configure an app or service to send emails](https://docs.microsoft.com/en-us/azure/sendgrid-dotnet-how-to-send-email), [Event Grid](https://docs.microsoft.com/en-us/samples/azure-samples/event-grid-dotnet-publish-consume-events/event-grid-dotnet-publish-consume-events/), and the [Azure Relay Service](https://docs.microsoft.com/en-us/azure/service-bus-relay/relay-hybrid-connections-http-requests-dotnet-get-started)
+ create and configure [Notification Hub](https://github.com/Azure/azure-notificationhubs-dotnet/tree/master/Samples), [Event Hub](https://docs.microsoft.com/en-us/azure/event-hubs/event-hubs-samples), and [Service Bus](https://docs.microsoft.com/en-us/azure/service-bus-messaging/service-bus-samples)  
+ [configure queries across multiple products]()

#### Develop for autoscaling
+ [implement autoscaling rules and patterns](https://docs.microsoft.com/en-us/azure/azure-monitor/platform/autoscale-overview)([schedule and operational/system metrics](https://docs.microsoft.com/en-us/azure/azure-monitor/platform/autoscale-get-started), code that addresses singleton application instance)
+ [implement code that addresses transient state](https://docs.microsoft.com/en-us/aspnet/aspnet/overview/developing-apps-with-windows-azure/building-real-world-cloud-apps-with-windows-azure/transient-fault-handling)

Includes: 
Azure Active Directory(now Microsoft Entra ID)
Permissions Management 
Verified ID 

Microsoft Entra

(Azure) Active Directory Domain Services 

Azure Active Directory (now Microsoft Entra ID)

## Azure AD vs. AD
### Azure AD:
***Uses modern architecture, protocols, and methods with a cloud-native design*
1. Modern Office Solution
	1. Azure Active Directory is designed for cloud-enabled devices, services, and platforms. 
2. Modern Web
	1. Azure Active Directory was designed with Web 2.0 in mind and can integrate most complex web applications now and into the future. 
3. Modern Authentication 
	1. Azure Active Directory authentication supports modern authentication protocols as well as modern authentication methods, like MFA. 

### Active Directory:
***Legacy architecture, protocols, and methods with on-premises/datacenter design 
1. Legacy Office Solution
	1. Active Directory implemented several older technologies to connect devices, like computers and printers. 
2. Active Directory was not designed within the era of Web 2.0 witrh its social media sites and the advent of complex web applications in mind.
3. Legacy Authentication 
	1. Active Directory authentication uses services and protocols that are not available on Azure 
## Azure Active Directory (Entra ID)
### Requirements:
- Automatic/mandatory
	- Every Azure account automatically has an Azure AD instance with it 
- Minimun of one user 
	- Every Azure AD instance needs at least one user, and this user is created with the initial Azure AD instance 
- Optional:
	- custom domain name 
	- Azure AD Connect (if on-premises AD present)
### Tenant
1. Organization 
	1. A tenant represents the organization. 
2. Dedicated Azure AD
	1. A tenant is a dedicated instance of Azure AD that an organization receives when signing up for Azure. 
3. Separate 
	1. Each tenant is distinct and completely separate from other Azure AD tenants.
4. Max 500 Tenants 
	1. Each user in Azure can be a member of guest of up to 500 Azure AD tenants. 
### Subscription
1.  Billing Entity 
	1. All resources within a subscription are billed together. 
2. Cost Separation
	1. You can have multiple subscriptions within a tenant to separate costs.
3. Payment 
	1. If a subscription isn't paid, all the resources and services associated with the subscription stop. 

![](attachments/Pasted%20image%2020250114132322.png)
### Summary
- Microsoft Entra is a product family that includes Azure Active Directory/Microsoft Entra ID
- Active Directory (AD) ***Is not*** the same as Azure Active Directory. 
- Azure Active Directory has been renamed Microsoft Entra ID. 
- Every Azure account will have an Azure AD/Entra ID service. 
- A tenant is a dedication instance of Azure AD/Entra ID. It represents your organization in Azure. 
- A user can be a member or guest of up to 500 tenants. 
- A subscription is a billing entity. All resources belong to a single subscription.
- Azure AD/ Entra ID can help mange users in a hybrid cloud setup. 
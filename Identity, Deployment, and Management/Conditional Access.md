## Concepts 
- If/then policy to grant access 
	- If (user) meets these conditions (signals), then grant/block access to defined applications. 
- Often paired with MFA
	- Centrally applied MFA enforcement 
		- Does not rely on end user enabling MFA

## How it Works
### Create Conditional Access Policy
- Assign signal (conditions)
	- Users/groups
	- Application to grant/deny access 
	- Location (IP)
	- Approved devices 
- Access decisions (grant/block access)
	- Grant access 
	- Block access 
	- Require MFA

## Conditional Access Scenarios 
- Enforce MFA for all administrators/all users 
- Block sign-ins using legacy authentication protocols 
- Grant access only to specific locations
- Require organization-managed devices for application sign-in
# Summary 
- Conditional Access is a feature that provides an additional layer of security to your environments and identity. 
- Conditional Access rule are essentially if/then statements that permit or deny access depending on whether the rules are met. 
- Multi-factor authentication is often implemented with Conditional Access as further security. 
- Modern best practices encourage the use of Conditional Access. 
### Typically, Azure AD defines users in three ways:

#### Cloud identities 
These users exist only in Azure AD. Examples are administrator accounts and users that you manage yourself. Cloud identities can be in Azure Active Directory or an external Azure Active Directory, if the user is defined in another Azure AD instance. When these accounts are removed from the primary directory, they are deleted.

#### Directory-synchronized identities 
These users exist in an on-premises Active Directory. A synchronization activity that occurs via Azure AD Connect brings these users in to Azure. Their source is Windows Server AD.

#### Guest users
These users exist outside Azure. Examples are accounts from other cloud providers and Microsoft accounts such as an Xbox LIVE account. Their source is Invited user. This type of account is useful when external vendors or contractors need access to your Azure resources. Once their help is no longer necessary, you can remove the account and all of their access.


### There are multiple ways to add cloud identities to Azure AD.
#### Things to consider when managing users:
- User profile (picture, job, contact info) is optional.
- Deleted users can be restored for 30 days.
- Sign in and audit log information is available.
---
external help file:
Module Name: Az.Resources
online version: https://docs.microsoft.com/powershell/module/az.resources/update-azadserviceprincipal
schema: 2.0.0
---

# Update-AzADServicePrincipal

## SYNOPSIS
Updates entity in service principal

## SYNTAX

### SpObjectIdWithDisplayNameParameterSet (Default)
```
Update-AzADServicePrincipal -ObjectId <String> [-AccountEnabled] [-AddIn <IMicrosoftGraphAddIn[]>]
 [-AlternativeName <String[]>] [-AppDescription <String>] [-AppOwnerOrganizationId <String>]
 [-AppRole <IMicrosoftGraphAppRole[]>] [-AppRoleAssignedTo <IMicrosoftGraphAppRoleAssignment[]>]
 [-AppRoleAssignment <IMicrosoftGraphAppRoleAssignment[]>] [-AppRoleAssignmentRequired]
 [-ClaimsMappingPolicy <IMicrosoftGraphClaimsMappingPolicy[]>]
 [-DelegatedPermissionClassification <IMicrosoftGraphDelegatedPermissionClassification[]>]
 [-DeletedDateTime <DateTime>] [-Description <String>] [-DisabledByMicrosoftStatus <String>]
 [-DisplayName <String>] [-Endpoint <IMicrosoftGraphEndpoint[]>] [-Homepage <String>]
 [-HomeRealmDiscoveryPolicy <IMicrosoftGraphHomeRealmDiscoveryPolicy[]>] [-IdentifierUri <String[]>]
 [-Info <IMicrosoftGraphInformationalUrl>] [-KeyCredential <IMicrosoftGraphKeyCredential[]>]
 [-LoginUrl <String>] [-LogoutUrl <String>] [-Note <String>] [-NotificationEmailAddress <String[]>]
 [-Oauth2PermissionScope <IMicrosoftGraphPermissionScope[]>]
 [-PasswordCredential <IMicrosoftGraphPasswordCredential[]>] [-PreferredSingleSignOnMode <String>]
 [-PreferredTokenSigningKeyThumbprint <String>] [-ReplyUrl <String[]>]
 [-SamlSingleSignOnSetting <IMicrosoftGraphSamlSingleSignOnSettings>] [-ServicePrincipalType <String>]
 [-Tag <String[]>] [-TokenEncryptionKeyId <String>]
 [-TokenIssuancePolicy <IMicrosoftGraphTokenIssuancePolicy[]>]
 [-TokenLifetimePolicy <IMicrosoftGraphTokenLifetimePolicy[]>]
 [-TransitiveMemberOf <IMicrosoftGraphDirectoryObject[]>] [-DefaultProfile <PSObject>] [-PassThru] [-Confirm]
 [-WhatIf] [<CommonParameters>]
```

### InputObjectWithDisplayNameParameterSet
```
Update-AzADServicePrincipal -InputObject <IMicrosoftGraphServicePrincipal> [-AccountEnabled]
 [-AddIn <IMicrosoftGraphAddIn[]>] [-AlternativeName <String[]>] [-AppDescription <String>]
 [-AppOwnerOrganizationId <String>] [-AppRole <IMicrosoftGraphAppRole[]>]
 [-AppRoleAssignedTo <IMicrosoftGraphAppRoleAssignment[]>]
 [-AppRoleAssignment <IMicrosoftGraphAppRoleAssignment[]>] [-AppRoleAssignmentRequired]
 [-ClaimsMappingPolicy <IMicrosoftGraphClaimsMappingPolicy[]>]
 [-DelegatedPermissionClassification <IMicrosoftGraphDelegatedPermissionClassification[]>]
 [-DeletedDateTime <DateTime>] [-Description <String>] [-DisabledByMicrosoftStatus <String>]
 [-DisplayName <String>] [-Endpoint <IMicrosoftGraphEndpoint[]>] [-Homepage <String>]
 [-HomeRealmDiscoveryPolicy <IMicrosoftGraphHomeRealmDiscoveryPolicy[]>] [-IdentifierUri <String[]>]
 [-Info <IMicrosoftGraphInformationalUrl>] [-KeyCredential <IMicrosoftGraphKeyCredential[]>]
 [-LoginUrl <String>] [-LogoutUrl <String>] [-Note <String>] [-NotificationEmailAddress <String[]>]
 [-Oauth2PermissionScope <IMicrosoftGraphPermissionScope[]>]
 [-PasswordCredential <IMicrosoftGraphPasswordCredential[]>] [-PreferredSingleSignOnMode <String>]
 [-PreferredTokenSigningKeyThumbprint <String>] [-ReplyUrl <String[]>]
 [-SamlSingleSignOnSetting <IMicrosoftGraphSamlSingleSignOnSettings>] [-ServicePrincipalType <String>]
 [-Tag <String[]>] [-TokenEncryptionKeyId <String>]
 [-TokenIssuancePolicy <IMicrosoftGraphTokenIssuancePolicy[]>]
 [-TokenLifetimePolicy <IMicrosoftGraphTokenLifetimePolicy[]>]
 [-TransitiveMemberOf <IMicrosoftGraphDirectoryObject[]>] [-DefaultProfile <PSObject>] [-PassThru] [-Confirm]
 [-WhatIf] [<CommonParameters>]
```

### SpApplicationIdWithDisplayNameParameterSet
```
Update-AzADServicePrincipal -ApplicationId <Guid> [-AccountEnabled] [-AddIn <IMicrosoftGraphAddIn[]>]
 [-AlternativeName <String[]>] [-AppDescription <String>] [-AppOwnerOrganizationId <String>]
 [-AppRole <IMicrosoftGraphAppRole[]>] [-AppRoleAssignedTo <IMicrosoftGraphAppRoleAssignment[]>]
 [-AppRoleAssignment <IMicrosoftGraphAppRoleAssignment[]>] [-AppRoleAssignmentRequired]
 [-ClaimsMappingPolicy <IMicrosoftGraphClaimsMappingPolicy[]>]
 [-DelegatedPermissionClassification <IMicrosoftGraphDelegatedPermissionClassification[]>]
 [-DeletedDateTime <DateTime>] [-Description <String>] [-DisabledByMicrosoftStatus <String>]
 [-DisplayName <String>] [-Endpoint <IMicrosoftGraphEndpoint[]>] [-Homepage <String>]
 [-HomeRealmDiscoveryPolicy <IMicrosoftGraphHomeRealmDiscoveryPolicy[]>] [-IdentifierUri <String[]>]
 [-Info <IMicrosoftGraphInformationalUrl>] [-KeyCredential <IMicrosoftGraphKeyCredential[]>]
 [-LoginUrl <String>] [-LogoutUrl <String>] [-Note <String>] [-NotificationEmailAddress <String[]>]
 [-Oauth2PermissionScope <IMicrosoftGraphPermissionScope[]>]
 [-PasswordCredential <IMicrosoftGraphPasswordCredential[]>] [-PreferredSingleSignOnMode <String>]
 [-PreferredTokenSigningKeyThumbprint <String>] [-ReplyUrl <String[]>]
 [-SamlSingleSignOnSetting <IMicrosoftGraphSamlSingleSignOnSettings>] [-ServicePrincipalType <String>]
 [-Tag <String[]>] [-TokenEncryptionKeyId <String>]
 [-TokenIssuancePolicy <IMicrosoftGraphTokenIssuancePolicy[]>]
 [-TokenLifetimePolicy <IMicrosoftGraphTokenLifetimePolicy[]>]
 [-TransitiveMemberOf <IMicrosoftGraphDirectoryObject[]>] [-DefaultProfile <PSObject>] [-PassThru] [-Confirm]
 [-WhatIf] [<CommonParameters>]
```

### SPNWithDisplayNameParameterSet
```
Update-AzADServicePrincipal -ServicePrincipalName <String> [-AccountEnabled] [-AddIn <IMicrosoftGraphAddIn[]>]
 [-AlternativeName <String[]>] [-AppDescription <String>] [-AppOwnerOrganizationId <String>]
 [-AppRole <IMicrosoftGraphAppRole[]>] [-AppRoleAssignedTo <IMicrosoftGraphAppRoleAssignment[]>]
 [-AppRoleAssignment <IMicrosoftGraphAppRoleAssignment[]>] [-AppRoleAssignmentRequired]
 [-ClaimsMappingPolicy <IMicrosoftGraphClaimsMappingPolicy[]>]
 [-DelegatedPermissionClassification <IMicrosoftGraphDelegatedPermissionClassification[]>]
 [-DeletedDateTime <DateTime>] [-Description <String>] [-DisabledByMicrosoftStatus <String>]
 [-DisplayName <String>] [-Endpoint <IMicrosoftGraphEndpoint[]>] [-Homepage <String>]
 [-HomeRealmDiscoveryPolicy <IMicrosoftGraphHomeRealmDiscoveryPolicy[]>] [-IdentifierUri <String[]>]
 [-Info <IMicrosoftGraphInformationalUrl>] [-KeyCredential <IMicrosoftGraphKeyCredential[]>]
 [-LoginUrl <String>] [-LogoutUrl <String>] [-Note <String>] [-NotificationEmailAddress <String[]>]
 [-Oauth2PermissionScope <IMicrosoftGraphPermissionScope[]>]
 [-PasswordCredential <IMicrosoftGraphPasswordCredential[]>] [-PreferredSingleSignOnMode <String>]
 [-PreferredTokenSigningKeyThumbprint <String>] [-ReplyUrl <String[]>]
 [-SamlSingleSignOnSetting <IMicrosoftGraphSamlSingleSignOnSettings>] [-ServicePrincipalType <String>]
 [-Tag <String[]>] [-TokenEncryptionKeyId <String>]
 [-TokenIssuancePolicy <IMicrosoftGraphTokenIssuancePolicy[]>]
 [-TokenLifetimePolicy <IMicrosoftGraphTokenLifetimePolicy[]>]
 [-TransitiveMemberOf <IMicrosoftGraphDirectoryObject[]>] [-DefaultProfile <PSObject>] [-PassThru] [-Confirm]
 [-WhatIf] [<CommonParameters>]
```

## DESCRIPTION
Updates entity in service principal

## EXAMPLES

### Example 1: Update service principal and associated application by display name
```powershell
Update-AzADServicePrincipal -DisplayName $name -IdentifierUri $uri
```

Update service principal and associated application by display name, 'IdentifierUri', 'PasswordCredential', 'KeyCredential' will be assigned to application

### Example 2: Update service principal by pipeline input
```powershell
Get-AzADServicePrincipal -ObjectId $id | Update-AzADServicePrincipal -Note $note
```

Update service principal and associated application by display name, 'IdentifierUri', 'PasswordCredential', 'KeyCredential' will be assigned to application

## PARAMETERS

### -AccountEnabled
true if the service principal account is enabled; otherwise, false.
Supports $filter (eq, ne, NOT, in).

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AddIn
Defines custom behavior that a consuming service can use to call an app in specific contexts.
For example, applications that can render file streams may set the addIns property for its 'FileHandler' functionality.
This will let services like Microsoft 365 call the application in the context of a document the user is working on.
To construct, see NOTES section for ADDIN properties and create a hash table.

```yaml
Type: Microsoft.Azure.PowerShell.Cmdlets.Resources.MSGraph.Models.ApiV10.IMicrosoftGraphAddIn[]
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AlternativeName
Used to retrieve service principals by subscription, identify resource group and full resource ids for managed identities.
Supports $filter (eq, NOT, ge, le, startsWith).

```yaml
Type: System.String[]
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AppDescription
The description exposed by the associated application.

```yaml
Type: System.String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ApplicationId
The unique identifier for the associated application (its appId property).

```yaml
Type: System.Guid
Parameter Sets: SpApplicationIdWithDisplayNameParameterSet
Aliases: AppId

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AppOwnerOrganizationId
Contains the tenant id where the application is registered.
This is applicable only to service principals backed by applications.Supports $filter (eq, ne, NOT, ge, le).

```yaml
Type: System.String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AppRole
The roles exposed by the application which this service principal represents.
For more information see the appRoles property definition on the application entity.
Not nullable.
To construct, see NOTES section for APPROLE properties and create a hash table.

```yaml
Type: Microsoft.Azure.PowerShell.Cmdlets.Resources.MSGraph.Models.ApiV10.IMicrosoftGraphAppRole[]
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AppRoleAssignedTo
App role assignments for this app or service, granted to users, groups, and other service principals.Supports $expand.
To construct, see NOTES section for APPROLEASSIGNEDTO properties and create a hash table.

```yaml
Type: Microsoft.Azure.PowerShell.Cmdlets.Resources.MSGraph.Models.ApiV10.IMicrosoftGraphAppRoleAssignment[]
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AppRoleAssignment
App role assignment for another app or service, granted to this service principal.
Supports $expand.
To construct, see NOTES section for APPROLEASSIGNMENT properties and create a hash table.

```yaml
Type: Microsoft.Azure.PowerShell.Cmdlets.Resources.MSGraph.Models.ApiV10.IMicrosoftGraphAppRoleAssignment[]
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AppRoleAssignmentRequired
Specifies whether users or other service principals need to be granted an app role assignment for this service principal before users can sign in or apps can get tokens.
The default value is false.
Not nullable.
Supports $filter (eq, ne, NOT).

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ClaimsMappingPolicy
The claimsMappingPolicies assigned to this service principal.
Supports $expand.
To construct, see NOTES section for CLAIMSMAPPINGPOLICY properties and create a hash table.

```yaml
Type: Microsoft.Azure.PowerShell.Cmdlets.Resources.MSGraph.Models.ApiV10.IMicrosoftGraphClaimsMappingPolicy[]
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DefaultProfile
The credentials, account, tenant, and subscription used for communication with Azure.

```yaml
Type: System.Management.Automation.PSObject
Parameter Sets: (All)
Aliases: AzContext, AzureRmContext, AzureCredential

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DelegatedPermissionClassification
The permission classifications for delegated permissions exposed by the app that this service principal represents.
Supports $expand.
To construct, see NOTES section for DELEGATEDPERMISSIONCLASSIFICATION properties and create a hash table.

```yaml
Type: Microsoft.Azure.PowerShell.Cmdlets.Resources.MSGraph.Models.ApiV10.IMicrosoftGraphDelegatedPermissionClassification[]
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DeletedDateTime
.

```yaml
Type: System.DateTime
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Description
Free text field to provide an internal end-user facing description of the service principal.
End-user portals such MyApps will display the application description in this field.
The maximum allowed size is 1024 characters.
Supports $filter (eq, ne, NOT, ge, le, startsWith) and $search.

```yaml
Type: System.String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DisabledByMicrosoftStatus
Specifies whether Microsoft has disabled the registered application.
Possible values are: null (default value), NotDisabled, and DisabledDueToViolationOfServicesAgreement (reasons may include suspicious, abusive, or malicious activity, or a violation of the Microsoft Services Agreement).
Supports $filter (eq, ne, NOT).

```yaml
Type: System.String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DisplayName
The display name for the service principal.
Supports $filter (eq, ne, NOT, ge, le, in, startsWith), $search, and $orderBy.

```yaml
Type: System.String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Endpoint
Endpoints available for discovery.
Services like Sharepoint populate this property with a tenant specific SharePoint endpoints that other applications can discover and use in their experiences.
To construct, see NOTES section for ENDPOINT properties and create a hash table.

```yaml
Type: Microsoft.Azure.PowerShell.Cmdlets.Resources.MSGraph.Models.ApiV10.IMicrosoftGraphEndpoint[]
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Homepage
Home page or landing page of the application.

```yaml
Type: System.String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -HomeRealmDiscoveryPolicy
The homeRealmDiscoveryPolicies assigned to this service principal.
Supports $expand.
To construct, see NOTES section for HOMEREALMDISCOVERYPOLICY properties and create a hash table.

```yaml
Type: Microsoft.Azure.PowerShell.Cmdlets.Resources.MSGraph.Models.ApiV10.IMicrosoftGraphHomeRealmDiscoveryPolicy[]
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -IdentifierUri
The URIs that identify the application within its Azure AD tenant, or within a verified custom domain if the application is multi-tenant.
For more information, see Application Objects and Service Principal Objects.
The any operator is required for filter expressions on multi-valued properties.
Not nullable.
Supports $filter (eq, ne, ge, le, startsWith).

```yaml
Type: System.String[]
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Info
informationalUrl
To construct, see NOTES section for INFO properties and create a hash table.

```yaml
Type: Microsoft.Azure.PowerShell.Cmdlets.Resources.MSGraph.Models.ApiV10.IMicrosoftGraphInformationalUrl
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -InputObject
service principal object
To construct, see NOTES section for INPUTOBJECT properties and create a hash table.

```yaml
Type: Microsoft.Azure.PowerShell.Cmdlets.Resources.MSGraph.Models.ApiV10.IMicrosoftGraphServicePrincipal
Parameter Sets: InputObjectWithDisplayNameParameterSet
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -KeyCredential
The collection of key credentials associated with the application.
Not nullable.
Supports $filter (eq, NOT, ge, le).
To construct, see NOTES section for KEYCREDENTIALS properties and create a hash table.
To construct, see NOTES section for KEYCREDENTIAL properties and create a hash table.

```yaml
Type: Microsoft.Azure.PowerShell.Cmdlets.Resources.MSGraph.Models.ApiV10.IMicrosoftGraphKeyCredential[]
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -LoginUrl
Specifies the URL where the service provider redirects the user to Azure AD to authenticate.
Azure AD uses the URL to launch the application from Microsoft 365 or the Azure AD My Apps.
When blank, Azure AD performs IdP-initiated sign-on for applications configured with SAML-based single sign-on.
The user launches the application from Microsoft 365, the Azure AD My Apps, or the Azure AD SSO URL.

```yaml
Type: System.String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -LogoutUrl
Specifies the URL that will be used by Microsoft's authorization service to logout an user using OpenId Connect front-channel, back-channel or SAML logout protocols.

```yaml
Type: System.String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Note
Free text field to capture information about the service principal, typically used for operational purposes.
Maximum allowed size is 1024 characters.

```yaml
Type: System.String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -NotificationEmailAddress
Specifies the list of email addresses where Azure AD sends a notification when the active certificate is near the expiration date.
This is only for the certificates used to sign the SAML token issued for Azure AD Gallery applications.

```yaml
Type: System.String[]
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Oauth2PermissionScope
The delegated permissions exposed by the application.
For more information see the oauth2PermissionScopes property on the application entity's api property.
Not nullable.
To construct, see NOTES section for OAUTH2PERMISSIONSCOPE properties and create a hash table.

```yaml
Type: Microsoft.Azure.PowerShell.Cmdlets.Resources.MSGraph.Models.ApiV10.IMicrosoftGraphPermissionScope[]
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ObjectId
key: id of servicePrincipal

```yaml
Type: System.String
Parameter Sets: SpObjectIdWithDisplayNameParameterSet
Aliases: ServicePrincipalId, Id, ServicePrincipalObjectId

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PassThru
Returns true when the command succeeds

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PasswordCredential
The collection of password credentials associated with the application.
Not nullable.
To construct, see NOTES section for PASSWORDCREDENTIALS properties and create a hash table.
To construct, see NOTES section for PASSWORDCREDENTIAL properties and create a hash table.

```yaml
Type: Microsoft.Azure.PowerShell.Cmdlets.Resources.MSGraph.Models.ApiV10.IMicrosoftGraphPasswordCredential[]
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PreferredSingleSignOnMode
Specifies the single sign-on mode configured for this application.
Azure AD uses the preferred single sign-on mode to launch the application from Microsoft 365 or the Azure AD My Apps.
The supported values are password, saml, notSupported, and oidc.

```yaml
Type: System.String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PreferredTokenSigningKeyThumbprint
Reserved for internal use only.
Do not write or otherwise rely on this property.
May be removed in future versions.

```yaml
Type: System.String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ReplyUrl
The URLs that user tokens are sent to for sign in with the associated application, or the redirect URIs that OAuth 2.0 authorization codes and access tokens are sent to for the associated application.
Not nullable.

```yaml
Type: System.String[]
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -SamlSingleSignOnSetting
samlSingleSignOnSettings
To construct, see NOTES section for SAMLSINGLESIGNONSETTING properties and create a hash table.

```yaml
Type: Microsoft.Azure.PowerShell.Cmdlets.Resources.MSGraph.Models.ApiV10.IMicrosoftGraphSamlSingleSignOnSettings
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ServicePrincipalName
Contains the list of identifiersUris, copied over from the associated application.
Additional values can be added to hybrid applications.
These values can be used to identify the permissions exposed by this app within Azure AD.
For example,Client apps can specify a resource URI which is based on the values of this property to acquire an access token, which is the URI returned in the 'aud' claim.The any operator is required for filter expressions on multi-valued properties.
Not nullable.
Supports $filter (eq, NOT, ge, le, startsWith).

```yaml
Type: System.String
Parameter Sets: SPNWithDisplayNameParameterSet
Aliases: SPN

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ServicePrincipalType
Identifies if the service principal represents an application or a managed identity.
This is set by Azure AD internally.
For a service principal that represents an application this is set as Application.
For a service principal that represent a managed identity this is set as ManagedIdentity.

```yaml
Type: System.String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Tag
Custom strings that can be used to categorize and identify the service principal.
Not nullable.
Supports $filter (eq, NOT, ge, le, startsWith).

```yaml
Type: System.String[]
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -TokenEncryptionKeyId
Specifies the keyId of a public key from the keyCredentials collection.
When configured, Azure AD issues tokens for this application encrypted using the key specified by this property.
The application code that receives the encrypted token must use the matching private key to decrypt the token before it can be used for the signed-in user.

```yaml
Type: System.String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -TokenIssuancePolicy
The tokenIssuancePolicies assigned to this service principal.
Supports $expand.
To construct, see NOTES section for TOKENISSUANCEPOLICY properties and create a hash table.

```yaml
Type: Microsoft.Azure.PowerShell.Cmdlets.Resources.MSGraph.Models.ApiV10.IMicrosoftGraphTokenIssuancePolicy[]
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -TokenLifetimePolicy
The tokenLifetimePolicies assigned to this service principal.
Supports $expand.
To construct, see NOTES section for TOKENLIFETIMEPOLICY properties and create a hash table.

```yaml
Type: Microsoft.Azure.PowerShell.Cmdlets.Resources.MSGraph.Models.ApiV10.IMicrosoftGraphTokenLifetimePolicy[]
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -TransitiveMemberOf
.
To construct, see NOTES section for TRANSITIVEMEMBEROF properties and create a hash table.

```yaml
Type: Microsoft.Azure.PowerShell.Cmdlets.Resources.MSGraph.Models.ApiV10.IMicrosoftGraphDirectoryObject[]
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Confirm
Prompts you for confirmation before running the cmdlet.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: (All)
Aliases: cf

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -WhatIf
Shows what would happen if the cmdlet runs.
The cmdlet is not run.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: (All)
Aliases: wi

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### Microsoft.Azure.PowerShell.Cmdlets.Resources.MSGraph.Models.ApiV10.IMicrosoftGraphServicePrincipal

## OUTPUTS

### System.Boolean

## NOTES

ALIASES

Set-AzADServicePrincipal

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


`ADDIN <IMicrosoftGraphAddIn[]>`: Defines custom behavior that a consuming service can use to call an app in specific contexts. For example, applications that can render file streams may set the addIns property for its 'FileHandler' functionality. This will let services like Microsoft 365 call the application in the context of a document the user is working on.
  - `[Id <String>]`: 
  - `[Property <IMicrosoftGraphKeyValue[]>]`: 
    - `[Key <String>]`: Key.
    - `[Value <String>]`: Value.
  - `[Type <String>]`: 

`APPROLE <IMicrosoftGraphAppRole[]>`: The roles exposed by the application which this service principal represents. For more information see the appRoles property definition on the application entity. Not nullable.
  - `[AllowedMemberType <String[]>]`: Specifies whether this app role can be assigned to users and groups (by setting to ['User']), to other application's (by setting to ['Application'], or both (by setting to ['User', 'Application']). App roles supporting assignment to other applications' service principals are also known as application permissions. The 'Application' value is only supported for app roles defined on application entities.
  - `[Description <String>]`: The description for the app role. This is displayed when the app role is being assigned and, if the app role functions as an application permission, during  consent experiences.
  - `[DisplayName <String>]`: Display name for the permission that appears in the app role assignment and consent experiences.
  - `[Id <String>]`: Unique role identifier inside the appRoles collection. When creating a new app role, a new Guid identifier must be provided.
  - `[IsEnabled <Boolean?>]`: When creating or updating an app role, this must be set to true (which is the default). To delete a role, this must first be set to false.  At that point, in a subsequent call, this role may be removed.
  - `[Value <String>]`: Specifies the value to include in the roles claim in ID tokens and access tokens authenticating an assigned user or service principal. Must not exceed 120 characters in length. Allowed characters are : ! # $ % & ' ( ) * + , - . / : ;  =  ? @ [ ] ^ + _  {  } ~, as well as characters in the ranges 0-9, A-Z and a-z. Any other character, including the space character, are not allowed. May not begin with ..

`APPROLEASSIGNEDTO <IMicrosoftGraphAppRoleAssignment[]>`: App role assignments for this app or service, granted to users, groups, and other service principals.Supports $expand.
  - `[DeletedDateTime <DateTime?>]`: 
  - `[DisplayName <String>]`: The name displayed in directory
  - `[AppRoleId <String>]`: The identifier (id) for the app role which is assigned to the principal. This app role must be exposed in the appRoles property on the resource application's service principal (resourceId). If the resource application has not declared any app roles, a default app role ID of 00000000-0000-0000-0000-000000000000 can be specified to signal that the principal is assigned to the resource app without any specific app roles. Required on create.
  - `[PrincipalId <String>]`: The unique identifier (id) for the user, group or service principal being granted the app role. Required on create.
  - `[ResourceDisplayName <String>]`: The display name of the resource app's service principal to which the assignment is made.
  - `[ResourceId <String>]`: The unique identifier (id) for the resource service principal for which the assignment is made. Required on create. Supports $filter (eq only).

`APPROLEASSIGNMENT <IMicrosoftGraphAppRoleAssignment[]>`: App role assignment for another app or service, granted to this service principal. Supports $expand.
  - `[DeletedDateTime <DateTime?>]`: 
  - `[DisplayName <String>]`: The name displayed in directory
  - `[AppRoleId <String>]`: The identifier (id) for the app role which is assigned to the principal. This app role must be exposed in the appRoles property on the resource application's service principal (resourceId). If the resource application has not declared any app roles, a default app role ID of 00000000-0000-0000-0000-000000000000 can be specified to signal that the principal is assigned to the resource app without any specific app roles. Required on create.
  - `[PrincipalId <String>]`: The unique identifier (id) for the user, group or service principal being granted the app role. Required on create.
  - `[ResourceDisplayName <String>]`: The display name of the resource app's service principal to which the assignment is made.
  - `[ResourceId <String>]`: The unique identifier (id) for the resource service principal for which the assignment is made. Required on create. Supports $filter (eq only).

`CLAIMSMAPPINGPOLICY <IMicrosoftGraphClaimsMappingPolicy[]>`: The claimsMappingPolicies assigned to this service principal. Supports $expand.
  - `[AppliesTo <IMicrosoftGraphDirectoryObject[]>]`: 
    - `[DeletedDateTime <DateTime?>]`: 
    - `[DisplayName <String>]`: The name displayed in directory
  - `[Definition <String[]>]`: A string collection containing a JSON string that defines the rules and settings for a policy. The syntax for the definition differs for each derived policy type. Required.
  - `[IsOrganizationDefault <Boolean?>]`: If set to true, activates this policy. There can be many policies for the same policy type, but only one can be activated as the organization default. Optional, default value is false.
  - `[Description <String>]`: Description for this policy.
  - `[DeletedDateTime <DateTime?>]`: 
  - `[DisplayName <String>]`: The name displayed in directory

`DELEGATEDPERMISSIONCLASSIFICATION <IMicrosoftGraphDelegatedPermissionClassification[]>`: The permission classifications for delegated permissions exposed by the app that this service principal represents. Supports $expand.
  - `[Classification <String>]`: permissionClassificationType
  - `[PermissionId <String>]`: The unique identifier (id) for the delegated permission listed in the publishedPermissionScopes collection of the servicePrincipal. Required on create. Does not support $filter.
  - `[PermissionName <String>]`: The claim value (value) for the delegated permission listed in the publishedPermissionScopes collection of the servicePrincipal. Does not support $filter.

`ENDPOINT <IMicrosoftGraphEndpoint[]>`: Endpoints available for discovery. Services like Sharepoint populate this property with a tenant specific SharePoint endpoints that other applications can discover and use in their experiences.
  - `[DeletedDateTime <DateTime?>]`: 
  - `[DisplayName <String>]`: The name displayed in directory

`HOMEREALMDISCOVERYPOLICY <IMicrosoftGraphHomeRealmDiscoveryPolicy[]>`: The homeRealmDiscoveryPolicies assigned to this service principal. Supports $expand.
  - `[AppliesTo <IMicrosoftGraphDirectoryObject[]>]`: 
    - `[DeletedDateTime <DateTime?>]`: 
    - `[DisplayName <String>]`: The name displayed in directory
  - `[Definition <String[]>]`: A string collection containing a JSON string that defines the rules and settings for a policy. The syntax for the definition differs for each derived policy type. Required.
  - `[IsOrganizationDefault <Boolean?>]`: If set to true, activates this policy. There can be many policies for the same policy type, but only one can be activated as the organization default. Optional, default value is false.
  - `[Description <String>]`: Description for this policy.
  - `[DeletedDateTime <DateTime?>]`: 
  - `[DisplayName <String>]`: The name displayed in directory

`INFO <IMicrosoftGraphInformationalUrl>`: informationalUrl
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[MarketingUrl <String>]`: Link to the application's marketing page. For example, https://www.contoso.com/app/marketing
  - `[PrivacyStatementUrl <String>]`: Link to the application's privacy statement. For example, https://www.contoso.com/app/privacy
  - `[SupportUrl <String>]`: Link to the application's support page. For example, https://www.contoso.com/app/support
  - `[TermsOfServiceUrl <String>]`: Link to the application's terms of service statement. For example, https://www.contoso.com/app/termsofservice

`INPUTOBJECT <IMicrosoftGraphServicePrincipal>`: service principal object
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[DeletedDateTime <DateTime?>]`: 
  - `[DisplayName <String>]`: The name displayed in directory
  - `[AccountEnabled <Boolean?>]`: true if the service principal account is enabled; otherwise, false. Supports $filter (eq, ne, NOT, in).
  - `[AddIn <IMicrosoftGraphAddIn[]>]`: Defines custom behavior that a consuming service can use to call an app in specific contexts. For example, applications that can render file streams may set the addIns property for its 'FileHandler' functionality. This will let services like Microsoft 365 call the application in the context of a document the user is working on.
    - `[Id <String>]`: 
    - `[Property <IMicrosoftGraphKeyValue[]>]`: 
      - `[Key <String>]`: Key.
      - `[Value <String>]`: Value.
    - `[Type <String>]`: 
  - `[AlternativeName <String[]>]`: Used to retrieve service principals by subscription, identify resource group and full resource ids for managed identities. Supports $filter (eq, NOT, ge, le, startsWith).
  - `[AppDescription <String>]`: The description exposed by the associated application.
  - `[AppDisplayName <String>]`: The display name exposed by the associated application.
  - `[AppId <String>]`: The unique identifier for the associated application (its appId property).
  - `[AppOwnerOrganizationId <String>]`: Contains the tenant id where the application is registered. This is applicable only to service principals backed by applications.Supports $filter (eq, ne, NOT, ge, le).
  - `[AppRole <IMicrosoftGraphAppRole[]>]`: The roles exposed by the application which this service principal represents. For more information see the appRoles property definition on the application entity. Not nullable.
    - `[AllowedMemberType <String[]>]`: Specifies whether this app role can be assigned to users and groups (by setting to ['User']), to other application's (by setting to ['Application'], or both (by setting to ['User', 'Application']). App roles supporting assignment to other applications' service principals are also known as application permissions. The 'Application' value is only supported for app roles defined on application entities.
    - `[Description <String>]`: The description for the app role. This is displayed when the app role is being assigned and, if the app role functions as an application permission, during  consent experiences.
    - `[DisplayName <String>]`: Display name for the permission that appears in the app role assignment and consent experiences.
    - `[Id <String>]`: Unique role identifier inside the appRoles collection. When creating a new app role, a new Guid identifier must be provided.
    - `[IsEnabled <Boolean?>]`: When creating or updating an app role, this must be set to true (which is the default). To delete a role, this must first be set to false.  At that point, in a subsequent call, this role may be removed.
    - `[Value <String>]`: Specifies the value to include in the roles claim in ID tokens and access tokens authenticating an assigned user or service principal. Must not exceed 120 characters in length. Allowed characters are : ! # $ % & ' ( ) * + , - . / : ;  =  ? @ [ ] ^ + _  {  } ~, as well as characters in the ranges 0-9, A-Z and a-z. Any other character, including the space character, are not allowed. May not begin with ..
  - `[AppRoleAssignedTo <IMicrosoftGraphAppRoleAssignment[]>]`: App role assignments for this app or service, granted to users, groups, and other service principals.Supports $expand.
    - `[DeletedDateTime <DateTime?>]`: 
    - `[DisplayName <String>]`: The name displayed in directory
    - `[AppRoleId <String>]`: The identifier (id) for the app role which is assigned to the principal. This app role must be exposed in the appRoles property on the resource application's service principal (resourceId). If the resource application has not declared any app roles, a default app role ID of 00000000-0000-0000-0000-000000000000 can be specified to signal that the principal is assigned to the resource app without any specific app roles. Required on create.
    - `[PrincipalId <String>]`: The unique identifier (id) for the user, group or service principal being granted the app role. Required on create.
    - `[ResourceDisplayName <String>]`: The display name of the resource app's service principal to which the assignment is made.
    - `[ResourceId <String>]`: The unique identifier (id) for the resource service principal for which the assignment is made. Required on create. Supports $filter (eq only).
  - `[AppRoleAssignment <IMicrosoftGraphAppRoleAssignment[]>]`: App role assignment for another app or service, granted to this service principal. Supports $expand.
  - `[AppRoleAssignmentRequired <Boolean?>]`: Specifies whether users or other service principals need to be granted an app role assignment for this service principal before users can sign in or apps can get tokens. The default value is false. Not nullable. Supports $filter (eq, ne, NOT).
  - `[ClaimsMappingPolicy <IMicrosoftGraphClaimsMappingPolicy[]>]`: The claimsMappingPolicies assigned to this service principal. Supports $expand.
    - `[AppliesTo <IMicrosoftGraphDirectoryObject[]>]`: 
      - `[DeletedDateTime <DateTime?>]`: 
      - `[DisplayName <String>]`: The name displayed in directory
    - `[Definition <String[]>]`: A string collection containing a JSON string that defines the rules and settings for a policy. The syntax for the definition differs for each derived policy type. Required.
    - `[IsOrganizationDefault <Boolean?>]`: If set to true, activates this policy. There can be many policies for the same policy type, but only one can be activated as the organization default. Optional, default value is false.
    - `[Description <String>]`: Description for this policy.
    - `[DeletedDateTime <DateTime?>]`: 
    - `[DisplayName <String>]`: The name displayed in directory
  - `[DelegatedPermissionClassification <IMicrosoftGraphDelegatedPermissionClassification[]>]`: The permission classifications for delegated permissions exposed by the app that this service principal represents. Supports $expand.
    - `[Classification <String>]`: permissionClassificationType
    - `[PermissionId <String>]`: The unique identifier (id) for the delegated permission listed in the publishedPermissionScopes collection of the servicePrincipal. Required on create. Does not support $filter.
    - `[PermissionName <String>]`: The claim value (value) for the delegated permission listed in the publishedPermissionScopes collection of the servicePrincipal. Does not support $filter.
  - `[Description <String>]`: Free text field to provide an internal end-user facing description of the service principal. End-user portals such MyApps will display the application description in this field. The maximum allowed size is 1024 characters. Supports $filter (eq, ne, NOT, ge, le, startsWith) and $search.
  - `[DisabledByMicrosoftStatus <String>]`: Specifies whether Microsoft has disabled the registered application. Possible values are: null (default value), NotDisabled, and DisabledDueToViolationOfServicesAgreement (reasons may include suspicious, abusive, or malicious activity, or a violation of the Microsoft Services Agreement).  Supports $filter (eq, ne, NOT).
  - `[Endpoint <IMicrosoftGraphEndpoint[]>]`: Endpoints available for discovery. Services like Sharepoint populate this property with a tenant specific SharePoint endpoints that other applications can discover and use in their experiences.
    - `[DeletedDateTime <DateTime?>]`: 
    - `[DisplayName <String>]`: The name displayed in directory
  - `[FederatedIdentityCredentials <IMicrosoftGraphFederatedIdentityCredential[]>]`: 
    - `[Audience <String[]>]`: Lists the audiences that can appear in the external token. This field is mandatory, and defaults to 'api://AzureADTokenExchange'. It says what Microsoft identity platform should accept in the aud claim in the incoming token. This value represents Azure AD in your external identity provider and has no fixed value across identity providers - you may need to create a new application registration in your identity provider to serve as the audience of this token. Required.
    - `[Description <String>]`: The un-validated, user-provided description of the federated identity credential. Optional.
    - `[Issuer <String>]`: The URL of the external identity provider and must match the issuer claim of the external token being exchanged. The combination of the values of issuer and subject must be unique on the app. Required.
    - `[Name <String>]`: is the unique identifier for the federated identity credential, which has a character limit of 120 characters and must be URL friendly. It is immutable once created. Required. Not nullable. Supports $filter (eq).
    - `[Subject <String>]`: Required. The identifier of the external software workload within the external identity provider. Like the audience value, it has no fixed format, as each identity provider uses their own - sometimes a GUID, sometimes a colon delimited identifier, sometimes arbitrary strings. The value here must match the sub claim within the token presented to Azure AD. The combination of issuer and subject must be unique on the app. Supports $filter (eq).
  - `[HomeRealmDiscoveryPolicy <IMicrosoftGraphHomeRealmDiscoveryPolicy[]>]`: The homeRealmDiscoveryPolicies assigned to this service principal. Supports $expand.
    - `[AppliesTo <IMicrosoftGraphDirectoryObject[]>]`: 
    - `[Definition <String[]>]`: A string collection containing a JSON string that defines the rules and settings for a policy. The syntax for the definition differs for each derived policy type. Required.
    - `[IsOrganizationDefault <Boolean?>]`: If set to true, activates this policy. There can be many policies for the same policy type, but only one can be activated as the organization default. Optional, default value is false.
    - `[Description <String>]`: Description for this policy.
    - `[DeletedDateTime <DateTime?>]`: 
    - `[DisplayName <String>]`: The name displayed in directory
  - `[Homepage <String>]`: Home page or landing page of the application.
  - `[Info <IMicrosoftGraphInformationalUrl>]`: informationalUrl
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[MarketingUrl <String>]`: Link to the application's marketing page. For example, https://www.contoso.com/app/marketing
    - `[PrivacyStatementUrl <String>]`: Link to the application's privacy statement. For example, https://www.contoso.com/app/privacy
    - `[SupportUrl <String>]`: Link to the application's support page. For example, https://www.contoso.com/app/support
    - `[TermsOfServiceUrl <String>]`: Link to the application's terms of service statement. For example, https://www.contoso.com/app/termsofservice
  - `[KeyCredentials <IMicrosoftGraphKeyCredential[]>]`: The collection of key credentials associated with the service principal. Not nullable. Supports $filter (eq, NOT, ge, le).
    - `[CustomKeyIdentifier <Byte[]>]`: Custom key identifier
    - `[DisplayName <String>]`: Friendly name for the key. Optional.
    - `[EndDateTime <DateTime?>]`: The date and time at which the credential expires.The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z
    - `[Key <Byte[]>]`: Value for the key credential. Should be a base 64 encoded value.
    - `[KeyId <String>]`: The unique identifier (GUID) for the key.
    - `[StartDateTime <DateTime?>]`: The date and time at which the credential becomes valid.The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z
    - `[Type <String>]`: The type of key credential; for example, 'Symmetric'.
    - `[Usage <String>]`: A string that describes the purpose for which the key can be used; for example, 'Verify'.
  - `[LoginUrl <String>]`: Specifies the URL where the service provider redirects the user to Azure AD to authenticate. Azure AD uses the URL to launch the application from Microsoft 365 or the Azure AD My Apps. When blank, Azure AD performs IdP-initiated sign-on for applications configured with SAML-based single sign-on. The user launches the application from Microsoft 365, the Azure AD My Apps, or the Azure AD SSO URL.
  - `[LogoutUrl <String>]`: Specifies the URL that will be used by Microsoft's authorization service to logout an user using OpenId Connect front-channel, back-channel or SAML logout protocols.
  - `[Note <String>]`: Free text field to capture information about the service principal, typically used for operational purposes. Maximum allowed size is 1024 characters.
  - `[NotificationEmailAddress <String[]>]`: Specifies the list of email addresses where Azure AD sends a notification when the active certificate is near the expiration date. This is only for the certificates used to sign the SAML token issued for Azure AD Gallery applications.
  - `[Oauth2PermissionScope <IMicrosoftGraphPermissionScope[]>]`: The delegated permissions exposed by the application. For more information see the oauth2PermissionScopes property on the application entity's api property. Not nullable.
    - `[AdminConsentDescription <String>]`: A description of the delegated permissions, intended to be read by an administrator granting the permission on behalf of all users. This text appears in tenant-wide admin consent experiences.
    - `[AdminConsentDisplayName <String>]`: The permission's title, intended to be read by an administrator granting the permission on behalf of all users.
    - `[Id <String>]`: Unique delegated permission identifier inside the collection of delegated permissions defined for a resource application.
    - `[IsEnabled <Boolean?>]`: When creating or updating a permission, this property must be set to true (which is the default). To delete a permission, this property must first be set to false.  At that point, in a subsequent call, the permission may be removed.
    - `[Origin <String>]`: 
    - `[Type <String>]`: Specifies whether this delegated permission should be considered safe for non-admin users to consent to on behalf of themselves, or whether an administrator should be required for consent to the permissions. This will be the default behavior, but each customer can choose to customize the behavior in their organization (by allowing, restricting or limiting user consent to this delegated permission.)
    - `[UserConsentDescription <String>]`: A description of the delegated permissions, intended to be read by a user granting the permission on their own behalf. This text appears in consent experiences where the user is consenting only on behalf of themselves.
    - `[UserConsentDisplayName <String>]`: A title for the permission, intended to be read by a user granting the permission on their own behalf. This text appears in consent experiences where the user is consenting only on behalf of themselves.
    - `[Value <String>]`: Specifies the value to include in the scp (scope) claim in access tokens. Must not exceed 120 characters in length. Allowed characters are : ! # $ % & ' ( ) * + , - . / : ;  =  ? @ [ ] ^ + _  {  } ~, as well as characters in the ranges 0-9, A-Z and a-z. Any other character, including the space character, are not allowed. May not begin with ..
  - `[PasswordCredentials <IMicrosoftGraphPasswordCredential[]>]`: The collection of password credentials associated with the service principal. Not nullable.
    - `[CustomKeyIdentifier <Byte[]>]`: Do not use.
    - `[DisplayName <String>]`: Friendly name for the password. Optional.
    - `[EndDateTime <DateTime?>]`: The date and time at which the password expires represented using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z. Optional.
    - `[KeyId <String>]`: The unique identifier for the password.
    - `[StartDateTime <DateTime?>]`: The date and time at which the password becomes valid. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z. Optional.
  - `[PreferredSingleSignOnMode <String>]`: Specifies the single sign-on mode configured for this application. Azure AD uses the preferred single sign-on mode to launch the application from Microsoft 365 or the Azure AD My Apps. The supported values are password, saml, notSupported, and oidc.
  - `[PreferredTokenSigningKeyThumbprint <String>]`: Reserved for internal use only. Do not write or otherwise rely on this property. May be removed in future versions.
  - `[ReplyUrl <String[]>]`: The URLs that user tokens are sent to for sign in with the associated application, or the redirect URIs that OAuth 2.0 authorization codes and access tokens are sent to for the associated application. Not nullable.
  - `[SamlSingleSignOnSetting <IMicrosoftGraphSamlSingleSignOnSettings>]`: samlSingleSignOnSettings
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[RelayState <String>]`: The relative URI the service provider would redirect to after completion of the single sign-on flow.
  - `[ServicePrincipalName <String[]>]`: Contains the list of identifiersUris, copied over from the associated application. Additional values can be added to hybrid applications. These values can be used to identify the permissions exposed by this app within Azure AD. For example,Client apps can specify a resource URI which is based on the values of this property to acquire an access token, which is the URI returned in the 'aud' claim.The any operator is required for filter expressions on multi-valued properties. Not nullable.  Supports $filter (eq, NOT, ge, le, startsWith).
  - `[ServicePrincipalType <String>]`: Identifies if the service principal represents an application or a managed identity. This is set by Azure AD internally. For a service principal that represents an application this is set as Application. For a service principal that represent a managed identity this is set as ManagedIdentity.
  - `[Tag <String[]>]`: Custom strings that can be used to categorize and identify the service principal. Not nullable. Supports $filter (eq, NOT, ge, le, startsWith).
  - `[TokenEncryptionKeyId <String>]`: Specifies the keyId of a public key from the keyCredentials collection. When configured, Azure AD issues tokens for this application encrypted using the key specified by this property. The application code that receives the encrypted token must use the matching private key to decrypt the token before it can be used for the signed-in user.
  - `[TokenIssuancePolicy <IMicrosoftGraphTokenIssuancePolicy[]>]`: The tokenIssuancePolicies assigned to this service principal. Supports $expand.
    - `[AppliesTo <IMicrosoftGraphDirectoryObject[]>]`: 
    - `[Definition <String[]>]`: A string collection containing a JSON string that defines the rules and settings for a policy. The syntax for the definition differs for each derived policy type. Required.
    - `[IsOrganizationDefault <Boolean?>]`: If set to true, activates this policy. There can be many policies for the same policy type, but only one can be activated as the organization default. Optional, default value is false.
    - `[Description <String>]`: Description for this policy.
    - `[DeletedDateTime <DateTime?>]`: 
    - `[DisplayName <String>]`: The name displayed in directory
  - `[TokenLifetimePolicy <IMicrosoftGraphTokenLifetimePolicy[]>]`: The tokenLifetimePolicies assigned to this service principal. Supports $expand.
    - `[AppliesTo <IMicrosoftGraphDirectoryObject[]>]`: 
    - `[Definition <String[]>]`: A string collection containing a JSON string that defines the rules and settings for a policy. The syntax for the definition differs for each derived policy type. Required.
    - `[IsOrganizationDefault <Boolean?>]`: If set to true, activates this policy. There can be many policies for the same policy type, but only one can be activated as the organization default. Optional, default value is false.
    - `[Description <String>]`: Description for this policy.
    - `[DeletedDateTime <DateTime?>]`: 
    - `[DisplayName <String>]`: The name displayed in directory
  - `[TransitiveMemberOf <IMicrosoftGraphDirectoryObject[]>]`: 

`KEYCREDENTIAL <IMicrosoftGraphKeyCredential[]>`: The collection of key credentials associated with the application. Not nullable. Supports $filter (eq, NOT, ge, le). To construct, see NOTES section for KEYCREDENTIALS properties and create a hash table.
  - `[CustomKeyIdentifier <Byte[]>]`: Custom key identifier
  - `[DisplayName <String>]`: Friendly name for the key. Optional.
  - `[EndDateTime <DateTime?>]`: The date and time at which the credential expires.The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z
  - `[Key <Byte[]>]`: Value for the key credential. Should be a base 64 encoded value.
  - `[KeyId <String>]`: The unique identifier (GUID) for the key.
  - `[StartDateTime <DateTime?>]`: The date and time at which the credential becomes valid.The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z
  - `[Type <String>]`: The type of key credential; for example, 'Symmetric'.
  - `[Usage <String>]`: A string that describes the purpose for which the key can be used; for example, 'Verify'.

`OAUTH2PERMISSIONSCOPE <IMicrosoftGraphPermissionScope[]>`: The delegated permissions exposed by the application. For more information see the oauth2PermissionScopes property on the application entity's api property. Not nullable.
  - `[AdminConsentDescription <String>]`: A description of the delegated permissions, intended to be read by an administrator granting the permission on behalf of all users. This text appears in tenant-wide admin consent experiences.
  - `[AdminConsentDisplayName <String>]`: The permission's title, intended to be read by an administrator granting the permission on behalf of all users.
  - `[Id <String>]`: Unique delegated permission identifier inside the collection of delegated permissions defined for a resource application.
  - `[IsEnabled <Boolean?>]`: When creating or updating a permission, this property must be set to true (which is the default). To delete a permission, this property must first be set to false.  At that point, in a subsequent call, the permission may be removed.
  - `[Origin <String>]`: 
  - `[Type <String>]`: Specifies whether this delegated permission should be considered safe for non-admin users to consent to on behalf of themselves, or whether an administrator should be required for consent to the permissions. This will be the default behavior, but each customer can choose to customize the behavior in their organization (by allowing, restricting or limiting user consent to this delegated permission.)
  - `[UserConsentDescription <String>]`: A description of the delegated permissions, intended to be read by a user granting the permission on their own behalf. This text appears in consent experiences where the user is consenting only on behalf of themselves.
  - `[UserConsentDisplayName <String>]`: A title for the permission, intended to be read by a user granting the permission on their own behalf. This text appears in consent experiences where the user is consenting only on behalf of themselves.
  - `[Value <String>]`: Specifies the value to include in the scp (scope) claim in access tokens. Must not exceed 120 characters in length. Allowed characters are : ! # $ % & ' ( ) * + , - . / : ;  =  ? @ [ ] ^ + _  {  } ~, as well as characters in the ranges 0-9, A-Z and a-z. Any other character, including the space character, are not allowed. May not begin with ..

`PASSWORDCREDENTIAL <IMicrosoftGraphPasswordCredential[]>`: The collection of password credentials associated with the application. Not nullable. To construct, see NOTES section for PASSWORDCREDENTIALS properties and create a hash table.
  - `[CustomKeyIdentifier <Byte[]>]`: Do not use.
  - `[DisplayName <String>]`: Friendly name for the password. Optional.
  - `[EndDateTime <DateTime?>]`: The date and time at which the password expires represented using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z. Optional.
  - `[KeyId <String>]`: The unique identifier for the password.
  - `[StartDateTime <DateTime?>]`: The date and time at which the password becomes valid. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z. Optional.

`SAMLSINGLESIGNONSETTING <IMicrosoftGraphSamlSingleSignOnSettings>`: samlSingleSignOnSettings
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[RelayState <String>]`: The relative URI the service provider would redirect to after completion of the single sign-on flow.

`TOKENISSUANCEPOLICY <IMicrosoftGraphTokenIssuancePolicy[]>`: The tokenIssuancePolicies assigned to this service principal. Supports $expand.
  - `[AppliesTo <IMicrosoftGraphDirectoryObject[]>]`: 
    - `[DeletedDateTime <DateTime?>]`: 
    - `[DisplayName <String>]`: The name displayed in directory
  - `[Definition <String[]>]`: A string collection containing a JSON string that defines the rules and settings for a policy. The syntax for the definition differs for each derived policy type. Required.
  - `[IsOrganizationDefault <Boolean?>]`: If set to true, activates this policy. There can be many policies for the same policy type, but only one can be activated as the organization default. Optional, default value is false.
  - `[Description <String>]`: Description for this policy.
  - `[DeletedDateTime <DateTime?>]`: 
  - `[DisplayName <String>]`: The name displayed in directory

`TOKENLIFETIMEPOLICY <IMicrosoftGraphTokenLifetimePolicy[]>`: The tokenLifetimePolicies assigned to this service principal. Supports $expand.
  - `[AppliesTo <IMicrosoftGraphDirectoryObject[]>]`: 
    - `[DeletedDateTime <DateTime?>]`: 
    - `[DisplayName <String>]`: The name displayed in directory
  - `[Definition <String[]>]`: A string collection containing a JSON string that defines the rules and settings for a policy. The syntax for the definition differs for each derived policy type. Required.
  - `[IsOrganizationDefault <Boolean?>]`: If set to true, activates this policy. There can be many policies for the same policy type, but only one can be activated as the organization default. Optional, default value is false.
  - `[Description <String>]`: Description for this policy.
  - `[DeletedDateTime <DateTime?>]`: 
  - `[DisplayName <String>]`: The name displayed in directory

`TRANSITIVEMEMBEROF <IMicrosoftGraphDirectoryObject[]>`: .
  - `[DeletedDateTime <DateTime?>]`: 
  - `[DisplayName <String>]`: The name displayed in directory

## RELATED LINKS


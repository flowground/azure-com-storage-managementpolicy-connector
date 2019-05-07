# ![LOGO](logo.png) StorageManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the StorageManagementClient API (version 2018-03-01-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/storage-managementpolicy/2018-03-01-preview/swagger.json<br/>
Generated at: 2019-05-07T17:39:16+03:00

## API Description

The Azure Storage Management API.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Deletes the data policy rules associated with the specified storage account.

*Tags:* `ManagementPolicies`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription. The name is case insensitive.
* `accountName` - _required_ - The name of the storage account within the specified resource group. Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.
* `api-version` - _required_ - The API version to use for this operation.
* `subscriptionId` - _required_ - The ID of the target subscription.
* `managementPolicyName` - _required_ - The name of the Storage Account Management Policy. It should always be 'default'
    Possible values: default.

### Gets the data policy rules associated with the specified storage account.

*Tags:* `ManagementPolicies`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription. The name is case insensitive.
* `accountName` - _required_ - The name of the storage account within the specified resource group. Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.
* `api-version` - _required_ - The API version to use for this operation.
* `subscriptionId` - _required_ - The ID of the target subscription.
* `managementPolicyName` - _required_ - The name of the Storage Account Management Policy. It should always be 'default'
    Possible values: default.

### Sets the data policy rules associated with the specified storage account.

*Tags:* `ManagementPolicies`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription. The name is case insensitive.
* `accountName` - _required_ - The name of the storage account within the specified resource group. Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.
* `api-version` - _required_ - The API version to use for this operation.
* `subscriptionId` - _required_ - The ID of the target subscription.
* `managementPolicyName` - _required_ - The name of the Storage Account Management Policy. It should always be 'default'
    Possible values: default.

## License

**flow**ground :- Telekom iPaaS / azure-com-storage-managementpolicy-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.

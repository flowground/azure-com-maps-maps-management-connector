# ![LOGO](logo.png) Azure Maps Resource Provider **flow**ground Connector

## Description

A generated **flow**ground connector for the Azure Maps Resource Provider API (version 2018-05-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/maps-maps-management/2018-05-01/swagger.json<br/>
Generated at: 2019-05-07T17:38:20+03:00

## API Description

Resource Provider

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### List operations available for the Maps Resource Provider

#### Input Parameters
* `api-version` - _required_ - Client Api Version.

### Get all Maps Accounts in a Subscription

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Moves Maps Accounts from one ResourceGroup (or Subscription) to another

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group that contains Maps Account to move.

### Get all Maps Accounts in a Resource Group

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the Azure Resource Group.

### Delete a Maps Account.

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the Azure Resource Group.
* `accountName` - _required_ - The name of the Maps Account.

### Get a Maps Account.

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the Azure Resource Group.
* `accountName` - _required_ - The name of the Maps Account.

### Updates a Maps Account. Only a subset of the parameters may be updated after creation, such as Sku and Tags.

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the Azure Resource Group.
* `accountName` - _required_ - The name of the Maps Account.

### Create or update a Maps Account. A Maps Account holds the keys which allow access to the Maps REST APIs.

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the Azure Resource Group.
* `accountName` - _required_ - The name of the Maps Account.

### Get the keys to use with the Maps APIs. A key is used to authenticate and authorize access to the Maps REST APIs. Only one key is needed at a time; two are given to provide seamless key regeneration.

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the Azure Resource Group.
* `accountName` - _required_ - The name of the Maps Account.

### Regenerate either the primary or secondary key for use with the Maps APIs. The old key will stop working immediately.

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the Azure Resource Group.
* `accountName` - _required_ - The name of the Maps Account.

## License

**flow**ground :- Telekom iPaaS / azure-com-maps-maps-management-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.

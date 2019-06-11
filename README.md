# ![LOGO](logo.png) AutomationManagement **flow**ground Connector

## Description

A generated **flow**ground connector for the AutomationManagement API (version 2018-01-15).

Generated from: https://api.apis.guru/v2/specs/azure.com/automation-dscNodeCounts/2018-01-15/swagger.json<br/>
Generated at: 2019-06-11T18:13:24+03:00

## API Description



## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Retrieve counts for Dsc Nodes.

*Tags:* `NodeCountInformation`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `automationAccountName` - _required_ - The name of the automation account.
* `countType` - _required_ - The type of counts to retrieve
    Possible values: status, nodeconfiguration.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client Api Version.

## License

**flow**ground :- Telekom iPaaS / azure-com-automation-dsc-node-counts-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.

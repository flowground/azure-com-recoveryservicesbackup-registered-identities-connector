# ![LOGO](logo.png) RecoveryServicesBackupClient **flow**ground Connector

## Description

A generated **flow**ground connector for the RecoveryServicesBackupClient API (version 2016-06-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/recoveryservicesbackup-registeredIdentities/2016-06-01/swagger.json<br/>
Generated at: 2019-06-11T18:14:12+03:00

## API Description



## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Unregisters the given container from your Recovery Services vault.

*Tags:* `ProtectionContainers`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group associated with the Recovery Services vault.
* `vaultName` - _required_ - The name of the Recovery Services vault.
* `api-version` - _required_ - Client API version.
* `identityName` - _required_ - Name of the protection container to unregister.

## License

**flow**ground :- Telekom iPaaS / azure-com-recoveryservicesbackup-registered-identities-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.

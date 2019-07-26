# ![LOGO](logo.png) groupalarm Billing API **flow**ground Connector

## Description

A generated **flow**ground connector for the groupalarm Billing API API (version 1.17.2).

Generated from: https://app.groupalarm.com/api/v1/billing<br/>
Generated at: 2019-07-26T13:59:33+03:00

## API Description

The billing service implements the billing business logic<br/>
<br/>
# Authentication<br/>
<br/>
<!-- ReDoc-Inject: <security-definitions> --><br/>

## Authorization

Supported authorization schemes:
- API Key
- API Key

## Actions

### UpdateBilling
> Updates a billing configuration for an organization<br/>

*Tags:* `billing`

### CreateBilling
> Creates a billing configuration for an organization<br/>

*Tags:* `billing`

### ActivateContract
> Revokes the odp-contract for the organization<br/>

*Tags:* `odp`

#### Input Parameters
* `organizationID` - _required_
* `token` - _required_

### CreateContract
> Creates an odp-contract for the passed organization<br/>

*Tags:* `odp`

### GetContract
> Get the current odp-contract of the organization<br/>

*Tags:* `odp`

#### Input Parameters
* `organizationID` - _required_

### DeleteContract
> Revokes the odp-contract for the organization<br/>

*Tags:* `odp`

#### Input Parameters
* `organizationID` - _required_

### GetBilling
> Get an organizations billing details<br/>

*Tags:* `billing`

#### Input Parameters
* `organizationID` - _required_

### ReactivateOrganization
> Reactivates a terminated organization payment option<br/>

*Tags:* `billing`

#### Input Parameters
* `organizationID` - _required_

### TerminateOrganization
> Terminates an organization payment option due the next billing<br/>

*Tags:* `billing`

#### Input Parameters
* `organizationID` - _required_

### GetBillingPreview
> Get a preview of the organization's current billing cycle<br/>

*Tags:* `billing`

#### Input Parameters
* `organizationID` - _required_

### GetProBonoRequest
> Check the status of an organization's pro-bono request<br/>

*Tags:* `pro-bono`

#### Input Parameters
* `organization_id` - _optional_

### AddProBonoRequest
> Create a new pro-bono request<br/>

*Tags:* `pro-bono`

## License

**flow**ground :- Telekom iPaaS / groupalarm-billing-api-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.

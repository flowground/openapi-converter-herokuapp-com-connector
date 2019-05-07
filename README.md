# ![LOGO](logo.png) Swagger2OpenAPI Converter **flow**ground Connector

## Description

A generated **flow**ground connector for the Swagger2OpenAPI Converter API (version 1.0.0).

Generated from: https://api.apis.guru/v2/specs/openapi-converter.herokuapp.com/1.0.0/swagger.json<br/>
Generated at: 2019-05-07T17:43:23+03:00

## API Description

Converter and validator for Swagger 2.0 to OpenAPI 3.0.x definitions

## Authorization

This API does not require authorization.

## Actions

### Return a redirect to a badge svg file depending on a source definition's validity

*Tags:* `validation`

#### Input Parameters
* `url` - _required_ - The URL to retrieve the OpenAPI 3.0.x definition from

### Convert a Swagger 2.0 definition to OpenAPI 3.0.x from a URL

*Tags:* `conversion`

#### Input Parameters
* `url` - _required_ - The URL to retrieve the OpenAPI 2.0 definition from

### Convert a Swagger 2.0 definition passed in the body to OpenAPI 3.0.x

*Tags:* `conversion`

### Get the status of the API

*Tags:* `metadata`

### Validate an OpenAPI 3.0.x definition

*Tags:* `validation`

#### Input Parameters
* `url` - _required_ - The URL to retrieve the OpenAPI 3.0.x definition from

### Validate an OpenAPI 3.0.x definition supplied in the body of the request

*Tags:* `validation`

## License

**flow**ground :- Telekom iPaaS / openapi-converter-herokuapp-com-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.

# ![LOGO](logo.png) SharedImageGalleryServiceClient **flow**ground Connector

## Description

A generated **flow**ground connector for the SharedImageGalleryServiceClient API (version 2018-06-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/compute-gallery/2018-06-01/swagger.json<br/>
Generated at: 2019-05-07T17:37:49+03:00

## API Description

Shared Image Gallery Service Client.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### List galleries under a subscription.

*Tags:* `Galleries`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client Api Version.

### List galleries under a resource group.

*Tags:* `Galleries`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group.
* `api-version` - _required_ - Client Api Version.

### Delete a Shared Image Gallery.

*Tags:* `Galleries`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group.
* `galleryName` - _required_ - The name of the Shared Image Gallery to be deleted.
* `api-version` - _required_ - Client Api Version.

### Retrieves information about a Shared Image Gallery.

*Tags:* `Galleries`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group.
* `galleryName` - _required_ - The name of the Shared Image Gallery.
* `api-version` - _required_ - Client Api Version.

### Create or update a Shared Image Gallery.

*Tags:* `Galleries`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group.
* `galleryName` - _required_ - The name of the Shared Image Gallery. The allowed characters are alphabets and numbers with dots and periods allowed in the middle. The maximum length is 80 characters.
* `api-version` - _required_ - Client Api Version.

### List gallery Image Definitions in a gallery.

*Tags:* `GalleryImages`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group.
* `galleryName` - _required_ - The name of the Shared Image Gallery from which Image Definitions are to be listed.
* `api-version` - _required_ - Client Api Version.

### Delete a gallery image.

*Tags:* `GalleryImages`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group.
* `galleryName` - _required_ - The name of the Shared Image Gallery in which the Image Definition is to be deleted.
* `galleryImageName` - _required_ - The name of the gallery Image Definition to be deleted.
* `api-version` - _required_ - Client Api Version.

### Retrieves information about a gallery Image Definition.

*Tags:* `GalleryImages`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group.
* `galleryName` - _required_ - The name of the Shared Image Gallery from which the Image Definitions are to be retrieved.
* `galleryImageName` - _required_ - The name of the gallery Image Definition to be retrieved.
* `api-version` - _required_ - Client Api Version.

### Create or update a gallery Image Definition.

*Tags:* `GalleryImages`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group.
* `galleryName` - _required_ - The name of the Shared Image Gallery in which the Image Definition is to be created.
* `galleryImageName` - _required_ - The name of the gallery Image Definition to be created or updated. The allowed characters are alphabets and numbers with dots, dashes, and periods allowed in the middle. The maximum length is 80 characters.
* `api-version` - _required_ - Client Api Version.

### List gallery Image Versions in a gallery Image Definition.

*Tags:* `GalleryImageVersions`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group.
* `galleryName` - _required_ - The name of the Shared Image Gallery in which the Image Definition resides.
* `galleryImageName` - _required_ - The name of the Shared Image Gallery Image Definition from which the Image Versions are to be listed.
* `api-version` - _required_ - Client Api Version.

### Delete a gallery Image Version.

*Tags:* `GalleryImageVersions`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group.
* `galleryName` - _required_ - The name of the Shared Image Gallery in which the Image Definition resides.
* `galleryImageName` - _required_ - The name of the gallery Image Definition in which the Image Version resides.
* `galleryImageVersionName` - _required_ - The name of the gallery Image Version to be deleted.
* `api-version` - _required_ - Client Api Version.

### Retrieves information about a gallery Image Version.

*Tags:* `GalleryImageVersions`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group.
* `galleryName` - _required_ - The name of the Shared Image Gallery in which the Image Definition resides.
* `galleryImageName` - _required_ - The name of the gallery Image Definition in which the Image Version resides.
* `galleryImageVersionName` - _required_ - The name of the gallery Image Version to be retrieved.
* `$expand` - _optional_ - The expand expression to apply on the operation.
    Possible values: ReplicationStatus.
* `api-version` - _required_ - Client Api Version.

### Create or update a gallery Image Version.

*Tags:* `GalleryImageVersions`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group.
* `galleryName` - _required_ - The name of the Shared Image Gallery in which the Image Definition resides.
* `galleryImageName` - _required_ - The name of the gallery Image Definition in which the Image Version is to be created.
* `galleryImageVersionName` - _required_ - The name of the gallery Image Version to be created. Needs to follow semantic version name pattern: The allowed characters are digit and period. Digits must be within the range of a 32-bit integer. Format: <MajorVersion>.<MinorVersion>.<Patch>
* `api-version` - _required_ - Client Api Version.

## License

**flow**ground :- Telekom iPaaS / azure-com-compute-gallery-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.

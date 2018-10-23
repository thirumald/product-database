
# Product Database

This web service provides a central point of management for product information. The current focus are the lifecycle data (EoL checks) for network products.

The following features are implemented:

* automatic check of the lifecycle state for a list of products against the local database (Product Check)
* synchronization with the Cisco EoX API (initial sync and periodic sync for specific Product ID's
* REST API to access the data
* data import using Excel (to add lifecycle data for other vendors)

## Setup & Installation

See the [Setup & Installation](docs/SETUP.md) for details on how to setup the webservice.

## License

See the [license](LICENSE.md) file for license rights and limitations (MIT).

## Cisco EoX APIs (Cisco Support APIs) within the Product Database

The Product Database is capable to synchronize the local database with the Cisco EoX API. More information about the API is available at [http://apiconsole.cisco.com](http://apiconsole.cisco.com) (Cisco Partner access only). The Getting Started guide is available at the [Cisco DevNet](https://developer.cisco.com/docs/support-apis/#getting-started-with-cisco-support-apis-for-sntc).
# iocage-plugin-asigra

Allows administrators to back up data from network-connected computers
and mobile devices. Leverages standard API calls from a single on-site
Asigra service (DS-Client) to reach into these devices and access the
data.

# Install

Follow the instructions in
[Installing a Plugin](https://www.ixsystems.com/documentation/freenas/11.2-U5/plugins.html#install "FreeNAS Userguide")

# Additional Information

See these Asigra documents for more information:

* [DS-Operator Management Guide](https://s3.amazonaws.com/asigra-documentation/Help/v14.1/DS-System%20Help/index.html):
  Using the **DS-Operator** interface to manage the plugin
  **DS-System** service. Click `Management` in the plugin options to open the
  DS-Operator interface.

* [DS-Client Installation Guide](https://s3.amazonaws.com/asigra-documentation/Guides/Cloud%20Backup/v14.1/Client_Software_Installation_Guide.pdf):
  How to install the **DS-Client** system. **DS-Client** aggregates
  backup content from endpoints and transmits it to the
  **DS-System** service.

* [DS-Client Management Guide](https://s3.amazonaws.com/asigra-documentation/Help/v14.1/DS-Client%20Help/index.html):
  Managing the **DS-Client** system after it has been successfully
  installed at one or more locations.

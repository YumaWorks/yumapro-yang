# yumapro-yang

## YumaPro SDK 20.10 Release Train

Contains the [YumaWorks](https://www.yumaworks.com)
YANG modules used in the 20.10 release train.
A tag for each new package release is added over time.

## YumaWorks YANG Modules

### netconfcentral

These YANG modules were originally developed for the yuma open-source project.
Several of the metadata modules are still used.  Many of the modules in this
directory have been replaced by standard versions of the module. They are
maintained for archival purposes only, and not intended to be used.

### yumaworks

These YANG modules are used in some or all YumaPro programs.
Some modules (e.g. netconfd-pro.yang) are used to define all the CLI
and configuration parameters.  Some modules are used internally by
netconfd-pro and not advertised to any client protocols.


## YumaWorks Software Packages

### yumapro-client

The [yumapro-client](https://www.yumaworks.com/support/download-yumapro-client/)
package provides free tools such as **yangcli-pro** for managing NETCONF and RESTCONF servers.


### yumapro-sdk-basic

The [yumapro-sdk-basic](https://www.yumaworks.com/support/download-yumapro-sdk-basic/)
package provides a NETCONF Server and SDK for developing YANG server instrumentation.


### yumabench

The [yumabench](https://www.yumaworks.com/support/download-yumabench/)
package provides a Qt5-based GUI for managing NETCONF servers.

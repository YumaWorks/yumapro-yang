# yumapro-yang

## YumaPro SDK YANG Modules

Contains the [YumaWorks](https://www.yumaworks.com)
YANG modules used in YumaPro SDK software.

## Latest YumaPro Release

YumaWorks maintains multiple release trains to increase stability.
Each October a new release train is started. (e.g. 22.10, 23.10).

Only the latest version (23.10T) is maintained here.
Use the modules included in the YumaPro package release
for other release trains.

## YumaWorks YANG Modules

### netconfcentral

These YANG modules were originally developed for the yuma open-source project.
Several of the metadata modules are still used.  Many of the modules in this
directory have been replaced by standard versions of the module. They are
maintained for archival purposes only, and not intended to be used.

Note that some yumaworks modules import some modules from this directory.


### yumaworks

These YANG modules are used in some or all YumaPro programs.
Some modules (e.g. netconfd-pro.yang) are used to define all the CLI
and configuration parameters.  Some modules are used internally by
netconfd-pro and not advertised to any client protocols.


## YumaWorks Software Packages

### yangcli-pro

The [yangcli-pro](https://dev.yumaworks.com/product/yangcli-pro/)
package provides a program for managing NETCONF and RESTCONF servers.


### yumapro-sdk-basic

The [yumapro-sdk-basic](https://dev.yumaworks.com/product/yumapro-sdk-basic/)
package provides a NETCONF Server and SDK for developing YANG server instrumentation.


### yumabench

The [yumabench](https://dev.yumaworks.com/product/yumabench/)
package provides a Qt6-based GUI for managing NETCONF servers.

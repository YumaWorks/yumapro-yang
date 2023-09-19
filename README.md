# yumapro-yang

## YumaPro SDK YANG Modules

Contains the [YumaWorks](https://www.yumaworks.com)
YANG modules used in YumaPro SDK software.

## YumaPro Release Trains

YumaWorks maintains multiple release trains to increase stability.
Each October a new release train is started. (e.g. 20.10, 21.10).

 - YumaPro SDK Release Trains
     - 21.10: oldstable
     - 22.10: stable (current)
     - 22.10T: unstable

[YumaPro Release Information](https://www.yumaworks.com/features/yumapro-sdk-release-information/)

### List the available tagged versions


      > git tag


### Checkout the YANG modules for a specific release:

Use the git checkout command. Example: Checkout the 20.10-13 release on branch 'my-branch'


     > git checkout tags/21.10-3 -b my-branch


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

### yangcli-pro

The [yangcli-pro](https://dev.yumaworks.com/product/yangcli-pro/)
package provides a program for managing NETCONF and RESTCONF servers.


### yumapro-sdk-basic

The [yumapro-sdk-basic](https://dev.yumaworks.com/product/yumapro-sdk-basic/)
package provides a NETCONF Server and SDK for developing YANG server instrumentation.


### yumabench

The [yumabench](https://dev.yumaworks.com/product/yumabench/)
package provides a Qt6-based GUI for managing NETCONF servers.

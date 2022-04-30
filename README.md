# yumapro-yang

## YumaPro SDK YANG Modules

Contains the [YumaWorks](https://www.yumaworks.com)
YANG modules used in YumaPro SDK software.

## YumaPro Release Trains

YumaWorks maintains multiple release trains to increase stability.
Each October a new release train is started. (e.g. 20.10, 21.10).

 - YumaPro SDK Release Trains
     - 19.10: oldstable
     - 20.10: stable
     - 21.10: stable (current)
     - 21.10T: unstable

[YumaPro Release Information](https://www.yumaworks.com/features/yumapro-sdk-release-information/)

### List the available tagged versions


      > git tag


### Checkout the YANG modules for a specific release:

Use the git checkout command. Example: Checkout the 20.10-13 release on branch 'my-branch'


     > git checkout tags/20.10-13 -b my-branch


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
This package uses the 20.10 release train.

### yumapro-sdk-basic

The [yumapro-sdk-basic](https://www.yumaworks.com/support/download-yumapro-sdk-basic/)
package provides a NETCONF Server and SDK for developing YANG server instrumentation.
This package uses the 20.10 release train.

### yumabench

The [yumabench](https://www.yumaworks.com/support/download-yumabench/)
package provides a Qt5-based GUI for managing NETCONF servers.

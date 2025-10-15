# yumapro-yang

## YumaPro SDK YANG Modules

Contains the [YumaWorks](https://www.yumaworks.com)
YANG modules used in YumaPro SDK software.

## Latest YumaPro Release

YumaWorks maintains multiple release trains to increase stability.
Each October a new release train is started. (e.g. 22.10, 23.10).

Only the latest version (25.10) is maintained here.
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

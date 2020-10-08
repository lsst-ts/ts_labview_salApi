# Telescope and Site LabVIEW SAL API

This module is to collect the low-level LabVIEW SAL API of subsystems for other modules to use. SAL means the service abstract layer.

## Platform

- CentOS 7
- LabVIEW 2018 SP1 64-bit Professional Version

## Needed Package

- [ts_sal](https://github.com/lsst-ts/ts_sal)
- [ts_idl](https://github.com/lsst-ts/ts_idl) (Needed by ts_sal)
- [ts_opensplice](https://github.com/lsst-ts/ts_opensplice) (Use OpenSpliceDDS V6.9)
- [ts_xml](https://github.com/lsst-ts/ts_xml)
- [ts_SALLabVIEW](https://github.com/lsst-ts/ts_SALLabVIEW)

The specific package versions are listed in each subsystem directory.

## Use the SAL LabVIEW Vi

Follow the `README.md` in [ts_SALLabVIEW_test](https://github.com/lsst-ts/ts_SALLabVIEW_test).

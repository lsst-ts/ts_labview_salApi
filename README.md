# Telescope and Site LabVIEW SAL API

*This module is to collect the low-level LabVIEW SAL API of subsystems for other modules to use. SAL means the service abstract layer.*

## 1. Platform

- *CentOS 7*

## 2. Needed Package

- *[ts_sal](https://github.com/lsst-ts/ts_sal)*
- *[ts_opensplice](https://github.com/lsst-ts/ts_opensplice) (OpenSpliceDDS V6.9.0 is used)*
- *[ts_xml](https://github.com/lsst-ts/ts_xml)*
- *[ts_SALLabVIEW](https://github.com/lsst-ts/ts_SALLabVIEW)*

*The specific package versions are listed in each subsystem directory.*

## 3. Increase the Stack Size

*For the SAL LabVIEW monitor to run, the user needs to increase the stack size. The default value is 8192 kb on CentOS 7 (check by `ulimit -s`). The user can use `ulimit -s 100000` to increase the stack size to be 100 mb.*

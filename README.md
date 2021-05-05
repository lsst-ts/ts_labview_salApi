# Telescope and Site LabVIEW SAL API

This module is to collect the low-level LabVIEW SAL API of subsystems for other modules to use. SAL means the service abstract layer.

## Platform

- CentOS 7
- LabVIEW 2018 SP1 64-bit Professional Version

## Needed Package

- [ts_sal](https://github.com/lsst-ts/ts_sal)
- [ts_idl](https://github.com/lsst-ts/ts_idl) (Needed by ts_sal)
- [ts_xml](https://github.com/lsst-ts/ts_xml)
- [ts_SALLabVIEW](https://github.com/lsst-ts/ts_SALLabVIEW)
- OpenSpliceDDS (by `lsst-ts-private` repository)

The specific package versions are listed in each subsystem directory.

## Information of lsst-ts-private Repository

The details of repository file is in the following (`username` and `password` are ignored):

```text
[lsst-ts-private]
name=LSST Telescope and Site packages - $basearch
baseurl=https://repo-nexus.lsst.org/nexus/repository/ts_yum_private
failovermethod=priority
enabled=0
gpgcheck=0
```

## Use the SAL LabVIEW Vi

Follow the `README.md` in [ts_SALLabVIEW_test](https://github.com/lsst-ts/ts_SALLabVIEW_test).

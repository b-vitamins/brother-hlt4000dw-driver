# Brother HL-T4000DW Driver

This repository contains the necessary files to build and release the .deb package for the Brother HL-T4000DW printer driver.

## Structure

- `DEBIAN/`: Package control files.
- `src/`: Printer driver and configuration files.
  - `opt/`: Contains the Brother printer files.
  - `usr/`: Contains the Brother printer executable.

## Building the package

To build the .deb package, you can use the following command:

```
dpkg-deb --build build/package hlt4000dw-driver.deb
```


##### This repository contains a repo manifest for building the HCC compiler

See the [wiki](https://github.com/RadeonOpenCompute/HCC-Native-GCN-ISA/wiki) for more detailed information.

### Build HCC
```bash
mkdir hcc
cd hcc
repo init -u https://github.com/RadeonOpenCompute/HCC-Native-GCN-ISA.git
repo sync
mkdir hcc/build
cd hcc/build
cmake ..
make
```

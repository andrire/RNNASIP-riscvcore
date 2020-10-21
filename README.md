[![Build Status](https://travis-ci.com/pulp-platform/riscv.svg?branch=master)](https://travis-ci.com/pulp-platform/riscv)
This is a fork of https://github.com/pulp-platform/riscv/tree/rnn_extension (ad1680c2ec65ea65b8e342c16131298b290c9e34)


# RI5CY: RISC-V Core

RI5CY is a small 4-stage RISC-V core. It started its life as a
fork of the OR10N CPU core that is based on the OpenRISC ISA.

RI5CY fully implements the RV32IMFC instruction set and many custom instruction
set extensions that improve its performance for signal processing applications.
It partially supports the privileged spec 1.10, USER MODE and Physical Memory Protection.

It has a custom debug support.

The core was developed as part of the [PULP platform](http://pulp.ethz.ch/) for
energy-efficient computing and is currently used as the processing core for
PULP and PULPino.

## Documentation

A datasheet that explains the most important features of the core can be found
in  the doc folder.

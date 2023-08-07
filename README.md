# EasyCT

## Terminology

- Burden Resistor: Also known as *sampling resistor*


## Supported Inputs

EasyCT supports most current-mode current transformers
(that is, current transformers without a built-in burden resistor).
These will have their outputs listed as currents (typically $\textrm{mA}$ or $\textrm{A}$),
__not__ voltages ($\textrm{mV, V}$) 

Additionally the PCB footprint has support for the following transformers:
- Three Terminal Jacks (known as TRS, AUX, XLR)
  - [YHDC-SCT013-000](https://www.poweruc.pl/collections/split-core-current-transformers2/products/split-core-current-transformer-sct013-rated-input-5a-100a)
- 2-Wire
  - PZCT10020 (generally PZCT-XXXXX, etc)
  - DLXQ26-XXXX
- ZMCT-style
  - ZMCT103C
  - ZMCT118F

## Supported Configurations
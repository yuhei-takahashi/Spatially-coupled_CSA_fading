[![DOI](https://img.shields.io/badge/DOI-10.1109/GCWKSHPS58843.2023.10464976-blue)](https://doi.org/10.1109/GCWKSHPS58843.2023.10464976) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Abstract

This repository provides C++ implementations for SC-CSA (Spatially coupled Coded Slotted ALOHA) system over Rayleigh fading channels.

### Overview of what is provided
- Monte Carlo Simulation
- Density Evolution

## Development environment
```
~ % xcodebuild -version
Xcode 15.3
Build version 15E204a
~ % c++ --version
Apple clang version 15.0.0 (clang-1500.3.9.4)
Target: x86_64-apple-darwin23.4.0
Thread model: posix
```

## Paramaters
The parameters in these source codes are as follows:

<ins>Simulation<ins>
- ite : # of fading samples
- SNR : average received SNR per device (dB)
- M : M+1 collisions wihtin a slot
- K : # of message segments
- trans : transmission packets per slot
  
<ins>Analysis<ins>
- SNR : average received SNR per device (dB)
- M : M+1 collisions wihtin a slot
- IS : # of message segments

Please, adjust the parameters as needed for your situation.

## Demo
<ins>Simulation<ins>

Here's how you'd run these codes:

<ins>Analysis<ins>





## Result


## How to cite

If you extend or use this work, please cite the [paper](https://ieeexplore.ieee.org/document/10464976) where it was introduced:
```
@INPROCEEDINGS{10464976,
  author={Takahashi, Yuhei and Masuo, Ippei and Song, Guanghui and Kimura, Tomotaka and Cheng, Jun},
  booktitle={2023 IEEE Globecom Workshops (GC Wkshps)}, 
  title={Coded Slotted ALOHA over Rayleigh Block Fading Channels: BP Threshold and Converse Bound}, 
  year={2023},
  volume={},
  number={},
  pages={1523-1528},
  keywords={Couplings;Codes;Protocols;Error probability;Rayleigh channels;Interference;Energy efficiency;belief propagation threshold;coded slotted ALOHA;converse bound;Rayleigh fading;spatial coupling},
  doi={10.1109/GCWkshps58843.2023.10464976}}
```

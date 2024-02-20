---
layout: default
---

# Supported Hardware

This is a brief list of hardware known to work with libscopehal and ngscopeclient, sorted by manufacturer. Similar models may work as well although correct functionality is not guaranteed. We'd love to hear results (successful or otherwise) of testing with instruments not listed here.

For full details on which features are or are not supported by particular drivers, known issues, etc. please see the appropriate section of the user manual.

# Agilent

* DSO5000
* DSO6000
* DSO7000
* MSOX-2000
* MSOX-3000

# ASEQ Instruments

* LR1 UV-VIS-NIR spectrometer via [bridge server](https://github.com/ngscopeclient/scopehal-aseq-bridge)

# Copper Mountain

* All instruments using S2VNA/S4VNA software (including S5180B)

# Digilent

* Analog Discovery via [bridge server](https://github.com/ngscopeclient/scopehal-waveforms-bridge)
* Analog Discovery 2 via [bridge server](https://github.com/ngscopeclient/scopehal-waveforms-bridge)
* Analog Discovery Pro via [bridge server](https://github.com/ngscopeclient/scopehal-waveforms-bridge)

# DreamSource Lab

* DScope U3P100 via [bridge server](https://github.com/ngscopeclient/scopehal-sigrok-bridge)
* DSLogic U3P16 via [bridge server](https://github.com/ngscopeclient/scopehal-sigrok-bridge)

# EEVengers

* Thunderscope

# Keysight

* DCA 86100A
* MSOX-2000
* MSOX-3000
* MSOX-3000T

# GW Instek

* GPD-X303S power supply

# HP

* 662xA power supply

# MultiLane

* ML4039 BERT via [bridge server](https://github.com/ngscopeclient/scopehal-mlbert-bridge)

# Pico

* All VNAs supported by PicoVNA 5 software (PicoVNA 106, 108)
* 3000D series via [bridge server](https://github.com/ngscopeclient/scopehal-pico-bridge)
* 6000E series via [bridge server](https://github.com/ngscopeclient/scopehal-pico-bridge)

# Rigol

* DG4000 series function generator
* DS1100D/E
* DS1000Z
* MSO5000

# Rohde & Schwarz

* HMC8012 multimeter
* HMC804x series power supply
* RTO6

# Siglent

* SDL1000X/X-E series electronic load
* SDS1000X-E
* SDS2000X-E
* SDS2000X+ / SDS2000X+ HD
* SDS5000X
* SDS6000A
* SPD3303X / X-E series power supply
* SSG5000X / X-V series RF/vector signal generator

# Teledyne LeCroy

All MAUI based oscilloscopes share a common command set and should work for data capture and remote control without any additional driver development, but the dropdown lists for supported sample rates and memory depths have to be added to the driver for each model. The models below have been recently tested, others can be easily added if required.

* DDA5000A
* HDO9000
* SDA 8Zi
* SDA 8Zi-A
* WaveRunner 8000
* WaveRunner 9000
* WaveSurfer 3000

# Tektronix

* MSO5
* MSO6

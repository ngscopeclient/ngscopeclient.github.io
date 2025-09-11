---
layout: default
---

# Supported Hardware

This is a brief list of hardware known to work with libscopehal and ngscopeclient, sorted by manufacturer. Similar models may work as well although correct functionality is not guaranteed. We'd love to hear results (successful or otherwise) of testing with instruments not listed here.

For full details on which features are or are not supported by particular drivers, known issues, etc. please see the appropriate section of the user manual.

A "slow" marking indicates that the device is supported, but known to have poor performance due to instrument firmware
limitations. (Many benchtop scopes, even relatively high end ones, are not well optimized for remote control. Delays of hundreds of milliseconds between the trigger and the API reporting availability of data, and multiple seconds to actually download waveform data, are not uncommon on entry level instruments)

# Agilent

* DSO5000
* DSO6000
* DSO7000
* MSOX-2000
* MSOX-3000 (slow)

# Alientek

* DP100

# Andy Haas

* Haasoscope Pro

# ASEQ Instruments

* LR1 UV-VIS-NIR spectrometer via [bridge server](https://github.com/ngscopeclient/scopehal-aseq-bridge)

# Copper Mountain

* All instruments using S2VNA/S4VNA software (including S5180B)

# Digilent

* Analog Discovery via [bridge server](https://github.com/ngscopeclient/scopehal-waveforms-bridge)
* Analog Discovery 2 via [bridge server](https://github.com/ngscopeclient/scopehal-waveforms-bridge)
* Analog Discovery Pro via [bridge server](https://github.com/ngscopeclient/scopehal-waveforms-bridge)

# DreamSource Lab

We've received reports that recent DSLogic updates have broken this. Nobody is currently maintaining this driver but we'd love for someone to take it over.

* DScope U3P100 via [bridge server](https://github.com/ngscopeclient/scopehal-sigrok-bridge)
* DSLogic U3P16 via [bridge server](https://github.com/ngscopeclient/scopehal-sigrok-bridge)

# edy555

* NanoVNA

# EEVengers

* Thunderscope

# Eric Kaashoek

* TinySA Ultra

# Ettus Research

* UHD-based SDRs (receive only) via [bridge server](https://github.com/ngscopeclient/scopehal-uhd-bridge)

# Generic

* CSV streaming data over TCP socket
* Linux socketcan

# GW Instek

* GPD-X303S

# HP

* 662xA power supply

# Keysight

* DCA 86100A
* MSOX-2000
* MSOX-3000
* MSOX-3000T (slow)

# Kuaiqu

* SSPS-S
* SPPS*D
* SPPS-D
* R-SPPS

# Microphase

* AntSDR running UHD firmware only via [bridge server](https://github.com/ngscopeclient/scopehal-uhd-bridge), IIO firmware not supported

# MultiLane

* ML4039 BERT via [bridge server](https://github.com/ngscopeclient/scopehal-mlbert-bridge)

# Owon

* XDG 2000
* XDG 3000
* XDM 1041
* XDM 1241

# Pico

* All VNAs supported by PicoVNA 5 software (PicoVNA 106, 108)
* 3000D series via [bridge server](https://github.com/ngscopeclient/scopehal-pico-bridge)
* 6000E series via [bridge server](https://github.com/ngscopeclient/scopehal-pico-bridge)

# Riden

* RD series

# Rigol

* DG4000 series function generator
* DS1100D/E (slow)
* DS1000Z (slow)
* MSO5000 (slow)
* DHO800 (slow)
* DHO900 (slow)
* DP832/832A power supply

# Rohde & Schwarz

* HMC8012 multimeter
* HMC804x series power supply
* RTM3000 (partial)
* RTO6

# Siglent

* SDL1000X/X-E series electronic load
* SDS1000X-E (slow)
* SDS2000X-E (slow)
* SDS2000X+ / SDS2000X+ HD (slow)
* SDS2000X HD (slow)
* SDS3000X HD (slow)
* SDS5000X (slow)
* SDS6000A
* SDS7000A
* SPD3303X / X-E series power supply
* SSG5000X / X-V series RF/vector signal generator

# Tektronix

* MSO5 (slow, firmware occasionally crashes)
* MSO6 (slow, firmware occasionally crashes)

# Teledyne LeCroy

All MAUI based oscilloscopes share a common command set and should work for data capture and remote control without any additional driver development, but the dropdown lists for supported sample rates and memory depths have to be added to the driver for each model. The models below have been recently tested, others can be easily added if required.

* DDA5000A
* HDO9000
* SDA 8Zi
* SDA 8Zi-A
* WaveRunner 8000
* WaveRunner 9000
* WaveSurfer 3000 (slow)

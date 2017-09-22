# Side Channel *Live!*

Welcome to Side Channel *Live!*. This "tutorial" is running at CHES 2017 in Taipei, Taiwan on September 25th. The objective is to provide some hands-on time for anyone interested in side-channel power analysis (or maybe a little fault injection) to work with some targets & tools.

A quick introduction will also be included, for anyone who is new to the field.

Note the final documentation will be updated closer to the actual event, with traces released shortly before it.

### Agenda ###

**13:00 - 13:30** Introduction, Event Setup, Data Format, Challenges.

**13:30 - 14:30** Tutorial on power analysis (for those new to field).

**14:30 - 15:00** Break

**15:00 - 16:00** Work on challenges, short presentations.

**16:00 - 16:30** Wrap-Up

# Hands-on Hardware #

Exact hardware present is still T.B.D. & will be updated on-site with a final tally. Expected hardware includes:

* AVR/XMEGA Targets
* ARM Targets (STM32Fx)
* MPC5748G Target (PowerPC)
* Artix FPGA Target
* Spartan 6 FPGA Target

* Several ChipWhisperer capture boards.

# Remote Server #

Pending connectivity, a remote server will provide virtual hardware access to several ChipWhisperer devices.

# Open Challenges #

### Calibration Waveforms ###

Several calibration waveforms are available, which may help you confirm your CPA attack is working as expected.

### Hardware Crypto ###

The following traces have been collected from various devices.

* HW Crypto, no countermeasures

* HW Crypto, basic countermeasures

* HW Crypto, unknown

# Contributing Changes #

All files/write-ups will be stored in the "CHES2017" directory. Please feel free to submit pull requests to this repository so we can keep any interesting results public.
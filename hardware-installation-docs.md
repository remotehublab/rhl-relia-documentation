# RHL RELIA Hardware Installation Docs

## Introduction

In the RHL RELIA project, we create remote laboratories for SDR (Software-Defined Radio), relying on the open-source [GNU Radio](https://www.gnuradio.org/). Most of the software and hardware developed in this project would work with any SDR kit that is supported by GNU Radio. Within the project, we have used two kits:

 * [ADALM Pluto](https://www.analog.com/en/resources/evaluation-hardware-and-software/evaluation-boards-kits/adalm-pluto.html)
 * [Red Pitaya STEMlab 125-14](https://redpitaya.com/stemlab-125-14/)

This document explains how to install the equipment and integrate it with RHL Relia. If you are interested in using RHL Relia with a different kit, please contact us.

## 3D-printed pieces

@zzyzzy42 how to print and why and which pieces

### Option 1: ADALM Pluto

@zzyzzy42 how to print, how to install, what model, and why and which pieces

### Option 2: Red Pitaya

@zzyzzy42 how to print, how to install, what model, and why and which pieces

[![Red Pitaya 3D printed piece](https://img.youtube.com/vi/U8Kwl83dq8U/0.jpg)](https://www.youtube.com/watch?v=U8Kwl83dq8U)

See the video: https://www.youtube.com/watch?v=U8Kwl83dq8U

## Structures

There are two alternatives. We have done both during the RHL RELIA project:
 * Creating our own structure
 * Relying on a third party-structure (such as LabsLand Prism4)

In this section, we explain both approaches.

### Option 1: Build your structure

What you have to have is essential:

 * A Raspberry Pi 4, fully powered with a proper USB charger (or any other charger, e.g., GPIO)
 * The two SDR devices (e.g., two ADALM Pluto or two Red Pitaya)
 * A camera (this is optional, but it helps students see that they are working with a real device and not with a simulation), and a camera management system (such as [WILSP](https://github.com/zstars/wilsp) -[paper](https://ieeexplore.ieee.org/document/7937791)-, [motion](https://motion-project.github.io/) or any other).

Then you need some space where to put it, such as some kind of shelves, etc., and you need to use a power strip and an ethernet switch to use it.

<p align=center><img src="images/hardware-installation-docs/your-own-structure.jpg" width="50%"></p>

In the picture above, you can see one shelving unit, with two setups of ADALM Pluto (and their corresponding Raspberry Pi), without the Faraday boxes, and two Red Pitaya on the bottom right (not yet connected).

### Option 2: LabsLand Prism4

Alternatively, [LabsLand](https://labsland.com) provides the Prism4 structures, which are more compact and they already provide mechanisms for powering up two setups with a single power supply.

In the pictures above you can see 5 LabsLand Prism4, each of them containing two sets of remote laboratories (total 10 remote labs), each set of remote laboratories having 2 SDR devices each (20 SDR devices, each pair -transmitter and receiver- of SDR devices inside a Faraday Cage). Each Prism4 comes with two cameras, software to manage it, power supply and power cables, an ethernet switch, a light system and shadows (to prevent the light hitting directly on the remote laboratory) and relies on [Phase Dock](https://phasedock.com/) workbench modular bases to be able to adjust both the remote laboratory and the Raspberry Pi's.

<p align=center><img src="images/hardware-installation-docs/labsland_prism4_1.jpg" width="45%"><img src="images/hardware-installation-docs/labsland_prism4_2.jpg" width="45%"></p>

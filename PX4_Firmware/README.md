## PX4 Pro Drone Autopilot ##

[![Releases](https://img.shields.io/github/release/PX4/Firmware.svg)](https://github.com/PX4/Firmware/releases) [![DOI](https://zenodo.org/badge/22634/PX4/Firmware.svg)](https://zenodo.org/badge/latestdoi/22634/PX4/Firmware) [![Build Status](https://travis-ci.org/PX4/Firmware.svg?branch=master)](https://travis-ci.org/PX4/Firmware) [![Coverity Scan](https://scan.coverity.com/projects/3966/badge.svg?flat=1)](https://scan.coverity.com/projects/3966?tab=overview)

[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/PX4/Firmware?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

This repository holds the [PX4 Pro](http://px4.io) flight control solution for drones, with the main applications located in the src/modules directory. It also contains the PX4 Drone Middleware Platform, which provides drivers and middleware to run drones.

*   Official Website: http://px4.io (License: BSD 3-clause, [LICENSE.md](https://github.com/PX4/Firmware/blob/master/LICENSE.md))
*   Supported airframes (more experimental types than listed here are supported):
  * [Multicopters](http://px4.io/portfolio_category/multicopter/)
  * [Fixed wing](http://px4.io/portfolio_category/plane/)
  * [VTOL](http://px4.io/portfolio_category/vtol/)
*   Releases: [Downloads](https://github.com/PX4/Firmware/releases)

### Weekly Dev Call

The PX4 Dev Team syncs up on its weekly dev call (connect via [Mumble](http://mumble.info) client).

  * TIME: 19:00h Zurich time, 1 p.m. Eastern Time, 10 a.m. Pacific Standard Time
  * Server: sitl01.dronetest.io
  * Port: 64738
  * Password: px4
  * The agenda is announced in advance on the [PX4 Discuss](http://discuss.px4.io/c/weekly-dev-call)
  * Issues and PRs may be labelled "devcall" to flag them for discussion### Users ###

Please refer to the [user documentation](http://px4.io/user-guide/) and [user forum](http://discuss.px4.io) for flying drones with the PX4 flight stack.

### Developers ###

  * [Developer Forum](http://discuss.px4.io)
  * [Guide for Contributions](https://github.com/PX4/Firmware/blob/master/CONTRIBUTING.md)
  * [Developer guide](http://dev.px4.io)

## Maintenance Team

  * Project / Founder - [Lorenz Meier](http://github.com/LorenzMeier)
  * Dev Call - [Mark Whitehorn](http://github.com/kd0aij), [Ramon Roche](http://github.com/mrpollo)
  * Communication Architecture - [Beat Kueng](http://github.com/bkueng), [Julian Oes](http://github.com/JulianOes)
  * UI / UX - [Gus Grubba](http://github.com/dogmaphobic)
  * Multicopter Flight Control - [Dennis Mannhart](http://github.com/Stifael), [Matthias Grob](http://github.com/MaEtUgR)
  * VTOL Flight Control - [Roman Bapst](http://github.com/tumbili), [Andreas Antener](http://github.com/AndreasAntener), [Sander Smeets](http://github.com/sanderux)
  * Fixed Wing Flight Control - [Daniel Agar](http://github.com/dagar), [Paul Riseborough](http://github.com/priseborough)
  * Racers - Anton Matosov / [Mark Whitehorn](http://github.com/kd0aij)
  * OS / drivers - [David Sidrane](http://github.com/david_s5)
  * UAVCAN / Industrial - [Pavel Kirienko](http://github.com/pavel-kirienko)
  * State Estimation - [James Goppert](http://github.com/jgoppert), [Paul Riseborough](http://github.com/priseborough)
  * VIO - Christoph Tobler
  * Obstacle Avoidance - [Vilhjalmur Vilhjalmsson](http://github.com/vilhjalmur89)
  * Snapdragon - [Mark Charlebois](http://github.com/mcharleb)
  * Intel Aero - [Lucas de Marchi](http://github.com/lucasdemarchi), [Simone Guscetti](http://github.com/simonegu)
  * Raspberry Pi / Navio - [Beat Kueng](http://github.com/bkueng)
  * Parrot Bebop - [Michael Schaeuble](http://github.com/eyeam3)

## Supported Hardware

This repository contains code supporting these boards:
  * [Snapdragon Flight](http://dev.px4.io/hardware-snapdragon.html)
  * Intel Aero
  * Raspberry PI with Navio 2
  * [Parrot Bebop](http://dev.px4.io/starting-building.html#parrot-bebop)
  * FMUv1.x
  * FMUv2.x ([Pixhawk](http://dev.px4.io/hardware-pixhawk.html) and [Pixfalcon](http://dev.px4.io/hardware-pixfalcon.html))
  * FMUv3.x ([Pixhawk 2](http://dev.px4.io/hardware-pixhawk.html))
  * FMUv4.x (Pixhawk 3 Pro and [Pixracer](http://dev.px4.io/hardware-pixracer.html))
  * FMUv5.x (ARM Cortex M7, future Pixhawk)
  * AeroCore (v1 and v2)
  * STM32F4Discovery (basic support) [Tutorial](https://pixhawk.org/modules/stm32f4discovery)
  * MindPX V2.8 [Tutorial](http://www.mindpx.net/assets/accessories/UserGuide_MindPX.pdf)
  * MindRacer V1.2 [Tutorial](http://mindpx.net/assets/accessories/mindracer_user_guide_v1.2.pdf)

## Project Milestones

The PX4 software and Pixhawk hardware (which has been designed for it) has been created in 2011 by Lorenz Meier.

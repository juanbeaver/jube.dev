---
layout: page
title: Tonometry / Poroelasticity Measurement Device
description: Custom LVDT readout PCB + closed-loop instrument for lymphedema monitoring
img: assets/img/1.jpg
importance: 1
category: research
---

Built a proof-of-concept instrument to characterize poroelastic properties of limbs for lymphedema and edema monitoring.

**Hardware:** Designed a custom LVDT read-out board in KiCad — ADC + microcontroller + analog filtering — achieving sub-micron displacement resolution with < 5 µV RMS noise at 300 Hz sampling.

**Firmware & Software:** Wrote MCU firmware and a Python/GUI application for acquisition, filtering, and logging. Implemented closed-loop motion control with E-stop and homing routines. PID-tuned a DC motor controller for low-disturbance weight placement; bench-stress tested for repeated use.

**Skills:** KiCad PCB design, analog front-end design, C firmware, Python/GUI, PID control, closed-loop motion.

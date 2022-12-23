---
title: "Midterm Report"
date: 2022-12-22T16:01:23+08:00
lastmod: 2022-12-22T16:01:23+08:00
draft: false
tags: ["preview", "shortcodes", "tutorial"]
categories: ["Notes"]
authors:
- "Yuxuan Li"
---
![Drone test](/drone.jpg)
# ESE519_Midterm Report
For ESE 519 midterm report. Drone with learning.

- **code:**
  - **working:**
    - RP2040
    - balance board Python code
    - PIO PWM code on PIO 0
    - I2C communication on PIO 1 from lab 2B
  - **in-progress:**
    - Pico4ML
    - Machine learning
    - gyroscope
  - **libraries:**
    - pwm.pio, uart_rx.pio, uart_tx.pio
    - pico_stdlib, hardware_pio, hardware_pwm
    - pico_multicore
  - **reference:**
    - https://cla.purdue.edu/academic/rueffschool/ad/etb/resources/robotics01_SN754410_Arduino.pdf
- **media:**
  - **materials:**
    - Pico4ML Image

     <img class="special-img-class" src="/static/drone.jpg" />
    - MiniDrone

    <img width="380" alt="Drone" src="./Pico4ML.jpeg">

    - RP2040
    
    <img width="300" alt="RP2040" src="media/materials/RP2040.jpeg">

    -LSM6DS3

    <img width="300" alt="RP2040" src="media/materials/LSM6DS3.png">


  - **design:**
  * Self-designed drone with hacking:
  Hacking:
         1. Borrow the shell of bought drone.
         2. Hacking the structure.
         3. Hacking the signals to control the servo.  


 
 <img width="500" alt="circuit" src="https://user-images.githubusercontent.com/87698138/205519976-f471acd5-c7fc-46cb-b8ed-c9c0dd39164f.jpg">
  
  - **troubleshooting:**
    - How to make the fan blades turn from 0
    - Using an oscilloscope to hack the original circuit to learn that the servo is DC input,then the group using pio and pwm to modify the value of the DC current and let the servo rotate with different speed. 

  - **demos:**
    - video
    The demo is given as follows:  
    
    ![Demo](media/materials/Demo.gif)
    
    - circuit connection
    
    <img width="500" alt="now" src="media/media in readme/12.3circuit.jpeg">

- **diagram:**
 
 <img width="500" alt="now" src="media/media in readme/diagram.jpeg">

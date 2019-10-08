
# liketohear

This repository holds the information for an web app control of the mobile openMHA hearing aid prototype.

This prototype is developed in he framework of the citizen science project ["Hear How You Like To Hear"  at the Fraunhofer IDMT Oldenburg](https://www.idmt.fraunhofer.de/de/institute/projects-products/projects/liketohear.html), funded by the BMBF. 
Corresponding author: Peggy Sylopp

# Aims
The prototype was deliberately designed for the self-fitting field research using affordable consumer hardware and open source software. The aim is to lower the entry barrier for hearing aid development and facilitate any interested person to get actively involved in testing and improving hearing devices; empowering power-users.

# Warning and disclaimer
First, a few words of warning:
Hearing aids are medical products! You use these instructions and the software at you own risk. The described device can produce very high sound levels. Exposure to high sound levels can permanently damage your hearing! You are responsible for the configuration of the device and the protection of your hearing.
Please read about the consequences of noise induced hearing loss before proceeding to the fun part: https://www.nidcd.nih.gov/health/noise-induced-hearing-loss


Main ingredients
Hardware:
* Binaural Microphones/Earphones
* Microphone pre-amplifier
* Raspberry Pi 3 model B
* Low-latency sound card
* USB power bank
* Bluetooth remote control
* Software:
  * openMHA
  * Raspbian
  * JACK
  * hostapd
  * OpenSSH
  * GNU/Octave
  * liketohear control app
festival-lite

# Main characteristics
Free software: Control is yours, you can change every single bit of it!
Efficient real-time implementations of research-approved hearing algorithms (c.f. openMHA at Github)
Competitively low delays: Less than 5ms
Looks like wearing in-ear headphones
Whole setup fits in a belt bag
Sum of all components is about 250 €

* Some cool features
  * Pre-configured SD-card image (~500 Mb) available for download!
  * Pre-calibrated for most "transparent" acoustic impression
  * Autostart on boot
  * Several hours of autonomy
  * Remote control via Bluetooth game pad
  * Connect via WiFi to the hearing aid prototype
  * Simulate impaired hearing with threshold simulating noise
  * Fit it to your hearing thresholds
  * Fit it to arbitrary hearing profiles using openMHA's graphical fitting interface
  * Extend openMHA with own algorithms
  * Combine it with any jack-based software (play, process, or record)

# Instructions
This page is only a teaser The files in this repository only contain the employed openMHA configuration file, a start script, and some example configuration files. The actual instructions are deployed in the corresponding wiki. Feel free to test them and contribute. Be sure to read the openMHA documentation (pdf files) if you want to dig deeper into signal processing for hearing aids.


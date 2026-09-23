# Junseo Park

Founder of SHADE. I build signal intelligence systems end to end: the SDR nodes that collect in the field, the server that fuses what they hear, the analyst screen on top, and the unmanned aircraft that carry the sensors. Most of it is C++ and Python, runs in real time on low-cost COTS hardware, and is meant to keep working unattended and without outside networks.

Background: B.S. in Computer Science. I spent Jul. 2022 – Feb. 2025 as a Technical ELINT Analyst at the Defense Security Agency, 777th Command, then worked as a Satellite Monitoring Assistant at the Satellite Radio Monitoring Center, Ministry of Science and ICT (Jul. 2025 – Sep. 2025). I founded SHADE in Apr. 2026.

What I enjoy most is pulling structure out of raw IQ: FFT, demodulation, spectral analysis, emitter identification. I like testing against the real thing, so the simulator runs the actual flight firmware, direction finding is calibrated on site, and every flight log gets analyzed. I also write a lot down: design calculations, procedures, and flight records.

## Projects

| Repository | Description |
|---|---|
| [BEWE](https://github.com/6K5EUQ/BEWE) | Distributed real-time SIGINT platform. SDR collection nodes, a central fusion server, and analyst workstations run as one system. Multi-site direction finding, ten concurrent demodulators, protocol decoders (ACARS, ADS-B, AIS, DMR, Wi-Fi, Bluetooth LE), ELINT pulse analysis, GPS jamming localization, satellite downlink tracking, and on-station ML for modulation classification and RF fingerprinting. |
| [SHADE01](https://github.com/6K5EUQ/SHADE01) | SIGINT UAV platform on a VTOL 4+1 quadplane running PX4. Flight log analysis, live telemetry, and preflight checks for the aircraft I assemble and fly. |
| [VTOL_SIMULATOR](https://github.com/6K5EUQ/VTOL_SIMULATOR) | Flight trainer that runs the real ArduPilot firmware in SITL, flown from a real transmitter in the browser with CesiumJS. |
| [DRONE](https://github.com/6K5EUQ/DRONE) | 2 kg quadcopter designed from scratch: design calculations, assembly and test procedures, flight controller history. |
| [BEWEX](https://github.com/6K5EUQ/BEWEX) | Live monitor that puts field cameras and ground-station screens on one console over WebRTC, falling back to a relay when P2P is blocked. |
| [AI-Hackathon](https://github.com/6K5EUQ/AI-Hackathon) | Air-gapped AI maritime monitoring platform built on received AIS signals. Honorable Mention, 11th Busan-Ulsan-Gyeongnam AI Convergence Hackathon (2026). |

## Stack

C++ Python JavaScript SDR PX4 ArduPilot WebRTC

## Elsewhere

[shade-signals.com](https://shade-signals.com)

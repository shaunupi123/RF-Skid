# RF-Skid
A RF pentest tool which runs based on the Bruce firmware with NRF , IR, CC1101 capabilities
# RF Skid 📡

Multi-protocol radio frequency research and wireless security testing device with Bruce Firmware.

RF Skid is a portable wireless experimentation platform which utilises Bruce Firmware. It is designed for radio-frequency (RF) exploration, infrared control, protocol research, and authorised penetration testing, combining multiple wireless interfaces in one compact device for hardware experimentation and security assessment.

## ✨ Features

- 📻 CC1101 Sub-GHz Radio — explore supported sub-GHz frequencies, inspect compatible signals, and experiment with RF protocols.

- 📡 NRF24L01+ Support — experiment with 2.4 GHz radio communication, compatible packet formats, and wireless protocol analysis.

- 📺 Infrared (IR) — capture, analyse, and transmit compatible infrared signals for remote-control testing and automation.

- 🧠 Bruce Firmware — take advantage of the Bruce firmware interface and supported features for wireless research.

- 🛠️ Modular Hardware — integrate multiple radio interfaces into one portable RF testing platform.

- 🔬 Security Research — learn about wireless protocols, evaluate compatible devices, and investigate potential security weaknesses in an authorised test environment.

> Note: Actual functionality will be dependent on the hardware revision, modules connected, firmware version, antenna configuration, and features supported by Bruce Firmware.

## 🧩 Hardware

RF Skid is based around a compatible Bruce-supported controller and external radio modules.

| Component | Purpose |

|---|---|

| Main controller | Runs Bruce Firmware and manages the device |

| NRF24L01+ | 2.4 GHz wireless experimentation |

| CC1101 | Supported sub-GHz RF experimentation |

| IR transmitter | Send compatible infrared commands |

| IR receiver | Capture compatible infrared signals, if fitted |

| Antennas | Support the relevant radio bands |

| Display and controls | Provide the user interface, if fitted |

| Power supply | Power the controller and connected modules |

Update this table to reflect the exact hardware fitted to your RF Skid.

## 🚀 Getting Started

### 1. Prepare the hardware

- Ensure that your controller is supported by the Bruce Firmware version you plan to use.

- Connect the NRF24L01+, CC1101, and IR hardware according to your board's wiring diagram.

- Check the module voltage requirements, signal levels, grounding, and pin assignment.

- Confirm that the antennas are suitable to their intended frequency bands.

### 2. Install Bruce Firmware

Refer to the official Bruce Firmware documentation for your particular controller and installation method.

Official project: https://github.com/pr3y/Bruce

Use a firmware build compatible to your hardware and confirm that the required radio modules are supported.

### 3. Verify module operation

After flashing the firmware:

1. Power on RF Skid.

2. Confirm that the firmware has started correctly.

3. Check that each connected module is detected or available through the relevant menu.

4. Test IR functionality with a device you own.

5. Perform RF experiments using compatible equipment and signals on an authorised test environment.

Menu names and available features will vary between firmware versions.

## 📡 Radio Interfaces

### NRF24L01+

The NRF24L01+ provides a 2.4 GHz radio interface for compatible wireless communication experiments.

Some potential research applications are as follows:

- Study packet-based wireless communication.

- Analyse supported radio configurations and protocols.

- Test communication between compatible development boards.

- Investigate the security properties of devices you own or are authorised to assess.

NRF24L01+ is not a general-purpose Wi-Fi adapter, and cannot automatically communicate with every 2.4 GHz device.

### CC1101

The CC1101 is a configurable sub-GHz transceiver which supports several frequency bands, and various modulation options, depending on the chip configuration and regional requirements.

Some potential research applications are as follows:

- Explore supported sub-GHz signals and modulation.

- Investigate compatible remote-control protocols.

- Test RF communication between development devices.

- Learn about signal characteristics and wireless device security.

The supported frequencies, modulation modes, and operations will vary depending on the module, antenna, firmware, and local regulations.

### Infrared (IR)

The IR interface supports compatible infrared remote-control experimentation.

Some potential applications are as follow:

- Learn how infrared remote protocols work.

- Test remote-control commands with equipment you own.

- Capture and replay compatible commands in a controlled environment.

- Develop and troubleshoot infrared automation projects.

IR operation will require compatible transmitting or receiving hardware and depends on the supported protocol.

## 🔐 Security Research and Pentesting

RF Skid is intended for authorised wireless security testing, education, and hardware research.

Some example use cases are:

- Assess the wireless security of your own devices.

- Explore RF protocol behaviour in a controlled lab.

- Evaluate the resilience of compatible remote-control systems.

- Test infrared automation and device interoperability.

- Document potential vulnerabilities and responsible remediation steps.

RF Skid is a research platform, and is not a guarantee that a device can be intercepted, decoded, cloned, or controlled. The outcome will be dependent on the target technology, protocol, hardware and applicable security mechanisms.

## ⚙️ Configuration and Compatibility

Before using RF Skid, verify:

- Controller compatibility with Bruce Firmware.

- Correct SPI, GPIO, and other required connections.

- NRF24L01+ and CC1101 module compatibility.

- Correct IR transmitter and receiver connections.

- Appropriate antenna selection and placement.

- Firmware and module configuration requirements.

- Applicable frequency allocations and transmission-power limits.

Keep wiring diagrams and hardware revisions documented so the device can be reproduced and maintained.

## ⚠️ Responsible Use

Use RF Skid only on equipment you own or have explicit permission to test.

- Follow applicable radio-spectrum regulations.

- Do not interfere with public-safety, aviation, emergency, or other protected communications.

- Do not access, disrupt, or control third-party devices without authorisation.

- Avoid transmitting on restricted frequencies or at unlawful power levels.

- Follow applicable privacy and data-protection requirements when capturing wireless signals.

You are responsible for ensuring that your experiments are compliant to local laws and regulations.

## 🛣️ Roadmap

Some possible future improvements:

- [ ] Document the exact hardware revision and pinout.

- [ ] Add module detection and diagnostic procedures.

- [ ] Document supported NRF24L01+ features.

- [ ] Document supported CC1101 frequency bands and modulation modes.

- [ ] Add IR hardware and protocol documentation.

- [ ] Publish wiring diagrams and assembly photographs.

- [ ] Add a troubleshooting guide.

- [ ] Maintain a compatibility list for firmware releases.

## 🤝 Contributing

Contributions to improve hardware documentation, compatibility, usability, testing, and responsible security research, are welcome. When submitting an improvement, include relevant hardware details, firmware versions, steps to reproduce, and any applicable test results.

## 📜 Credits

- Bruce Firmware: https://github.com/pr3y/Bruce

- NRF24L01+: Nordic Semiconductor wireless transceiver technology.

- CC1101: Texas Instruments sub-1 GHz RF transceiver technology.

Please refer to the respective projects and manufacturers for their documentation and licensing terms.

## 📄 License

Add a license suitable to your own hardware designs, documentation, and original code. Bruce Firmware and other incorporated components may have their own licensing requirements.

---

RF Skid — Explore the spectrum. Understand the protocols. Test responsibly.

# secbyte-wifi-security-wpa2-wpa3-rogue-ap-embedded-iot-ctf-labs
A practical collection of cybersecurity CTF labs covering wireless network security (Wi-Fi fundamentals, 802.11 monitor mode recon, WPA2 4-way handshakes, WPA3 SAE Dragonfly exchange, Rogue AP / Evil Twin hunting and countermeasures) and embedded IoT hardware security (UART consoles to binary firmware flags).
# Wi-Fi Security, WPA2/WPA3 Key Exchange, Rogue AP Evil Twin Hunt & Embedded IoT CTF Labs

Welcome to the **Wi-Fi Security, WPA2/WPA3 Key Exchange, Rogue AP Evil Twin Hunt & Embedded IoT CTF Lab Collection**. This repository serves as an organized, searchable catalog of practical cybersecurity labs hosted on Learn SecByte.

This collection focuses on radio frequency (RF) recon, 802.11 wireless frame analysis, rogue AP threat hunting, and low-level embedded hardware security—spanning **Wi-Fi Security Fundamentals & Wireless Reconnaissance (Radio signals, silent surveys, monitor mode packet captures, 802.11 frame dissection)**, **WPA2/WPA3 Protocol Security & Attack Simulations (WPA2 4-way handshakes, WPA3 Simultaneous Authentication of Equals SAE, offline dictionary attacks)**, **Rogue AP Detection & Evil Twin Hunting (Evil Twin countermeasures, rogue AP hunts, deauthentication monitoring)**, and **Embedded Systems & IoT Security Fundamentals (UART serial consoles, firmware extraction, smart device network isolation)**.

---

## Lab Collection Index

### 1. Wi-Fi Security Fundamentals, Packet Analysis & Reconnaissance
* **Wireless Fundamentals: Radio to Rogue AP**  
  *Lab Link:* [https://learn.secbyte.org/ctf/wireless-fundamentals-radio-to-rogue-ap](https://learn.secbyte.org/ctf/wireless-fundamentals-radio-to-rogue-ap)  
  *Focus:* Core principles of 802.11 wireless networks, RF channels (2.4 GHz vs. 5 GHz), SSID broadcasting, BSSID mapping, and identifying unauthorized access points.

* **Wireless Reconnaissance: The Silent Survey**  
  *Lab Link:* [https://learn.secbyte.org/ctf/wireless-reconnaissance-the-silent-survey](https://learn.secbyte.org/ctf/wireless-reconnaissance-the-silent-survey)  
  *Focus:* Performing passive wireless site surveys using `airodump-ng` and Kismet, capturing beacon frames, mapping hidden SSIDs, and identifying probe request histories.

* **Wireless Packet Analysis: The Silent AP**  
  *Lab Link:* [https://learn.secbyte.org/ctf/wireless-packet-analysis-the-silent-ap](https://learn.secbyte.org/ctf/wireless-packet-analysis-the-silent-ap)  
  *Focus:* Dissecting 802.11 management, control, and data frames in Wireshark; filtering radio tap headers; and identifying covert wireless AP communications.

* **Wi-Fi Security: From Fundamentals to Attack Simulation**  
  *Lab Link:* [https://learn.secbyte.org/ctf/wi-fi-security-from-fundamentals-to-attack-simulation](https://learn.secbyte.org/ctf/wi-fi-security-from-fundamentals-to-attack-simulation)  
  *Focus:* End-to-end wireless security assessments—simulating client deauthentication attacks, evaluating encryption configurations (WEP, WPA, WPA2, WPA3), and auditing wireless access gateways.

### 2. WPA2/WPA3 Encryption, Handshakes & Hardening
* **WPA2 Security: From Handshake to Hardening**  
  *Lab Link:* [https://learn.secbyte.org/ctf/wpa2-security-from-handshake-to-hardening](https://learn.secbyte.org/ctf/wpa2-security-from-handshake-to-hardening)  
  *Focus:* Capturing WPA2 EAPOL 4-way handshakes, performing dictionary/mask cracking against PMKID and EAPOL packets using Hashcat/Aircrack-ng, and hardening pre-shared keys.

<Image src="image_agent_tag_17859359994462383565" alt="WPA2 4-Way Handshake and Encryption Key Derivation Architecture Diagram" caption="WPA2 4-Way Handshake & Key Derivation Model" />

---

* **WPA3 Security: From SAE to Real-World Defenses**  
  *Lab Link:* [https://learn.secbyte.org/ctf/wpa3-security-from-sae-to-real-world-defenses](https://learn.secbyte.org/ctf/wpa3-security-from-sae-to-real-world-defenses)  
  *Focus:* Analyzing WPA3 Simultaneous Authentication of Equals (SAE) Dragonfly key exchange protocol, evaluating resistance to dictionary attacks, and mitigating transition-mode downgrade risks.

### 3. Rogue Access Points & Evil Twin Threat Hunting
* **Wireless Penetration Testing: From Recon to Rogue AP**  
  *Lab Link:* [https://learn.secbyte.org/ctf/wireless-penetration-testing-from-recon-to-rogue-ap](https://learn.secbyte.org/ctf/wireless-penetration-testing-from-recon-to-rogue-ap)  
  *Focus:* Executing full wireless penetration tests—from initial RF spectrum discovery to deploying rogue access points and inspecting intercepted transit payloads.

* **Wireless Defense: Rogue AP Hunt**  
  *Lab Link:* [https://learn.secbyte.org/ctf/wireless-defense-rogue-ap-hunt](https://learn.secbyte.org/ctf/wireless-defense-rogue-ap-hunt)  
  *Focus:* Utilizing Wireless Intrusion Prevention Systems (WIPS) to hunt rogue APs, tracking signal strength (RSSI) triangulation, and isolating unauthorized physical radios.

<Image src="image_agent_tag_17859359994462380176" alt="Diagram showing how an Evil Twin Access Point intercepts user device network traffic" caption="Evil Twin Rogue Access Point Traffic Interception Topology" />

---

* **Rogue Access Points: Evil Twin Hunt**  
  *Lab Link:* [https://learn.secbyte.org/ctf/rogue-access-points-evil-twin-hunt](https://learn.secbyte.org/ctf/rogue-access-points-evil-twin-hunt)  
  *Focus:* Detecting spoofed SSID/BSSID Evil Twin clones, identifying forced client deauthentication loops, and protecting enterprise devices from connecting to rogue networks.

* **Evil Twin: Rogue AP Detection & Countermeasures**  
  *Lab Link:* [https://learn.secbyte.org/ctf/evil-twin-rogue-ap-detection-countermeasures](https://learn.secbyte.org/ctf/evil-twin-rogue-ap-detection-countermeasures)  
  *Focus:* Implementing 802.11w Protected Management Frames (PMF), enforcing 802.1X Enterprise authentication (EAP-TLS/PEAP), and deploying active countermeasures against Evil Twin attacks.

### 4. Embedded Hardware & IoT Security Fundamentals
* **IoT Fundamentals: Smart Device to Secure Network**  
  *Lab Link:* [https://learn.secbyte.org/ctf/iot-fundamentals-smart-device-to-secure-network](https://learn.secbyte.org/ctf/iot-fundamentals-smart-device-to-secure-network)  
  *Focus:* Securing smart device connectivity, isolating IoT endpoints on dedicated VLANs, auditing local management protocols, and preventing IoT lateral movement.

* **Embedded Systems Security: From UART to Firmware Flags**  
  *Lab Link:* [https://learn.secbyte.org/ctf/embedded-systems-security-from-uart-to-firmware-flags](https://learn.secbyte.org/ctf/embedded-systems-security-from-uart-to-firmware-flags)  
  *Focus:* Interfacing with hardware debug headers (UART serial console), bypassing bootloader password prompts, carving raw firmware binaries, and recovering hidden flags.

---

## Learning Path

### Path A: Wireless Reconnaissance & WPA2/WPA3 Encryption Specialist
1. **RF Recon & Frame Analysis:** Start with [Wireless Fundamentals](https://learn.secbyte.org/ctf/wireless-fundamentals-radio-to-rogue-ap), [Wireless Reconnaissance](https://learn.secbyte.org/ctf/wireless-reconnaissance-the-silent-survey), and [Wireless Packet Analysis](https://learn.secbyte.org/ctf/wireless-packet-analysis-the-silent-ap).
2. **Key Exchange & Encryption:** Master handshakes via [WPA2 Security](https://learn.secbyte.org/ctf/wpa2-security-from-handshake-to-hardening) and [WPA3 Security](https://learn.secbyte.org/ctf/wpa3-security-from-sae-to-real-world-defenses).

### Path B: Rogue AP Threat Hunter & Wireless Defender
1. **Penetration Testing & Hunt:** Execute audits via [Wireless Penetration Testing](https://learn.secbyte.org/ctf/wireless-penetration-testing-from-recon-to-rogue-ap) and [Wireless Defense: Rogue AP Hunt](https://learn.secbyte.org/ctf/wireless-defense-rogue-ap-hunt).
2. **Evil Twin Mitigation:** Triage rogue clones in [Rogue Access Points: Evil Twin Hunt](https://learn.secbyte.org/ctf/rogue-access-points-evil-twin-hunt) and [Evil Twin: Detection & Countermeasures](https://learn.secbyte.org/ctf/evil-twin-rogue-ap-detection-countermeasures).

### Path C: Embedded Hardware & IoT Security Analyst
1. **Smart Network Isolation:** Secure IoT environments in [IoT Fundamentals: Smart Device to Secure Network](https://learn.secbyte.org/ctf/iot-fundamentals-smart-device-to-secure-network).
2. **Hardware Debugging & Firmware:** Intercept hardware interfaces in [Embedded Systems Security: From UART to Firmware Flags](https://learn.secbyte.org/ctf/embedded-systems-security-from-uart-to-firmware-flags).

---

## How to Use the Labs

1. Select a practice scenario from the **Lab Collection Index**.
2. Click the corresponding direct link to launch the exercise environment hosted on Learn SecByte.
3. Review scenario directives, 802.11 Wireshark packet captures (`.pcap`/`.cap`), WPA2/WPA3 handshake files, or UART terminal logs.
4. Filter radio tap headers, extract EAPOL 4-way handshakes, crack PMKID hashes with Hashcat, detect rogue AP RSSI anomalies, or bypass UART bootloader consoles to capture flags.

---

## Target Audience

* **Wireless Security Auditors & Pentesters:** Conduct RF spectrum surveys, execute WPA2/WPA3 handshake assessments, capture PMKID hashes, and deploy rogue AP simulations.
* **SOC Analysts & WIPS Security Engineers:** Detect Evil Twin AP clones, monitor deauthentication floods, enforce 802.11w PMF, and isolate rogue physical radios.
* **Embedded & Hardware Security Researchers:** Interface with hardware UART headers, extract firmware images, and audit IoT smart device isolation rules.
* **Cybersecurity Students:** Acquire practical hands-on experience in 802.11 wireless frame mechanics, WPA2/WPA3 key derivation, and embedded hardware security.

---

## Disclaimer

All lab links provided in this repository direct to official training environments hosted on Learn SecByte. All materials and exercises are provided strictly for educational purposes, defensive skill building, and authorized security research. Unauthorized wireless packet interception, deauthentication jamming, or rogue AP deployment against external networks without explicit consent is strictly prohibited.

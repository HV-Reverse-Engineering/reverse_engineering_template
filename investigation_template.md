# Reverse Engineering Investigation Template

## 1. Target Overview

- Product Name:
- Model / Variant:
- Manufacturer:
- Category: (e.g., router, IoT device, appliance, controller)
- Target Type:
  - [ ] Linux-based Embedded System
  - [ ] MCU-based Device
  - [ ] Hybrid / Unknown
- Acquisition Source: (purchase, client-provided, found, etc.)
- Date Acquired:
- Investigator(s):

---

## 2. Legal & Ethical Considerations

- Ownership Verified: [ ] Yes [ ] No
- Authorization to Reverse Engineer: [ ] Yes [ ] No
- Applicable Laws / Restrictions: (DMCA, regional laws, NDA, etc.)
- Notes:

---

## 3. External Intelligence & Open-Source Research

### 3.1 Public Documentation

- Product manuals:
- Datasheets:
- Marketing material:
- Patents:
- Certifications:

### 3.2 FCC / Regulatory Sources

- FCC ID:
- fcc.io / FCC Database Links:
- Internal Photos Available: [ ] Yes [ ] No
- External Photos Available: [ ] Yes [ ] No
- Schematics Available: [ ] Yes [ ] No
- Test Reports / Block Diagrams:
- Notes from FCC Documents:

### 3.3 Online Intelligence

- Forums / Communities:
- GitHub Repositories:
- Prior Research / Writeups:
- Known Vulnerabilities / CVEs:
- Similar Devices / Chipsets:

---

## 4. Physical Inspection & Teardown

### 4.1 External Inspection

- Enclosure type:
- Labels / Stickers:
- Serial numbers:
- Ports / Connectors:
- Buttons / LEDs:

### 4.2 Teardown Notes

- Fasteners type:
- Tamper resistance:
- Shielding:
- Board markings:
- Revision numbers:

### 4.3 Photographic Evidence

- External photos:
- Internal photos:
- PCB top:
- PCB bottom:
- Close-ups (IC markings, connectors):

---

## 5. Hardware Analysis

### 5.1 Major Components

| Component | Manufacturer | Part Number | Function | Notes |
|----------|--------------|-------------|----------|-------|
| SoC / MCU | | | | |
| Flash | | | | |
| RAM | | | | |
| Power IC | | | | |
| Radio | | | | |

### 5.2 MCU / SoC Details

- Architecture: (ARM, MIPS, RISC-V, etc.)
- Core(s):
- Clock source:
- Secure boot present: [ ] Yes [ ] No [ ] Unknown
- TrustZone / Security features:

---

## 6. Interfaces & Debug Access

### 6.1 Identified Interfaces

| Interface | Location | Voltage | Status | Notes |
|-----------|----------|---------|--------|-------|
| UART | | | | |
| JTAG | | | | |
| SWD | | | | |
| SPI | | | | |
| I2C | | | | |
| USB | | | | |
| Ethernet | | | | |

### 6.2 Debug Access Findings

- Console access: [ ] Yes [ ] No
- Authentication required:
- Bootloader interaction:
- Lock bits / fuses status:

---

## 7. Firmware & Software Analysis

### 7.1 Firmware Acquisition

- Source:
  - [ ] Flash dump
  - [ ] Vendor update
  - [ ] Network capture
  - [ ] Filesystem extraction
- Firmware version:
- Hashes (MD5/SHA256):

### 7.2 Firmware Structure

- Bootloader:
- Kernel:
- Filesystem type:
- Compression / encryption:
- Update mechanism:

### 7.3 Operating System (if applicable)

- OS type:
- Kernel version:
- Init system:
- Shell availability:
- Package manager:

---

## 8. Storage & Memory Analysis

- Flash type:
- Dump method:
- Encryption detected: [ ] Yes [ ] No
- Wear leveling:
- Partitions identified:

---

## 9. Communications & Protocols

- Wired protocols:
- Wireless protocols:
- Encryption used:
- Authentication mechanisms:
- Cloud services involved:

---

## 10. Security Features & Protections

- Secure boot:
- Code signing:
- Firmware encryption:
- Debug lockout:
- Anti-tamper mechanisms:

---

## 11. Attack Surface Summary

| Surface | Description | Risk Level | Notes |
|---------|-------------|------------|-------|
| Physical | | | |
| Network | | | |
| Firmware | | | |
| Supply Chain | | | |

---

## 12. Tools Used

- Hardware tools:
- Software tools:
- Custom scripts:
- Test equipment:

---

## 13. Findings & Observations

- Key discoveries:
- Unexpected behavior:
- Anomalies:
- Interesting artifacts:

---

## 14. Open Questions & Next Steps

- Unknown components:
- Blocked progress areas:
- Planned experiments:
- Required tools or access:

---

## 15. References & Artifacts

- Datasheets:
- Firmware files:
- Logic analyzer captures:
- Notes:
- Repository links:

---

## 16. Timeline / Activity Log

| Date | Activity | Result | Notes |
|------|----------|--------|-------|
| | | | |

---

## 17. Final Notes

- Summary:
- Risk assessment: riscy
- Recommendations:

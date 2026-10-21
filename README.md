# Laptop Repair, Troubleshooting & Refurbishment Portfolio

**Jamal Ramsey**  
**IT Enthusiast | Aspiring IT Support / Desktop Support Technician**  
**Project timeline:** July–October 2026  
**Portfolio focus:** Hardware diagnostics • Windows deployment • Component replacement • BIOS/UEFI • Driver troubleshooting • Refurbishment

> **Portfolio purpose:** This repository documents my hands-on laptop troubleshooting, repair, configuration, and refurbishment experience. The projects are presented chronologically, including successful repairs, incomplete investigations, and systems prepared for resale. An unresolved fault is labeled as such; a successful power-on is not treated as proof that every underlying issue was fixed.

## Quick Navigation

- [Portfolio Overview](#portfolio-overview)
- [Technical Skills Demonstrated](#technical-skills-demonstrated)
- [Troubleshooting Methodology](#troubleshooting-methodology)
- [Chronological Project Index](#chronological-project-index)
- [Detailed Project Documentation](#detailed-project-documentation)
- [Lessons Learned](#lessons-learned)
- [Interview Talking Points](#interview-talking-points)
- [Evidence and Documentation](#evidence-and-documentation)
- [Safety, Privacy and Scope](#safety-privacy-and-scope)

## Portfolio Overview

This portfolio began with hands-on work on laptops for my **nephew and niece**, then expanded to used and refurbished devices from HP, Acer, ASUS, Dell, and Apple. The work includes investigating incompatible SSD interfaces, upgrading memory and storage, replacing internal batteries, reinstalling Windows 11, resolving GPU-driver detection issues, testing hardware with vendor diagnostics, and investigating no-power/no-POST conditions.

**What this portfolio demonstrates:**

- A repeatable, evidence-based troubleshooting process.
- Comfort opening and inspecting laptops and handling replaceable components.
- Windows 11 installation, setup, driver checks, and post-install verification.
- Understanding the difference between a symptom, a hypothesis, a diagnostic test, and a confirmed fix.
- The ability to document findings for an IT support ticket, a technician handoff, or a future repair attempt.

**Status terminology**

| Status | Meaning |
|---|---|
| **Completed repair** | A specific fault was addressed and the relevant result was verified. |
| **Refurbished / prepared for resale** | The system was configured and checked for its intended next use; this does not imply every component was repaired. |
| **Diagnostic investigation** | Troubleshooting was performed but the root cause or resolution was not confirmed. |
| **Configuration / planned lab** | Setup or planning work; unperformed steps are not represented as completed. |

## Technical Skills Demonstrated

| Skill area | Hands-on examples |
|---|---|
| **Hardware identification** | Model identification, component inspection, RAM slots, SATA/NVMe storage, internal battery connectors |
| **Storage diagnostics** | NVMe vs. M.2 SATA compatibility, SSD testing in another laptop, failed HDD removal, salvaged SSD reuse |
| **Memory** | RAM upgrade, reseating modules, testing known-good memory and separate slots |
| **Power systems** | Internal battery replacement, AC-only tests, charging LED observation, power drains, battery reset procedures |
| **BIOS / UEFI** | BIOS update to F.79, boot/drive detection checks, Windows+B and Windows+V recovery attempts, HP UEFI diagnostics |
| **Windows deployment** | Windows 11 USB installation, clean installations, first-run setup, Device Manager checks, configuration for resale |
| **Driver troubleshooting** | NVIDIA GTX 1650 detection, Microsoft Basic Display Adapter / Code 10 investigation, Dell audio-device troubleshooting |
| **Health verification** | HP CPU, memory, system-board and SSD tests; battery runtime checks; Windows Device Performance & Health |
| **Thermal troubleshooting** | Interpreting a BIOS System Temperature (90D) warning, fan observation, recognizing limits of idle-temperature readings |
| **Documentation** | Recording symptoms, tests performed, observations, outcomes, limitations, and next actions |

## Troubleshooting Methodology

I approach laptop repair as a sequence of testable questions rather than immediately replacing parts.

```text
1. Identify the device and the reported symptom
                 |
                 v
2. Check power, connections, visible damage, and recent changes
                 |
                 v
3. Form a limited set of likely causes
                 |
                 v
4. Change one variable at a time (charger, battery, RAM, drive, driver)
                 |
                 v
5. Observe and record what actually changes
                 |
                 v
6. Apply a targeted fix or document an unresolved diagnosis
                 |
                 v
7. Verify the result and document remaining risks
```

Examples:

- **SSD not recognized:** Test the SSD in another system before declaring the drive defective.
- **No POST:** Test RAM modules and slots independently before assuming memory is the cause.
- **Driver issue after Windows installation:** Distinguish a missing or incorrect driver from a failed physical component.
- **Charging light present but no startup:** Do not assume that an illuminated LED proves the adapter, battery, or motherboard is fully functional.

## Chronological Project Index

> Projects 1 and 2 are intentionally the family laptops. Project 2 is the gray HP-dk series laptop with damaged/missing S and O keycaps; its full model suffix and any additional repairs remain unverified. Remaining entries follow the approximate project timeline; several projects overlapped.

| # | Approx. period | Device / project | Primary focus | Documented status |
|---|---|---|---|---|
| 1 | Jul–Aug 2026 | **HP 14-fq0013dx — nephew's laptop** | M.2 compatibility, SSD, RAM, BIOS, Windows | Hardware upgrade / configuration |
| 2 | 2026 | **HP-dk series — niece's gray laptop** | NVMe compatibility cross-test; missing S/O keycaps | SSD test confirmed; keycap repair not confirmed |
| 3 | Aug 2026 | MacBook Air | No-power / no-charge diagnosis | Unresolved investigation |
| 4 | Aug 2026 | ASUS laptop / VivoBook-type | Battery diagnosis and replacement | Completed battery repair |
| 5 | Aug 2026 | Acer Aspire 3 A317 | Windows configuration, remote lab planning | Configuration / planned lab |
| 6 | Aug–Oct 2026 | HP Pavilion Gaming 16 — Unit A | Windows, battery, GPU drivers, UEFI tests, thermals | Refurbished; thermal history noted |
| 7 | Aug–Sep 2026 | HP Pavilion Gaming 16 — Unit B | No POST, RAM isolation, BIOS recovery | Unresolved investigation |
| 8 | Aug–Sep 2026 | HP 17-by series | HDD removal, NVMe reuse, battery, Windows 11 | Refurbished / resale preparation |
| 9 | Aug 2026 | Dell laptop | Audio-device detection | Diagnostic investigation |
| 10 | Sep 2026 | Dell Latitude 5320 2-in-1 — Unit 1 | Windows 11, NVMe, touchscreen | Refurbished and sold |
| 11 | Sep 2026 | Dell Latitude 5320 2-in-1 — Unit 2 | Windows, hardware verification | Refurbished and sold |
| 12 | Sep 2026 | Acer Swift 1 14-inch | Windows setup and functional checks | Refurbished and sold |
| 13 | Sep–Oct 2026 | Acer Aspire 3 17.3-inch | Windows configuration | Refurbished and sold |
| 14 | Sep–Oct 2026 | ASUS VivoBook 14 | Windows and battery/runtime checks | Refurbished and sold |
| 15 | Oct 2026 | Acer Aspire 7 A717-72G-53P7 | Charging and no-power troubleshooting | Unresolved investigation |

## Detailed Project Documentation

### 01 — HP 14-fq0013dx: Nephew's Laptop

**Period:** Late July–August 2026  
**Primary goal:** Improve the usability and storage of a laptop originally equipped with 64 GB eMMC storage.  
**Status:** Storage and RAM upgrade work documented; Windows migration/configuration investigated.

**Starting condition**

- Factory 64 GB eMMC storage.
- Need for additional usable storage and memory.
- An internal M.2 slot required interface compatibility verification.

**Actions performed**

1. Opened the laptop and inspected the internal M.2 slot.
2. Attempted to install a **Patriot P300 256 GB NVMe SSD**.
3. Observed that the SSD was not detected in BIOS after multiple attempts.
4. Tested the same Patriot SSD in a separate HP laptop, where it worked.
5. Determined that this HP 14-fq configuration needed an **M.2 SATA** drive rather than that NVMe model.
6. Updated BIOS to **F.79**.
7. Installed a **Timetec 256 GB M.2 SATA SSD**.
8. Observed approximately **238 GB** usable capacity in Windows.
9. Initialized the drive as **GPT** and created/formatted an **NTFS** volume.
10. Upgraded memory to **8 GB RAM**.
11. Investigated Windows migration/setup options and supplemental microSD storage.

**Result / evidence**

- The Patriot NVMe was validated in another laptop, reducing the likelihood of a defective SSD.
- The replacement SATA SSD was recognized and initialized in Windows.
- The system's RAM was upgraded to 8 GB.

**Skills demonstrated:** Interface compatibility testing, controlled component substitution, BIOS update, laptop disassembly, RAM upgrade, Disk Management, GPT/NTFS.

**Key lesson:** **M.2 describes a form factor, not a guarantee that every M.2 SSD interface is supported.**

<img width="1182" height="665" alt="26618968-9C07-4EE2-AA0E-2F80D76AB7B4_1_105_c" src="https://github.com/user-attachments/assets/30c80c90-2708-4729-9ff9-8a8417701518" />

<img width="768" height="1024" alt="B1091C3B-2AB4-4B9E-804E-5D22625B2DE2_1_105_c" src="https://github.com/user-attachments/assets/eb56f634-835b-4587-99c7-69840f9967a0" />

<img width="768" height="1024" alt="B8848BE4-59B1-4F28-A083-F3154663C878_1_105_c" src="https://github.com/user-attachments/assets/dce024d5-cb65-42de-89f1-c126f7d54dc4" />

<img width="1182" height="665" alt="5F0A1A10-DF81-4E3E-98DF-473A01CCE5F0_1_105_c" src="https://github.com/user-attachments/assets/d31b5dbe-1617-4e2f-b705-35f785365122" />

<img width="768" height="1024" alt="AFE5C594-8F48-4713-825A-327C90846EEC_1_105_c" src="https://github.com/user-attachments/assets/c90ad284-41a8-4e6d-9114-1b5538d9128e" />


<img width="1182" height="665" alt="B00A33B5-F8DE-4760-B86A-5695C45EA9DE_1_105_c" src="https://github.com/user-attachments/assets/aef9b598-1a9e-4dc2-a2e7-b14431d76931" />


<img width="1182" height="665" alt="32D364C8-9410-4B15-9E6C-F0AE558F9CE2_1_105_c" src="https://github.com/user-attachments/assets/dd22d46a-c682-4d75-8de3-9ac9ba024409" />


<img width="1024" height="768" alt="A173147F-8285-4F14-9B01-81CE24735E39_1_105_c" src="https://github.com/user-attachments/assets/a0ece11a-bd4a-4220-9602-4e80d9abf58f" />



---

### 02 — HP-dk Series: Niece's Gray Laptop — SSD Cross-Test and Keyboard Assessment

**Period:** 2026 (exact date to confirm)  
**Model:** HP-dk series, gray chassis; full product number not yet verified  
**Status:** Used for a successful NVMe SSD cross-test; damaged/missing keycaps identified; keyboard repair not yet documented as completed.

**Initial observations**

- This is my niece's gray HP-dk laptop, distinct from my nephew's HP 14-fq0013dx.
- The **S and O keycaps** were visibly missing or damaged in a photo comparing this laptop with the blue HP-fq.
- I considered whether donor keycaps or an entire keyboard could be transferred between the two laptops, but compatibility was **not established**.

**Troubleshooting and component verification**

1. During Project 01, the Patriot P300 256 GB M.2 NVMe SSD was not recognized in the HP 14-fq.
2. I tested that SSD in the HP-dk laptop, where it was recognized, helping demonstrate that the SSD itself was functional.
3. This comparative test helped isolate the original problem to the HP-fq's storage-interface compatibility rather than an inherently defective SSD.
4. I visually compared the two laptops' keyboard layouts and assessed the possibility of replacing only the missing S/O keycaps.
5. I did **not** assume that similarly shaped keys share the same scissor hinges or retaining clips; a close-up inspection and part compatibility check would be required before removal.

**Skills demonstrated:** Known-good system/component substitution, SSD fault isolation, M.2 NVMe compatibility testing, visual keyboard assessment, avoiding unverified replacement-part compatibility.

**Outcome:** The HP-dk served as a functional comparison system for the NVMe SSD. The keyboard/keycap issue remained an assessment, **not a confirmed repair**.

<img width="1182" height="665" alt="27748CA7-C093-4E02-90A6-AF9E2E318130_1_105_c" src="https://github.com/user-attachments/assets/91d34258-7049-47e9-9d3f-27ccd7253f58" />


<img width="1182" height="665" alt="CB821A97-E9F8-4AA1-BD06-D7C69BA37C47_1_105_c" src="https://github.com/user-attachments/assets/13c7323e-33a8-4f88-8389-435072bd1043" />


<img width="2208" height="1242" alt="91A5B95E-F850-4523-9E0E-80595240B99D_1_201_a" src="https://github.com/user-attachments/assets/929188ec-e80f-418d-9f3e-80ff86025bfa" />


<img width="1182" height="665" alt="BDA998F6-72B9-4454-AE5D-325820748966_1_105_c" src="https://github.com/user-attachments/assets/f0000cb0-1f8d-4e40-9caa-774940a134ca" />







**Suggested evidence:** Side-by-side photo of the gray HP-dk and blue HP-fq, close-ups of missing keycaps, and a storage-detection screenshot if available. Avoid posting serial numbers or personal information.

---

### 03 — MacBook Air: No-Power / No-Charge Diagnosis

**Period:** August 2026  
**Status:** Diagnostic investigation; no confirmed repair.

**Reported symptom:** A used MacBook Air showed no apparent response to power or charging.

**Actions performed**

- Connected a charger and observed the system's response.
- Retested with another charger available to me.
- Considered battery, charging-port/USB-C power path, and board-level power faults.

**Result:** The MacBook Air did not reach a confirmed working state during this investigation. No specific failed component was proven.

**Skills demonstrated:** Initial power triage, adapter substitution, hypothesis formation, documenting an unresolved issue.

**Key lesson:** A no-power symptom alone cannot identify a failed motherboard or battery.

---

### 04 — ASUS Laptop / VivoBook-Type System: Battery Replacement

**Period:** August 2026  
**Status:** Completed battery repair.

**Symptoms**

- Unusual behavior when AC power was connected, including automatic power-on behavior.
- Amber/orange charging indicator behavior.
- Concerns about the existing internal battery.

**Actions performed**

1. Opened the chassis and located the internal battery.
2. Disconnected and removed the battery, taking care with its connector.
3. Compared behavior with AC power and the battery disconnected.
4. Replaced the battery.
5. Verified charging and unplugged runtime.

**Verified result**

- Battery reached approximately **99%** charge.
- Laptop ran for **more than five hours** unplugged.
- Laptop operated normally without continuous AC power.

**Skills demonstrated:** Battery isolation, safe connector handling, battery replacement, functional verification.

**Key lesson:** A replacement is only a confirmed fix when the original symptom no longer occurs during relevant testing.

---

### 05 — Acer Aspire 3 A317: Windows Configuration and Remote-Lab Planning

**Period:** August 2026  
**Status:** Configuration investigation and planned lab use.

**Actions / planning documented**

- Identified the Acer A317 laptop and researched appropriate charger requirements.
- Investigated Windows S Mode and its implications for application installation.
- Discussed standard Windows configuration.
- Planned TeamViewer use for remote access and troubleshooting exercises.

**Result:** The record supports configuration planning and investigation; it does not establish that every proposed TeamViewer lab or S Mode change was completed.

**Skills demonstrated:** Hardware identification, Windows edition/configuration awareness, remote-support lab planning.

---

### 06 — HP Pavilion Gaming 16: Unit A

**Period:** August–October 2026  
**Status:** Extensive refurbishment and diagnostic work; historical thermal warning not conclusively resolved.

**Initial issues**

- Battery did not hold power; the system shut down when unplugged.
- Windows required reset/reinstallation work.
- Graphics-driver detection problems occurred after OS installation.

**Actions performed**

1. Replaced the battery and later verified unplugged operation.
2. Used Windows 11 installation media for a clean installation.
3. Observed fan behavior during installation and updates.
4. Ran HP UEFI diagnostics:
   - CPU: **passed**.
   - Memory: **passed**.
   - System board: **passed**.
   - SSD SMART: **passed**.
   - SSD Short DST: **passed**.
5. Investigated NVIDIA GPU detection, including **Microsoft Basic Display Adapter / Code 10** behavior.
6. Removed/reinstalled graphics drivers and verified that Windows recognized the **NVIDIA GTX 1650**.
7. Updated BIOS and system software.
8. Investigated a remaining **Detection Verification / Code 28** device; an audio-related driver was considered, not conclusively identified.
9. Reviewed battery diagnostics, including an initial calibration-required indication.
10. Investigated a recorded **System Temperature (90D) — Thermal Shutdown** warning.
11. Checked fan behavior and observed a GPU idle temperature around the low-50°C range.
12. Discussed further CPU package-temperature testing using tools such as HWiNFO or Core Temp.

**Result / limitations**

- Windows 11 was installed and the GTX 1650 was recognized.
- Battery-powered operation was demonstrated.
- Multiple HP UEFI diagnostic tests passed.
- The recorded thermal warning was **not conclusively cleared by load-temperature testing**. A low idle GPU temperature does not establish safe CPU thermals under sustained load.
- The laptop was later sold as a refurbished device; this portfolio does not imply the thermal warning had a proven root-cause fix.

**Skills demonstrated:** OS deployment, Device Manager troubleshooting, GPU drivers, BIOS updates, vendor diagnostics, battery verification, thermal risk documentation.

**Key lesson:** A passing quick diagnostic or successful boot does not automatically rule out intermittent thermal or power issues.

---

### 07 — HP Pavilion Gaming 16: Unit B

**Period:** August–September 2026  
**Status:** Unresolved no-POST investigation.

**Symptoms**

- Brief keyboard/power illumination.
- No successful POST or boot screen.
- Charger indicator changed color during some tests.

**Actions performed**

1. Installed/replaced the internal battery.
2. Tested with AC power and the battery disconnected.
3. Performed a power drain.
4. Reseated RAM.
5. Tested memory modules separately.
6. Tested both memory slots and known-good RAM.
7. Attempted BIOS recovery using **Windows + B** and **Windows + V**.
8. Inspected the motherboard, connectors, cooling system, and storage-bay area.
9. Distinguished a brief keyboard-light flash from a confirmed diagnostic blink code.

**Result:** No successful POST was achieved. Memory was tested extensively, making a simple RAM seating problem less likely; motherboard power delivery, firmware, and other hardware causes remained possibilities, not proven diagnoses.

**Skills demonstrated:** No-POST triage, component isolation, BIOS recovery procedures, board inspection, evidence-based escalation.

**Key lesson:** Record negative tests and stop short of claiming a motherboard failure without confirming it.

---

### 08 — HP 17-by Series: Storage Reuse and Windows 11 Refurbishment

**Period:** August–September 2026  
**Status:** Refurbished / prepared for resale.

**Known configuration**

- 17.3-inch HP laptop.
- Intel Core **i5-8250U**.
- **8 GB RAM**.

**Actions performed**

1. Removed a failed **1 TB HDD**.
2. Reused a salvaged **256 GB NVMe SSD** from another damaged computer.
3. Installed a replacement **HT03XL battery**.
4. Clean-installed **Windows 11 Home**.
5. Completed Windows updates/configuration.
6. Checked Windows **Device Performance & Health**.
7. Prepared the system for resale.

**Result:** The laptop was configured with replacement storage, battery, and Windows 11, and was prepared/listed for resale. Sale status is not claimed here.

**Skills demonstrated:** Hardware reuse, HDD-to-SSD replacement, battery installation, OS deployment, post-install checks.

**Key lesson:** Salvaged components can be useful when their health and compatibility are checked first.

---

### 09 — Dell Laptop: “No Audio Device Found”

**Period:** August 2026  
**Status:** Diagnostic investigation; final resolution not confirmed.

**Symptoms**

- Windows displayed **“No audio device found.”**
- Internal speakers did not function.
- Audio was available through a headset.

**Actions performed**

- Investigated the audio device in Device Manager.
- Uninstalled the audio driver/device as part of troubleshooting.
- Consulted Dell support documentation.
- Compared headset and internal-speaker behavior.

**Result:** The investigation helped narrow the distinction between Windows device detection, driver configuration, and output hardware; a confirmed final fix was not documented.

**Skills demonstrated:** Peripheral troubleshooting, Windows driver management, vendor documentation use.

---

### 10 — Dell Latitude 5320 2-in-1: Unit 1

**Period:** September 2026  
**Status:** Refurbished and sold.

**Actions performed**

- Worked with the internal **128 GB NVMe SSD**.
- Booted Windows installation media.
- Performed a clean **Windows 11** installation.
- Completed first-run configuration.
- Checked touchscreen and convertible functionality.
- Prepared the device for Marketplace resale.

**Result:** Device was sold following refurbishment and functionality checks.

**Skills demonstrated:** Windows installation, business-class laptop setup, touchscreen verification, resale preparation.

---

### 11 — Dell Latitude 5320 2-in-1: Unit 2

**Period:** September 2026  
**Status:** Refurbished and sold.

**Actions performed**

- Completed Windows installation/configuration.
- Performed general hardware verification.
- Checked touchscreen/2-in-1 operation.
- Prepared and sold the second Latitude 5320.

**Result:** Working on two systems of the same model provided opportunities to compare normal operation and repeat the configuration workflow.

**Skills demonstrated:** Repeatable deployment, functional verification, standardized refurbishment.

---

### 12 — Acer Swift 1 14-inch: Windows Refurbishment

**Period:** September 2026  
**Status:** Refurbished and sold.

**Known configuration:** Approximately **4 GB RAM / 128 GB storage**.

**Actions performed**

- Configured Windows 11.
- Performed general functionality checks.
- Prepared the laptop for resale.

**Result:** Device sold after configuration and preparation.

**Skills demonstrated:** Supporting lower-spec hardware, Windows setup, pre-sale functional checks.

---

### 13 — Acer Aspire 3 17.3-inch: Refurbishment

**Period:** September–October 2026  
**Status:** Refurbished and sold.

**Actions performed**

- Identified and reviewed system specifications.
- Completed Windows setup/configuration.
- Checked general functionality.
- Prepared the device for Marketplace.

**Result:** Device sold following preparation.

**Skills demonstrated:** Hardware inventory, Windows configuration, refurbishment workflow.

---

### 14 — ASUS VivoBook 14: Windows and Resale Preparation

**Period:** September–October 2026  
**Status:** Refurbished and sold.

**Actions performed**

- Completed Windows 11 setup.
- Checked general hardware operation.
- Reviewed battery/runtime behavior in connection with ASUS laptop work.
- Prepared and sold the laptop.

**Important scope note:** The documented ASUS battery replacement in Project 04 may relate to this same device; this portfolio does **not** assume two distinct ASUS battery repairs without model-level confirmation.

**Skills demonstrated:** Windows configuration, functional checks, battery verification, resale preparation.

---

### 15 — Acer Aspire 7 A717-72G-53P7: No-Power / Charging Diagnosis

**Period:** October 2026  
**Status:** Unresolved diagnostic investigation; no confirmed repair.

**Device identification**

- **Model:** Acer Aspire 7 A717-72G-53P7.
- **Regulatory model:** N17C3.
- **Manufacture date on label:** 2018-09-19.
- **Adapter requirement on laptop:** **19 V DC, 7.1 A (~135 W)**.
- **Battery:** Acer **AC14B8K**, 15.2 V nominal, 48 Wh typical.
- **Visible internal components:** Toshiba 2.5-inch SATA HDD, RAM module, dual-fan cooling assembly.

**Symptoms**

- No successful power-on or display.
- Charging indicator initially showed solid amber, then blinking amber.
- After battery reconnection, solid amber returned temporarily before blinking resumed.

**Actions performed**

1. Checked the laptop's adapter specifications and obtained an aftermarket **HSXIRQA** charger labeled **19 V / 7.1 A**.
2. Observed charging-light behavior over time.
3. Attempted a power drain.
4. Opened the chassis and identified the battery, connector, RAM, and drive.
5. Disconnected the internal battery and attempted AC-only startup.
6. Observed no LEDs and no startup during that battery-disconnected test.
7. Reconnected the battery and observed solid, then blinking, amber behavior.
8. Used the laptop's battery-reset pinhole procedure.
9. Investigated charger output, DC jack, battery, and motherboard charging circuitry as possible causes.

**Result / limitations**

- No successful startup was achieved.
- **No multimeter was available**, so the adapter's actual voltage and load performance were not measured.
- The replacement charger's label matched the laptop's nominal power requirement, but the charger was not independently validated under load.
- A battery-disconnected no-boot result does not by itself prove motherboard failure.
- A blinking amber light was **not treated as a verified diagnostic fault code**.
- The decision was made to stop investing in replacement parts until the power source could be verified.

**Next diagnostic step:** Test with a known-good compatible 19 V, 135 W adapter, then inspect/test the DC input path if symptoms persist.

**Skills demonstrated:** Adapter specification matching, internal inspection, battery isolation, reset procedures, symptom tracking, safe escalation.

**Key lesson:** Avoid replacing expensive components based only on charging LED behavior.

---

## Lessons Learned

1. **Confirm compatibility, not just physical fit.** M.2 SATA and NVMe can look similar while using different interfaces.
2. **Use known-good parts to isolate faults.** Testing an SSD or RAM module in a second system can prevent unnecessary purchases.
3. **A successful boot is not a complete health check.** Battery, SSD, GPU, thermal, and driver checks matter.
4. **Separate symptoms from conclusions.** A charging LED, error code, or brief power flash is evidence, not a diagnosis by itself.
5. **Document unresolved issues.** A clear diagnostic history makes escalation and future repair attempts more efficient.
6. **Treat reused hardware carefully.** Confirm condition and compatibility before using salvaged parts.
7. **Protect user data.** Only reinstall, erase, or repurpose storage with appropriate authorization; do not publish identifying information.

## Interview Talking Points

### Example 1 — Compatibility Troubleshooting

**Question:** “Tell me about a time you diagnosed a hardware issue.”

**Answer outline (HP 14-fq):**

- **Situation:** An M.2 NVMe SSD was not detected after installation.
- **Task:** Determine whether the problem was the SSD or the laptop's compatibility.
- **Action:** Retested the SSD in a separate HP system, confirmed it worked, reviewed the storage interface requirement, and installed an M.2 SATA alternative.
- **Result:** The replacement SATA drive was recognized and configured in Windows, avoiding the mistaken conclusion that the original NVMe SSD was defective.

### Example 2 — Windows and Driver Troubleshooting

**Question:** “Describe your Windows deployment experience.”

**Answer outline (HP Pavilion Gaming 16, Unit A):**

- Used Windows 11 USB installation media for a clean deployment.
- Used Device Manager and driver reinstalls to troubleshoot GPU recognition.
- Confirmed the GTX 1650 was recognized and ran HP UEFI component diagnostics.
- Kept the thermal-shutdown history documented rather than assuming it was fixed by a successful boot.

### Example 3 — A Problem You Couldn't Fully Fix

**Question:** “What do you do when troubleshooting doesn't resolve the issue?”

**Answer outline (HP Pavilion Gaming 16, Unit B):**

- Documented the no-POST symptom.
- Isolated RAM modules and slots and attempted vendor BIOS recovery.
- Recorded which tests produced no change.
- Identified next-level possibilities without claiming a proven board failure.
- Explained when additional diagnostic equipment or escalation would be appropriate.

### Example 4 — Cost-Conscious Troubleshooting

**Question:** “How do you avoid unnecessary replacement costs?”

**Answer outline (Acer Aspire 7):**

- Matched the adapter's required voltage/current before testing.
- Compared behavior with the battery connected and disconnected.
- Used available reset procedures.
- Recognized that the charger had not been electrically verified.
- Deferred battery or motherboard purchases until the input power source could be tested.

## Evidence and Documentation

To make this portfolio stronger during an interview, attach **real evidence only**. Suggested repository structure:

```text
laptop-repair-troubleshooting-portfolio/
├── README.md
├── assets/
│   ├── hp-14-fq/
│   ├── asus-battery/
│   ├── hp-gaming-unit-a/
│   ├── hp-gaming-unit-b/
│   ├── dell-latitude-5320/
│   └── acer-aspire-7/
└── docs/
    ├── diagnostic-template.md
    └── project-notes.md
```

**Suggested evidence per project**

- **Before:** A photo of the device or a screenshot of the symptom.
- **Diagnostics:** BIOS screen, vendor test result, Device Manager status, or storage layout.
- **Action:** A photo of the replaced component or installation step.
- **After:** Successful boot, device detection, battery runtime, or another relevant verified result.
- **Status:** Completed, partially completed, planned, or unresolved.

Use relative Markdown image paths when evidence is available:

```markdown
![HP 14-fq storage upgrade](assets/hp-14-fq/storage-upgrade.jpg)
```

Do **not** add a placeholder image link as if the file exists; upload the corresponding image first.

### Reusable Repair Ticket Template

```markdown
## Device / Ticket ID
- Manufacturer and model:
- Date:
- Reported issue:
- Initial condition:

## Diagnostic Steps
1.
2.
3.

## Observations
-

## Root Cause
- Confirmed / suspected / unknown:

## Resolution or Next Action
-

## Verification
- Test performed:
- Result:

## Notes / Risks
-
```

## Safety, Privacy and Scope

- All work described is hands-on learning, personal refurbishment, or authorized device work; it is **not** presented as paid enterprise IT employment.
- Power adapters, battery packs, and exposed circuitry require careful handling. Disconnect power before opening equipment and stop if a battery is swollen, damaged, or overheating.
- Do not publish device serial numbers, asset tags, Windows product keys, personal files, account information, or identifying information from prior owners.
- A system passing selected tests does not establish that all hardware is free of faults.
- Any future evidence or results should be added with dates rather than retroactively presented as completed work.

---

**Portfolio maintained by Jamal Ramsey**  
*IT Enthusiast | Hands-on hardware troubleshooting, Windows deployment, and refurbishment*

# Laptop Repair, Troubleshooting & Refurbishment Portfolio

**Jamal Ramsey**  
**IT Enthusiast | Aspiring IT Support / Desktop Support & Repair Technician**  
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


<img width="886" height="886" alt="04FE2591-F84F-4E9E-A158-37FBCC22A655_1_105_c" src="https://github.com/user-attachments/assets/8801fb70-9fa6-43ec-aa63-205ee216ab65" />


<img width="1024" height="768" alt="A30811A9-0655-405C-A119-9D34BF539947_1_105_c" src="https://github.com/user-attachments/assets/f20ed6b0-5b63-4e80-96e6-aa289da153ab" />

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


<img width="1182" height="665" alt="5BD9E5D0-1935-45D5-A721-33DF20F0D67C_1_105_c" src="https://github.com/user-attachments/assets/95f347f5-f8f2-4909-8879-3b5cd637e728" />


<img width="665" height="1182" alt="9D9BF7B5-1238-4FCB-A2FA-680242E5051F_1_105_c" src="https://github.com/user-attachments/assets/dd4a1eb7-b90f-46f0-bfdb-f8867d83ca61" />


<img width="665" height="1182" alt="B351C004-6446-4E3B-A04D-47CA54F61AB6_1_105_c" src="https://github.com/user-attachments/assets/f47b35b1-d01f-4e3c-ab4a-870572642103" />


<img width="1182" height="665" alt="ED89D906-67CD-4410-8D92-3FFB67DBE1DC_1_105_c" src="https://github.com/user-attachments/assets/a93295e1-6995-4248-b538-698abdc3f466" />


<img width="1182" height="665" alt="0C52DC50-A7B1-4E6C-871E-7EFBFF29A80E_1_105_c" src="https://github.com/user-attachments/assets/f664fe0a-9139-434e-8df8-070d83b2468f" />


<img width="1182" height="665" alt="6293615A-A224-4D4E-B440-86EB0F48D0CE_1_105_c" src="https://github.com/user-attachments/assets/73cab0d8-3c5b-4361-b967-2bc79cf043e3" />


<img width="1182" height="665" alt="36B9491B-2EEA-4EC3-ABAE-D490E59F0A5D_1_105_c" src="https://github.com/user-attachments/assets/dae707b9-ddbd-41dd-8f1e-ec5ad9b8aea5" />


<img width="1182" height="665" alt="23793975-8711-4A25-8A3D-84970DF4E19C_1_105_c" src="https://github.com/user-attachments/assets/3af37348-819a-47f7-8523-0378e898e7ce" />


<img width="1182" height="665" alt="8F2706BB-247F-4FCF-9E3A-B8BB6937E21C_1_105_c" src="https://github.com/user-attachments/assets/b895cba6-89a6-4d3a-b4cc-08d689b22663" />

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

<img width="1182" height="665" alt="EC58FD0C-6F9F-4A13-8A3A-F45D78A5FD1A_1_105_c" src="https://github.com/user-attachments/assets/e272976d-0ac5-409a-ae8c-093d69468c7a" />

<img width="1182" height="665" alt="206FE3DC-B69C-446E-8EDF-F2007CAB79AB_1_105_c" src="https://github.com/user-attachments/assets/a41af205-7445-42c1-b4e1-7a3552f85797" />


<img width="1182" height="665" alt="E7E57B98-0057-41D0-9C52-0D604A70895D_1_105_c" src="https://github.com/user-attachments/assets/ff010c30-9733-440e-94e1-a84ee780a326" />


<img width="1182" height="665" alt="0E9B1F43-5A5E-4519-9CFE-4DB7DEFFCEC8_1_105_c" src="https://github.com/user-attachments/assets/a389565f-b8ab-4704-8d38-ed226ad36937" />

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

<img width="2208" height="1242" alt="9D5332B4-B72E-4F01-9BBC-4943BB5A806E_1_201_a" src="https://github.com/user-attachments/assets/6168d218-0d3a-4ccf-965f-31db12aff7ca" />

<img width="1182" height="665" alt="A66098C9-05B1-460F-B123-09D5DA6D1E08_1_105_c" src="https://github.com/user-attachments/assets/55194ca3-09b5-467b-b65a-ff17a87b118b" />

<img width="665" height="1182" alt="AC778FA0-8335-4CB0-BA88-D588D710A914_1_105_c" src="https://github.com/user-attachments/assets/479259df-3b90-459f-838c-a428b069af03" />


<img width="665" height="1182" alt="55C0F4F3-6FC9-4C68-BED6-C91F17A53A5F_1_105_c" src="https://github.com/user-attachments/assets/95938bdc-ce4d-45fe-aa4c-ecc5ce320b78" />

<img width="665" height="1182" alt="677CC79C-A570-486A-8F61-BE1B0B103DAD_1_105_c" src="https://github.com/user-attachments/assets/6b101b71-76c8-4e9a-8e19-dec0943a424e" />


<img width="665" height="1182" alt="B59931DA-A695-4AB5-B8B0-3CFDEC9583B2_1_105_c" src="https://github.com/user-attachments/assets/6a281fac-3b1c-4e02-9370-6c2cd836c6a4" />


<img width="1182" height="665" alt="C2FF2DA6-AB4B-4269-8ADD-4660A3111D61_1_105_c" src="https://github.com/user-attachments/assets/a65f325f-f305-4589-848c-2226aa884e9d" />

<img width="665" height="1182" alt="F4D8EA6F-ABCE-4479-8DBC-CC9399115091_1_105_c" src="https://github.com/user-attachments/assets/13530493-69b1-4d1c-81be-73d440ab63e4" />


<img width="665" height="1182" alt="235ADD37-5216-4E78-9B71-A4AF77A9E3CB_1_105_c" src="https://github.com/user-attachments/assets/8f1572a3-1f53-4baf-8bae-6ac4e868662a" />


<img width="1182" height="665" alt="4EF0CF3E-3129-4C23-877C-DB4231CE0636_1_105_c" src="https://github.com/user-attachments/assets/08339346-6895-4c42-9881-294219bb3ad9" />

<img width="1182" height="665" alt="D3F0C792-25EE-4B0C-8D60-D2C51CB277B2_1_105_c" src="https://github.com/user-attachments/assets/38079b70-e2d6-41aa-895d-80e326a6deeb" />


<img width="665" height="1182" alt="9B442226-7DB5-4FB0-A358-0D03F228F3E8_1_105_c" src="https://github.com/user-attachments/assets/7d808952-a638-47b8-a26a-22de82b50300" />


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

<img width="638" height="360" alt="630D58B9-D774-4CB6-BFC3-F304C97D20EE_4_5005_c" src="https://github.com/user-attachments/assets/c1b42b67-8ee8-4cc8-bb1a-61885277c836" />

<img width="1182" height="665" alt="B386C18D-9D7A-4A1E-B24A-36610DEB6BA0_1_105_c" src="https://github.com/user-attachments/assets/81da4e86-2c23-4b6b-a60a-bfd4da94e1e2" />


<img width="2208" height="1242" alt="76935401-888E-4374-938D-C33A60C8EE21_1_201_a" src="https://github.com/user-attachments/assets/3ef07755-4422-4c9c-8586-7f7c6fcbde45" />


<img width="1182" height="665" alt="085160DF-2771-4E4C-BC89-D7ADCECA34BC_1_105_c" src="https://github.com/user-attachments/assets/9ce2d5d3-4407-4d3a-9cf7-e7117c311f8e" />

<img width="1182" height="665" alt="98B4ACCB-C334-414D-A273-3195E6AA1230_1_105_c" src="https://github.com/user-attachments/assets/2b58aa3d-cbfd-449f-8efc-3428a873d754" />


<img width="1182" height="665" alt="C812EF77-3D48-486B-8F38-D809E3BB5F67_1_105_c" src="https://github.com/user-attachments/assets/0cf724cb-3f92-45c5-b3cb-231d96d1cfc3" />

<img width="1182" height="665" alt="3C22CFF7-545F-47B7-989E-EE0D1024FA30_1_105_c" src="https://github.com/user-attachments/assets/f5d6c0bc-d688-473e-b33e-772fd5e84bfd" />


<img width="665" height="1182" alt="ED30FDC4-F957-4688-8B27-F84B14444890_1_105_c" src="https://github.com/user-attachments/assets/a22321da-f0dc-4803-ada6-3ecd9006da3e" />


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

<img width="1024" height="768" alt="1C0CA825-5734-4266-9369-AF09906B6D86_1_105_c" src="https://github.com/user-attachments/assets/96adfdd2-ab09-44fc-9529-3f545ffb5e3a" />


<img width="1182" height="665" alt="4F952902-824B-41C4-BC0B-F5D9B0D05493_1_105_c" src="https://github.com/user-attachments/assets/e6f72019-5933-4c49-8d89-a18f1e804720" />


<img width="1182" height="665" alt="4D219E2D-A38A-4BF1-ABB1-7FF1134E4E09_1_105_c" src="https://github.com/user-attachments/assets/4cf75416-fcd2-4ef7-a755-3b127fe9dc50" />


<img width="1182" height="665" alt="973A9FFC-8673-41EE-A915-82594C4217BB_1_105_c" src="https://github.com/user-attachments/assets/61cdf632-c811-4d71-be12-7aa8b633efe9" />


<img width="1182" height="665" alt="E148CB39-6095-4DBD-9ECD-A360ACD61EB4_1_105_c" src="https://github.com/user-attachments/assets/9b257b14-03b2-490e-b12d-a0a089df0822" />

<img width="1182" height="665" alt="97CAE23B-5499-4361-A502-E0035F785CD4_1_105_c" src="https://github.com/user-attachments/assets/d5716a36-acda-4190-9ea9-c93bc445d3a4" />


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


<img width="1182" height="665" alt="0F4EB4F3-775E-4515-B71F-9E49AF648A55_1_105_c" src="https://github.com/user-attachments/assets/320d6072-1c25-44e4-8220-22977239aca2" />


<img width="1182" height="665" alt="4A58AF42-1BBF-4D5C-ACE7-DF9F1757E852_1_105_c" src="https://github.com/user-attachments/assets/45382622-692d-46fb-ab5e-9f6f0433b56b" />


<img width="1182" height="665" alt="385BBE41-9428-4E7D-BDA7-756FCD480955_1_105_c" src="https://github.com/user-attachments/assets/aba80361-deab-473f-be77-a50aa8e29350" />



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

<img width="2208" height="1242" alt="09409793-B205-42B5-8887-E5C75EF819B9_1_201_a" src="https://github.com/user-attachments/assets/99b03586-5076-46c0-a4fe-b84f7ec9b7bf" />

<img width="2208" height="1242" alt="BEE7C6B6-EBDC-4038-AA71-A1EF00B01623_1_201_a" src="https://github.com/user-attachments/assets/ae6e5ba3-f0e0-477c-9c44-ec348f22c4f6" />


<img width="665" height="1182" alt="30D42D4A-33AF-4F3E-8279-DDE9F4942DE9_1_105_c" src="https://github.com/user-attachments/assets/98a7e38f-9d17-42ce-b793-eb6868112c86" />


<img width="2208" height="1242" alt="6734C07E-D8C7-475D-A2BC-6BD0931B9020_1_201_a" src="https://github.com/user-attachments/assets/27266a13-41c5-4c0f-9cd2-f09c86726859" />



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


## Safety, Privacy and Scope

- All work described is hands-on learning, personal refurbishment, or authorized device work; it is **not** presented as paid enterprise IT employment.
- Power adapters, battery packs, and exposed circuitry require careful handling. Disconnect power before opening equipment and stop if a battery is swollen, damaged, or overheating.
- Do not publish device serial numbers, asset tags, Windows product keys, personal files, account information, or identifying information from prior owners.
- A system passing selected tests does not establish that all hardware is free of faults.
- Any future evidence or results should be added with dates rather than retroactively presented as completed work.

---

**Portfolio maintained by Jamal Ramsey**  
*IT Enthusiast | Hands-on hardware troubleshooting, Windows deployment, and refurbishment*

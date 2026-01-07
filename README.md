# Roll-Off Roof Observatory

## STRUCTURE CONSIDERATIONS

- Sliding roof using rack and pinion (commercial gate opener)
- Roof will sit just above telescope when telescope is fully sideways, allowing for viewing of the horizon when the roof is rolled off
- Roof will roll on a V-track with rollers
- Roof will roll back onto scaffolding with additional V-track
- Roof locking options for storms:
  - Solenoids on the roof that push locking pins into the walls to hold the roof down during severe weather  
  - *OR* a manual locking system used when a storm is anticipated
- Dimensions:
  - Observatory footprint: **8 ft × 10 ft**
  - Additional space on either side for sliding roof scaffolding
- Framing:
  - Constructed from **2×4 lumber**
- Foundation:
  - Raised foundation using plastic grid system filled with gravel
  - **MOT Type 2 sub-base**, leveled
  - Weed guard beneath plastic grids and gravel

---

## TELESCOPE PIER CONSIDERATIONS

- Concrete pier poured **before** the observatory foundation
- Pier depth:
  - **3 feet into the ground**
- Reinforcement:
  - Rebar embedded in the concrete
  - Rebar extends upward and connects into tube scaffolding
- Mounting plate:
  - Submerged into wet concrete and leveled while curing
  - Plate has **4 mounting studs**
  - Plate sides aligned with **cardinal directions**
- Telescope mount adapter:
  - Custom-machined adapter
  - Adjustable using the 4 studs for fine alignment

---

## REMOTE TELESCOPE SETUP

### Roof Control
- Roll-off roof controlled using **Wi-Fi-controlled relays**
  - One relay for opening
  - One relay for closing
- Safeguards in place to prevent roof movement unless the telescope is parked safely out of the roof path

### Telescope & Hardware Upgrades
- Planned upgrades for full remote operation:
  - Dedicated **CCD/CMOS astrophotography camera** (replaces DSLR)
  - More robust focuser with autofocuser
  - Improved mounting of OTA to mount
  - General maintenance:
    - Cleaning primary mirror
    - Collimation
- Aside from these upgrades, the setup is ready for remote operation

### Control Computer & Software
- Permanent PC or mini-PC connected to the internet
- Software stack:
  - **NINA** – open-source all-in-one astrophotography software
  - **EQMOD** – direct telescope control (required by NINA)
    - Used to park the telescope safely before roof movement

### Remote Access & Automation
- Short term:
  - Remote desktop access to control the system
- Long term:
  - Build an API to control NINA functions through a web server

### Data & Monitoring
- File transfer system to send images captured by NINA
- Wi-Fi cameras:
  - Interior camera to monitor telescope position  
    - Potential future use of computer vision for telescope recovery or movement
  - Exterior camera to monitor cloud cover
- Weather station:
  - Includes rain detector
  - Automatically triggers roof closure

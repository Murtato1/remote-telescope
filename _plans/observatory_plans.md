---
layout: page
title: Observatory Design
permalink: /plans/observatory/
---


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

<table>
  <thead>
    <tr>
      <th>Subsystem</th>
      <th>Design Summary</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Observatory Type</strong></td>
      <td>Roll-off roof observatory with motorized sliding roof</td>
    </tr>

    <tr>
      <td><strong>Roof Mechanism</strong></td>
      <td>
        Rack-and-pinion drive (commercial gate opener) on V-track with rollers;
        roof rolls onto external scaffolding extension
      </td>
    </tr>

    <tr>
      <td><strong>Storm Restraint</strong></td>
      <td>
        Solenoid-driven locking pins into wall structure
        <em>or</em> manual locking system for severe weather
      </td>
    </tr>

    <tr>
      <td><strong>Clearance &amp; Visibility</strong></td>
      <td>
        Roof height allows telescope to remain inside enclosure when horizontal,
        enabling low-altitude and horizon observations
      </td>
    </tr>

    <tr>
      <td><strong>Structure Dimensions</strong></td>
      <td>
        8 ft × 10 ft footprint, plus additional length for roof travel on scaffolding
      </td>
    </tr>

    <tr>
      <td><strong>Framing</strong></td>
      <td>2×4 lumber construction</td>
    </tr>

    <tr>
      <td><strong>Foundation</strong></td>
      <td>
        Raised foundation using plastic grid system with gravel fill;
        MOT Type 2 sub-base with weed barrier
      </td>
    </tr>

    <tr>
      <td><strong>Telescope Pier</strong></td>
      <td>
        Reinforced concrete pier, 3 ft deep, poured before foundation;
        rebar integrated into tube scaffolding
      </td>
    </tr>

    <tr>
      <td><strong>Mount Interface</strong></td>
      <td>
        Embedded mounting plate with four studs aligned to cardinal directions;
        custom adjustable mount adapter
      </td>
    </tr>

    <tr>
      <td><strong>Roof Control</strong></td>
      <td>
        Wi-Fi–controlled relays for open/close operations with software safety interlocks
      </td>
    </tr>

    <tr>
      <td><strong>Control Software</strong></td>
      <td>
        NINA for imaging automation and EQMOD for direct telescope control and parking
      </td>
    </tr>

    <tr>
      <td><strong>Remote Operation</strong></td>
      <td>
        Permanent on-site PC or mini-PC with remote desktop access;
        future API-based web control
      </td>
    </tr>

    <tr>
      <td><strong>Monitoring &amp; Safety</strong></td>
      <td>
        Interior and exterior Wi-Fi cameras, weather station with rain detector,
        automatic roof closure on unsafe conditions
      </td>
    </tr>

    <tr>
      <td><strong>Planned Upgrades</strong></td>
      <td>
        Dedicated CCD/CMOS camera, autofocuser, improved OTA mounting,
        mirror cleaning and collimation
      </td>
    </tr>
  </tbody>
</table>

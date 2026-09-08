# Ashton Hendrickson 🚀
**Aerospace Engineering Student | CAD • Flight Simulation • Automation**

[Portfolio](https://ashrick12.github.io/) • [LinkedIn](https://www.linkedin.com/in/ashton-hendrickson-55508a262) • [Email](mailto:ashtonh1204@gmail.com)

---

## About

I am an aerospace engineering transfer student at Chandler-Gilbert Community College preparing to transfer to Arizona State University for a B.S. in Aerospace Engineering (Astronautics track). I design mechanical assemblies in SolidWorks, run flight and stability simulations in OpenRocket, and prototype components using 3D printing and microcontrollers. Currently, I am building a custom mid-power sounding rocket and developing Python workflow automation tools in clinical operations.

## Highlights

- **3.711 GPA** — Member of Phi Theta Kappa National Honor Society (A grades in Calculus I & II and Physics I Kinematics).
- **1.49 cal Static Margin** — Tuned fin geometry in OpenRocket to establish stability with zero dead ballast weight.
- **10-Part SolidWorks Assembly** — Modeled dynamic rotational mates and produced 2D ANSI drawings (ECE 103 — Grade A).
- **Able Aerospace Job Shadow** — Observed FAA airworthiness data confirmation (Form 8110-3) and dynamic flight component machining.
- **Clinical Automation** — Built desktop route optimization and offline OCR tools in active daily office use.

## Featured Projects

### 1. Scratch-Built Mid-Power Sounding Rocket
Status: In Progress / Unlaunched

**What It Is**  
A 2.6-inch diameter (BT-80) sounding rocket designed to reach an apogee of 268 m (~880 ft) on an Aerotech F32 composite motor while recording barometric altitude and 6-axis acceleration data.

<p align="center">
  <img src="assets/rocket_cad_exploded.png" alt="SolidWorks Rocket Exploded CAD Assembly" width="800">
  <br>
  <em>SolidWorks exploded assembly of the current sounding rocket design</em>
</p>

**Flight Problem → Design Change → Result**
- **Flight Stability:** Early OpenRocket simulations showed marginal stability of 0.745 calibers. Reshaped fin sweep and chord to shift the center of pressure aft to 28.01" (with center of gravity at 24.12"), raising the static margin to **1.49 calibers** with zero dead ballast weight.
- **Thermal Recovery Protection:** Preliminary flight tests with commercial Estes kits (Hi-Flier on A8-3 and C6-5 motors) suffered wadding burn-through and excessive drift. Replaced paper wadding with a flameproof Nomex cloth piston that seals motor ejection gases, protects electronics, and pushes a 24" parachute for a **5.76 m/s** touchdown speed.
- **Structural Integrity:** Modeled the payload section with integrated coupler shoulders and an internal **4-legged shock cord anchor** across the bulkhead floor, distributing parachute opening shock directly into outer airframe walls.
- **Telemetry System:** Developing a flight datalogger using an RP2040 microcontroller, BMP390 precision barometer, and MPU-6500 6-axis IMU to log apogee and acceleration data to flash memory.

<p align="center">
  <img src="assets/rocket_launch.gif" width="280" alt="Estes Launch Liftoff">
  &nbsp;&nbsp;
  <img src="assets/rocket_launch_far.gif" width="280" alt="Ascent Tracking">
  <br>
  <em>Preliminary Estes flight tests at Freestone Park: assessing recovery drift and wadding burn</em>
</p>

<p align="center">
  <img src="assets/rocket_printed_parts.jpg" width="380" alt="3D Printed Rocket Parts">
  &nbsp;&nbsp;
  <img src="assets/rocket_avionics_haul.png" width="380" alt="RP2040 Avionics Hardware">
  <br>
  <em>Left: 3D-printed nose cone and payload bay. Right: Bench-testing RP2040 avionics sensors.</em>
</p>

**Tools**  
SolidWorks, OpenRocket, Bambu Lab A1, eSUN PLA+, Polymaker PETG, Raspberry Pi Pico (RP2040)

**Current Status**  
Airframe CAD and aerodynamic simulations are complete. Structural parts are printed in eSUN PLA+, and motor retention brackets are scheduled for PETG. Sensor data logging is being bench-tested in Python before field testing at an Arizona rocketry club launch site.

### 2. 10-Part SolidWorks Assembly
Status: Completed (ECE 103 — Grade A)

**What It Is**  
A 10-component mechanical desk fan designed from dimensioned hand sketches to a fully constrained assembly and standard 2D manufacturing drawings.

<p align="center">
  <img src="assets/desk_fan_poster.png" alt="SolidWorks Desk Fan Design Poster" width="750">
  <br>
  <em>SolidWorks 10-part assembly poster and orthographic views</em>
</p>

**What I Did**  
- Modeled 10 discrete parts including front and back grills with radial pattern cuts, aerodynamic blades, motor housing, on/off knob, shaft, frame ring, vertical stand, and weighted base.
- Applied concentric, coincident, and rotational mates to simulate full 360° blade rotation without interference.
- Conducted clearance detection between spinning blade tips and housing walls to eliminate collision points.
- Drafted production 2D ANSI drawings specifying tolerances, datum references, and manufacturing dimensions.

**Tools**  
SolidWorks 3D CAD, 2D ANSI Drawings

**Result**  
Assembly passed all interference and clearance checks; received an **A grade** in engineering CAD coursework.

### 3. Solar Energy Systems Modeling (MATLAB)
Status: Completed (Academic Team Project — Grade A)

**What It Is**  
A mathematical simulation and 25-year lifecycle financial analysis of an off-grid residential solar and battery storage installation in Chandler, Arizona.

<p align="center">
  <img src="assets/matlab_solar_plot.png" alt="MATLAB Solar Energy Simulation Plot" width="600">
  <br>
  <em>MATLAB simulation of seasonal solar irradiance and battery charge profiles</em>
</p>

**What I Did**  
- Served as lead mathematical modeler on a 5-person engineering team.
- Formulated balance equations linking seasonal sun angles and ambient temperatures to photovoltaic power output.
- Simulated battery charge and discharge profiles against peak summer cooling electrical demands.
- Built a 25-year Net Present Value (NPV) financial model comparing two competing battery chemistry options.

**Tools**  
MATLAB

**Result**  
Determined optimal battery storage capacity to ensure reliability during multi-day overcast periods; awarded an **A grade** and earned MathWorks MATLAB Onramp certification.

### 4. Smart Schedule Finder
Status: Deployed & In Use (Mobile Hearing Solutions)

**What It Is**  
A desktop scheduling tool built for Mobile Hearing Solutions to match patient appointments with existing travel routes across the Phoenix metropolitan area.

<p align="center">
  <img src="assets/schedule_finder_ui.png" alt="Smart Schedule Finder UI Screenshot" width="700">
  <br>
  <em>Application interface showing automated route and appointment matching</em>
</p>

**What I Did**  
- Connected to Google Calendar API using OAuth2 authentication with automated background token refresh.
- Automated appointment lookups by evaluating travel distance against existing technician schedules to minimize cross-town driving.
- Implemented single-patient checks and automated batch queue processing (next 5 patients).

**Tools**  
Python, Streamlit, Google Calendar API

**Result**  
Adopted into daily clinical operations, saving **2 to 3 hours per week** of manual route verification.

### 5. Local Document OCR Pipeline
Status: In Use (Mobile Hearing Solutions)

**What It Is**  
An offline document processing pipeline that extracts structured patient and insurance data from incoming multi-page fax transmissions.

**What I Did**  
- Configured an offline pipeline combining EasyOCR with 4-bit quantized local vision models.
- Processed demographic, insurance, and doctor referral fields into structured records without sending patient data to third-party cloud APIs, maintaining strict HIPAA compliance.
- Added confidence-score thresholds and manual review flags for ambiguous scans.

**Tools**  
Python, EasyOCR, Phi-4 Mini (4-bit)

**Result**  
Eliminated third-party OCR API fees while keeping sensitive patient healthcare data entirely on local office hardware.

---

## Aerospace Experience

### Able Aerospace (Textron Aviation) — Mesa, AZ
*Engineering Specialist Job Shadow | August 2026 | FAA Part 145 Repair Station*

- **FAA Airworthiness Certification:** Shadowed an engineering specialist reviewing engineering change orders, confirming airworthiness data, and preparing compliance documentation submitted under **FAA Form 8110-3** for dynamic flight components.
- **Flight-Critical Machining:** Observed multi-axis CNC milling and tolerance verification of high-stress aircraft components, including helicopter rotor hubs, transmission shafts, and landing gear parts.
- **Surface Treatments & Tooling:** Observed shot-peening processes for fatigue resistance, cadmium electroplating lines, and in-house SolidWorks fixture design for hydrostatic test tanks.

## Technical Skills

- **CAD & Mechanical Design:** SolidWorks (3D Parametric Part Modeling, Multi-Body Assemblies, Rotational Mates, Interference Checking, 2D ANSI Drawings)
- **Aerodynamics & Flight Simulation:** OpenRocket (Trajectory Analysis, Center of Pressure / Center of Gravity Tuning, Static Stability Margin, Descent Rate Sizing), MATLAB
- **Additive Manufacturing & Prototyping:** Bambu Lab A1, Bambu Studio (STEP File Slicing, Gyroid Infill, eSUN PLA+, Polymaker PETG), Hand Soldering
- **Avionics & Embedded Systems:** Raspberry Pi Pico (RP2040), BMP390 Barometer, MPU-6500 6-Axis IMU, SPI MicroSD Logging, LiPo / TP4056 USB-C Power Management
- **Programming & Software:** Python, MATLAB, Streamlit, Git, Google Calendar API, EasyOCR
- **Standards & Regulations:** FAA Form 8110-3, FAA Part 145 Overview, NAR Safety Code

## Repository

```text
.
├── assets/             # CAD renders, flight media, and circuit photos
├── index.html          # Interactive dark-mode web portfolio
├── styles.css          # Modern engineering stylesheet
├── portfolio.md        # Comprehensive technical dossier (markdown)
└── README.md           # Engineering repository overview
```

## Contact

- **Email:** [ashtonh1204@gmail.com](mailto:ashtonh1204@gmail.com)
- **LinkedIn:** [linkedin.com/in/ashton-hendrickson-55508a262](https://www.linkedin.com/in/ashton-hendrickson-55508a262)
- **GitHub:** [github.com/ashrick12](https://github.com/ashrick12)
- **Portfolio:** [ashrick12.github.io](https://ashrick12.github.io/)

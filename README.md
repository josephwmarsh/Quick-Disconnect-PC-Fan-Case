# Quick-Disconnect-PC-Fan-Case
Design and prototyping of a tool-less, electrical quick-disconnect PC fan housing utilizing a sliding track system and magnetic pogo-pin connectors.

## Project Overview
This repository documents the design, engineering, and prototyping of the "Easy-Clean" fan housing. The product features a "Quick Disconnect" mechanism that allows users to remove and clean PC fans without tools or manual cable management. By decoupling the fan's electrical connection from the case wiring via magnetic pogo-pin connectors, the design significantly reduces maintenance downtime and risk of cable damage.

## Technical Features and Innovation
### 1. Tool-less Electrical Interface
* **Component:** Utilized magnetic pogo-pin (JH-Pogo2) connector sets integrated directly into the housing.
* **Functionality:** The electrical circuit is completed automatically upon seating the fan basket into the case-mounted sheath.
* **Tolerances:** Engineered the assembly to maintain a **0.5 mm alignment tolerance** to ensure consistent electrical contact and prevent pin shear.



### 2. "Sheath and Basket" Sliding Track System
* **Architecture:** Divided the housing into two primary structural components:
    * **Sheath:** Mounts permanently to the PC chassis using standard mounting points.
    * **Basket:** Houses the 120mm fan and slides into the sheath via a custom-designed rail system.
* **Mechanical Design:** Optimized the sliding track for a friction-fit that prevents vibrational noise while allowing for low-force extraction.



## Design for Manufacturing (DFM)
The project transitioned from rapid prototyping to a mass-production feasibility study:
* **Prototyping:** Produced initial iterations using PLA via FDM 3D printing to validate fitment and sliding clearances.
* **Production Intent:** Developed a Production Bill of Materials (BOM) for an initial 4,000-unit run. 
* **Material Selection:** Selected **Polybenzimidazole** for production due to its high heat resistance and abrasion resistance, ensuring the sliding tracks do not degrade over thousands of cycles.
* **Process:** Designed the sub-components specifically for **Injection Molding**, ensuring proper draft angles and wall thicknesses for high-volume scalability.

## Validation and Iteration
* **FMEA Analysis:** Conducted a Failure Mode and Effects Analysis to identify risks such as pogo-pin misalignment or track binding.
* **Prototypive Iteration:** Successfully moved from "Prototype 1" (simple mounting) to "Prototype 2" (integrated sliding mechanism) after identifying that extraction forces needed to be minimized for user safety.
* **Assembly Validation:** Created full technical drawings and a collapsed isometric assembly to verify component interdependencies.

## Repository Contents
* **Quick_Disconnect_PC_Fan_Case_Design_Analysis.pdf**: A comprehensive 8-page technical packet including the Prototype BOM, Production BOM, and detailed CAD drafting for sub-components.

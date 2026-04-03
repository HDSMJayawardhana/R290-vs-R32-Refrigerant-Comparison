# ❄️ Comparison of R-290 as an Alternative Refrigerant to R-32 in Domestic Air Conditioners
### ME325 - Mechanical Engineering Group Project | University of Peradeniya | 2024

![Language](https://img.shields.io/badge/Tools-SolidWorks-red)
![Language](https://img.shields.io/badge/Tools-MS_Office-blue)
![Language](https://img.shields.io/badge/Tools-GitHub-black)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![University](https://img.shields.io/badge/University-Peradeniya-maroon)
![Year](https://img.shields.io/badge/Year-2024-yellow)
![Industry](https://img.shields.io/badge/Industry_Partner-Abans_PLC-orange)

---

## 📖 Project Overview

This project presents a comprehensive comparative analysis of R-290 (Propane)
as a sustainable alternative refrigerant to R-32 (Difluoromethane) in domestic
split-type air conditioning systems.

The study evaluates both refrigerants across four key dimensions:
- Environmental Impact (GWP and ODP)
- Safety Considerations (Flammability and handling)
- Thermodynamic Performance (COP, VRE, Pressure Ratios)
- Economic Viability (Cost comparison and long-term savings)

The conclusion confirms that R-290 is a viable, sustainable, and energy-efficient
alternative to R-32, provided that enhanced safety protocols are implemented.

---

## 👥 Group Details

Group Name: RvsR

Members:
- Amunumulla A. L. B. G.    - E/19/022
- Ellawala K. K. Y. A.      - E/19/099
- Fernando A. A. N.         - E/19/107
- Jayawardhana H. D. S. M.  - E/19/169 (Salinda Madushan)

Supervised by:
Prof. Primal Fernando
Department of Mechanical Engineering
Faculty of Engineering
University of Peradeniya

---

## 🏭 Industry Partner

This project was conducted in collaboration with Abans PLC and
AB Manufacturing Pvt. Ltd., Sri Lanka.

A field visit to AB Manufacturing was conducted on 08/10/2024
to study the existing air conditioning unit and collect real-world data.

---

## 🔬 Refrigerant Overview

### R-32 (Difluoromethane - CH2F2)

    Classification   : Hydrofluorocarbon (HFC)
    GWP              : 675
    ODP              : 0
    Flammability     : A2L - Mildly Flammable
    Boiling Point    : -52.5 degrees C
    Critical Temp    : 78.11 degrees C
    Critical Pressure: 5.72 MPa
    Toxicity         : A - Non toxic

### R-290 (Propane - C3H8)

    Classification   : Hydrocarbon (HC)
    GWP              : 3
    ODP              : 0
    Flammability     : A3 - Highly Flammable
    Boiling Point    : -42.1 degrees C
    Critical Temp    : 96.7 degrees C
    Critical Pressure: 4.248 MPa
    Toxicity         : A - Non toxic

---

## 📊 Key Comparison Results

### 1. Environmental Impact

| Parameter | R-32 | R-290 | Winner |
|-----------|------|-------|--------|
| GWP (100yr) | 675 | 3 | R-290 |
| ODP | 0 | 0 | Equal |
| Atmospheric Lifetime | ~5 years | Very short | R-290 |
| Production Impact | Synthetic | Natural | R-290 |

R-290 is significantly more environmentally friendly with a GWP
225 times lower than R-32. Both have zero ODP.

---

### 2. Safety Considerations

| Parameter | R-32 | R-290 |
|-----------|------|-------|
| ASHRAE Class | A2L - Lower Flammability | A3 - Higher Flammability |
| Operating Pressure | Higher | Lower |
| Toxicity | Non-toxic | Non-toxic |
| Handling Risk | Moderate | High - requires strict protocols |

R-32 is safer in terms of flammability. R-290 requires:
- Proper ventilation systems
- Flameproof equipment and components
- Leak detection systems
- Safety valves and pressure relief devices
- Certified technicians for handling

---

### 3. Thermodynamic Properties

    Pressure Variation vs Temperature:
    Both refrigerants show similar pressure-temperature trends.
    R-32 operates at higher pressures than R-290.

    Volumetric Refrigerating Effect (VRE):
    R-32 : Higher VRE - better for compact high-capacity systems
    R-290 : Lower VRE - but compensated by superior energy efficiency

    Pressure Ratio (discharge/suction):
    R-290 has lower pressure ratios than R-32 at all condenser
    temperatures, indicating lower compressor power consumption.

---

### 4. COP Calculation Results

Assumptions:
   - Condenser Temperature : 40 degrees C
   - Evaporator Temperature: 10 degrees C
   - Process 1-2           : Isentropic

R-32 COP Calculation:
   - P1 = 1.10690 MPa
   - P3 = 2.47830 MPa
   - h1 = 516.66 kJ/kg
   - h2 = 553 kJ/kg
   - h3 = 275.61 kJ/kg
   - Work input = h2 - h1 = 36.34 kJ/kg
   - Q_in = h1 - h4 = 241.01 kJ/kg
   - COP (R-32) = 6.633

R-290 COP Calculation:
   - P1 = 0.63660 MPa   P3 = 1.3694 MPa
   - h1 = 585.67 kJ/kg  h2 = 620 kJ/kg
   - h3 = 307.15 kJ/kg
   - Work input = h2 - h1 = 34.33 kJ/kg
   - Q_in = h1 - h4 = 278.52 kJ/kg
   - COP (R-290) = 8.113

Result: 
- COP R-32 (6.633) < COP R-290 (8.113)
- R-290 demonstrates superior energy efficiency.

---

### 5. Energy Efficiency Summary

| Metric | R-32 | R-290 | Advantage |
|--------|------|-------|-----------|
| COP | 6.633 | 8.113 | R-290 (+22%) |
| Compressor Power | Higher | Lower | R-290 |
| Heat Transfer | Good | Superior | R-290 |
| VRE | Higher | Lower | R-32 |
| Pressure Ratio | Higher | Lower | R-290 |

---

### 6. Cost Comparison

    Refrigerant Cost   : R-290 significantly cheaper (natural availability)
    Initial Investment : R-290 higher (safety modifications required)
    Operating Cost     : R-290 lower (better energy efficiency)
    Long-term Value    : R-290 superior (energy savings + regulatory compliance)

---

## 🔧 Practical Challenges Identified

### Problem 1 - Compressor Compatibility
    Existing compressor model: KSN108D32UFZ (R32)
    Lubricant type: Ester type (synthetic base oil)
    Finding: R-290 is compatible with ester type lubricants
    Conclusion: Same compressor can be used with R-290

### Problem 2 - Lower Cooling Capacity of R-290
    R-290 has slightly lower volumetric cooling capacity than R-32.
    This results in longer time to achieve desired temperature.
    Impact minimal for small domestic applications.
    For large industrial applications: compressor modifications needed.

### Problem 3 - Higher Flammability of R-290
    R-290 auto ignition temperature: 470 degrees C
    R-290 operates at lower pressures than R-32 - reduces some risk
    Mitigation: Flameproof components, ventilation, leak detectors

### Problem 4 - Operating Condition Differences
    R-290 and R-32 operate under different thermodynamic conditions.
    Direct COP comparison using same evaporator and condenser
    temperatures is not practically valid.
    Solution: Compare pressure ratios as indicator of power consumption.

---

## 📁 Repository Structure

    R290-vs-R32-Refrigerant-Comparison/
    |
    |-- README.md
    |
    |-- Report/
    |   |-- Final_Report.pdf
    |
    |-- Figures/
        |-- Pressure Vs Enthalpy diagram of a refrigeration cycle.png
        |-- Pressure_vs_Temperature_R32_R290.png
        |-- VRE_vs_Evaporating_Temp_R32.png
        |-- VRE_vs_Evaporating_Temp_R290.png
        |-- Pressure_Ratio_vs_Evaporating_Temp_R32.png
        |-- Pressure_Ratio_vs_Evaporating_Temp_R290.png
        |-- Flammability_Classification_Chart.png
        |-- Schematic diagram for basic refrigeration_Cycle.png

---

## 🔄 Basic Refrigeration Cycle

    The split-type air conditioning system consists of:

    Indoor Unit:
    - Evaporator coil
    - Fan
    - Air filter

    Outdoor Unit:
    - Compressor
    - Condenser coil
    - Fan

    Refrigeration Cycle Process:
    1. Compressor compresses refrigerant (high temp + high pressure)
    2. Condenser releases heat to outside air
    3. Expansion valve reduces pressure
    4. Evaporator absorbs heat from indoor air
    5. Cycle repeats

    Key Equations:
    COP = Cooling Output (W) / Power Input (W)
    EER = Cooling Capacity (kW or BTU/h) / Power Input (kW or W)
    Pressure Ratio = Discharge Pressure / Suction Pressure

---

## 📚 Methodology

    1. Literature Review
       - Thermodynamic properties of R-32 and R-290
       - Existing research on refrigerant alternatives
       - Industry standards (ASHRAE, ISO 817:2014)

    2. Experimental Setup (Planned)
       - Split-type AC unit designed for R-32
       - Temperature sensors, pressure gauges, energy meters
       - Field visit to AB Manufacturing (08/10/2024)

    3. Theoretical Analysis (Performed)
       - Thermodynamic cycle calculations
       - COP comparison at standard conditions
       - Volumetric refrigerating effect analysis
       - Pressure ratio comparison

    4. Results and Discussion
       - Environmental impact comparison
       - Safety considerations analysis
       - Cost-benefit evaluation
       - Thermodynamic performance comparison

    Note: Experimental analysis could not be fully conducted due to
    inability to procure necessary instruments. Theoretical analysis
    was performed instead.

---

## 📋 Key Findings Summary

    Environmental : R-290 is superior - GWP of 3 vs 675 for R-32
    Safety        : R-32 is safer - A2L vs A3 flammability class
    Efficiency    : R-290 is superior - COP 8.113 vs 6.633
    Cost          : R-290 better long-term despite higher initial cost
    Feasibility   : Replacement is viable with proper safety measures

---

## 🔮 Future Work

The future scope includes:
- Practical implementation in thermodynamics laboratory
- Use of climate chamber for controlled testing
- Measurement of condenser and evaporator pressures and temperatures
- Calculation of cooling capacity in BTU/hr
- Direct performance comparison under real operating conditions

---

## 📖 Key References

1. Rizka Ulum, Berkah Fajar, Tony Suryo Utomo (2022).
   Experimental Study of Performance AC Split R32 Retrofitted
   with R290 at 50% Mass. IRJIET, Volume 6, Issue 7, pp 8-11.
   DOI: https://doi.org/10.47001/IRJIET/2022.607002

2. IIR (2014). Performance of R32 and R290 as alternatives to
   R22 and R410A in domestic air conditioning.
   International Institute of Refrigeration.

3. ASHRAE Standard 34-2022: Designation and Safety
   Classification of Refrigerants.

4. ISO 817:2014 - Refrigerants - Designation and Safety
   Classification.

---

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| SolidWorks | 3D modeling and visualization |
| MS Office (Excel) | Data analysis and graphs |
| GitHub | Version control and collaboration |

---

## 🎓 Academic Information

| Detail | Info |
|--------|------|
| Course | ME325 - Mechanical Engineering Group Project |
| Year | 3rd Year - 2024 |
| Institution | University of Peradeniya |
| Faculty | Faculty of Engineering |
| Department | Mechanical Engineering |
| Submission Date | 01/12/2024 |
| Industry Partner | Abans PLC / AB Manufacturing Pvt. Ltd. |

---

## 👤 Author (Salinda Madushan)

Mechatronics Engineer | Robotics and AI Specialist

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue)](https://linkedin.com/in/h-d-s-m-jayawardhana)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black)](https://github.com/Salinda1999)

---

## 📄 License

This project was developed as academic coursework at the
University of Peradeniya. All work is original and conducted
by the RvsR group members.

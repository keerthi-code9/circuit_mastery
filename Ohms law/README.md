# ⚡ Ohm's Law

## Objective
To verify Ohm's Law through simulation and understand the relationship between voltage, current, and resistance.

---

## Theory





Ohm's Law states that the current flowing through an ohmic conductor is directly proportional to the applied voltage and inversely proportional to its resistance, provided temperature and other physical conditions remain constant.

---

## Circuit

### Components
- DC Voltage Source: **5 V**
- Resistor 1: **100 Ω**
- Resistor 2: **1 kΩ**

> *Insert circuit schematic here.*
<img width="1599" height="899" alt="image" src="https://github.com/user-attachments/assets/5f727146-9137-4919-9ff6-60715c293cb9" />


## Prediction

Before simulation:

- Both resistors will have **5 V** across them.
- The **100 Ω** resistor will draw more current than the **1 kΩ** resistor.
- Increasing voltage should increase current.
- Increasing resistance should decrease current.

---

## Simulation Results

| Resistance | Voltage | Current |
|------------|---------|---------|
| 100 Ω | 5 V | 50 mA |
| 1 kΩ | 5 V | 5 mA |

<img width="642" height="582" alt="image" src="https://github.com/user-attachments/assets/0ca19b9a-ba25-46a1-a124-338b2cf0bdb5" />


---

## Analysis

- Both resistors experienced the same voltage because they were connected in parallel.
- The 100 Ω resistor drew **10× more current** than the 1 kΩ resistor.
- This confirms that **current is inversely proportional to resistance** for a constant voltage.

---

## Power

The power consumed by a component is:

\[
P = VI
\]

This does **not** mean voltage and current are always inversely proportional.

- **Constant Resistance:** Voltage ↑ → Current ↑
- **Constant Power:** Voltage ↑ → Current ↓

The relationship depends on **what is held constant**.

---

## Exceptions

Ohm's Law applies only to **ohmic devices** with constant resistance.

Examples of non-ohmic devices:
- LED
- Diode
- Transistor
- Filament Lamp

---

## Key Learnings

- Voltage is the driving force for current.
- Resistance limits the current flow.
- Lower resistance results in higher current.
- Ohm's Law is valid only for ohmic materials.
- Always identify whether **resistance** or **power** is the constant quantity before relating voltage and current.

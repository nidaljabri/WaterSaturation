# 💧 Water Saturation Calculator

A GUI-based Python application to calculate water saturation in reservoir rocks using two different methods: **Archie's Equation** and **Simandoux Equation**.

---

## 📌 Overview

This tool provides a user-friendly interface for geoscientists and petrophysicists to estimate water saturation (Swa) based on input parameters related to rock and fluid properties. It supports:

- **Archie's Method**: Ideal for clean formations.
- **Simandoux Method**: Suitable for shaly formations.

Developed using Python's `tkinter` library for GUI and `PIL` for image handling.

---

## 👨‍💻 Author

**Nidal Jabri**  
© 2019 Nila Holding Group LLC  
📧 Contact: [Nidal.Jabri@Mavs.Uta.Edu](mailto:Nidal.Jabri@Mavs.Uta.Edu)

---

## 🧮 Calculation Methods

### 1. Archie's Equation

\[
S_{wa} = \left( \frac{A \cdot R_{wft}}{\phi^m \cdot R_{esd}} \right)^{\frac{1}{n}} \times 100
\]

- **A**: Tortuosity exponent  
- **m**: Cementation exponent  
- **n**: Saturation exponent  
- **ϕ (PHIE)**: Effective porosity  
- **Resd**: Resistivity of the zone  
- **Rwft**: Formation water resistivity  

### 2. Simandoux Equation

\[
S_{wa} = \left[ \frac{0.4 \cdot R_{wft}}{\phi^2} \cdot \left( \sqrt{\left( \frac{V_{sh}}{R_{sh}} \right)^2} + \frac{\phi^2 \cdot 5}{R_{esd} \cdot R_{wft}} \right) - \left( \frac{V_{sh}}{R_{sh}} \right) \right] \times 100
\]

- **Vsh**: Volume of shale  
- **Rsh**: Resistivity of shale  

---

## 🖥️ GUI Features

- Input fields for all required parameters
- Buttons to compute water saturation using either method
- Displays result as a percentage
- Includes branding and icons
- Menu options for "About" and "Exit"

---

## 🛠️ Requirements

- Python 3.x
- `tkinter` (standard with Python)
- `Pillow` (for image handling)

Install Pillow if not already available:

```bash
pip install pillow

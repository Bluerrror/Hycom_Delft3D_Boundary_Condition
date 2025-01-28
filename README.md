# 🌊 HYCOM to Delft3D Boundary Conditions

This repository contains a Python script designed to convert HYCOM (Hybrid Coordinate Ocean Model) dataset outputs into multiple levels of boundary conditions for **Delft3D-FM** and **Delft3D-FLOW**. Specifically, it prepares the salinity and temperature boundary conditions required for hydrodynamic and water quality simulations.

---

## ✨ Features
- 🌀 **Processes HYCOM dataset outputs**.
- 📊 **Generates boundary conditions for Delft3D-FM and Delft3D-FLOW**.
- 🌐 **Supports multiple vertical levels**.
- 🌡️ **Prepares salinity and temperature boundary conditions**.

---

## 🛠️ Requirements

To use this script, ensure the following Python libraries are installed:

- `sys`
- `numpy`
- `pandas`
- `openearthtools`
- `xarray`
- `datetime`
- `warnings`
- `tqdm`

To install the required packages, use the following command:

```bash
pip install numpy pandas xarray openearthtools tqdm
```

---

## 🚀 Usage

### 🔹 Input
The script requires **HYCOM dataset files** as input. These files should be in a format readable by `xarray` (e.g., NetCDF).

### 🔹 Output
The script produces **boundary condition files** for Delft3D-FM and Delft3D-FLOW.

### 🔹 Running the Script
1. **Clone this repository**:

```bash
git clone <repository_url>
cd <repository_name>
```

2. **Run the Python script**:

```bash
python script_name.py
```

Replace `script_name.py` with the actual script filename.

---

## 📂 Code Overview

### 📚 Key Libraries
The script uses the following key libraries:
- **`openearthtools.io.delft3d`**: Handles Delft3D data input and output.
- **`xarray`**: Manages HYCOM dataset processing.
- **`tqdm`**: Provides progress tracking.

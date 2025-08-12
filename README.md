# SSTSS-Tool

# SSTSS Tool

**SSTSS** ([[{S}imulation-based \underline{S}afety \underline{T}esting \underline{S}cenario \underline{S}election) process]]) is an interactive **Scenario Database Management Tool** designed for organizing, filtering, prioritizing, and selecting driving scenarios for simulation and testing.  
Built with **Python** and **PyQt5**, it provides an intuitive GUI for researchers, testers, and engineers working with scenario-based testing datasets.

---

## Features

- **Scenario Catalog Selection** – Easily switch between catalogs (US, Singapore, Europe, Other).
- **Flag Display** – Dynamic flag icon based on selected catalog.
- **Scenario Management**:
  1. View all available scenarios.
  2. Select Operational Design Domains (ODDs).
  3. Filter scenarios based on ODD selection.
  4. Assign scenarios to scenario groups.
  5. Prioritize scenario groups for testing.
  6. Filter scenarios by simulator compatibility (Carla, Gazebo, Audacity, LGSVL).
  7. Review final selected scenarios.
- **Excel-based Storage** – Reads and updates scenario datasets stored in `.xlsx` format.
- **Modular Design** – Separate scripts for each functional component.

---

## Screenshot

![SSTSS Main Window](assets/sstss_main.png)  
*Example main interface with catalog selector and scenario actions.*  
> **Note:** Replace with your actual screenshot(s).

---

## Workflow

1. **Launch the Tool** – Run the main Python script.
2. **Select Catalog** – Choose the dataset region (US, Singapore, Europe, Other).
3. **View / Add Scenarios** – Add new entries or browse existing ones.
4. **Select ODD** – Narrow down scenarios based on operational conditions.
5. **Assign & Prioritize** – Group related scenarios and rank their importance.
6. **Filter by Simulator** – Keep only scenarios compatible with a specific simulator.
7. **Export / Review Final Set** – Prepare scenarios for testing or simulation.

---

## Installation

### 1. Clone the Repository
```bash
git clone https://github.com/[[your-username]]/sstss-tool.git
cd sstss-tool

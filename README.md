# SHM of Offshore Structures Workshop

This repository contains a **Python notebook and supporting scripts** developed for the **SHM of Offshore Structures Workshop** on fatigue analysis. It is designed to familiarize users with:  

- **Integration with the OWI metadatabase**: Accessing geometric and fatigue-related information through a Python API.  
- **Material definitions**: Assigning material properties relevant for fatigue calculations.  
- **Strain data preprocessing**: Cleaning, filtering, and structuring raw strain measurements from sensors.  
- **Fatigue analysis workflows**: Computing cumulative fatigue damage, generating time series, and visualizing results.  

The notebook provides hands-on examples to help participants:  

- Fetch geometry and fatigue metadata directly from the OWI metadatabase.  
- Define and apply material properties for fatigue calculations.  
- Load and preprocess structural strain datasets.  
- Visualize cumulative fatigue damage with respect to time and operational conditions.  

This repository is intended for users interested in **offshore wind turbine structural health monitoring and fatigue analysis**, offering a practical introduction to combining experimental data with database-driven structural insights.

### Dependency management with uv

This repository uses [uv](https://docs.astral.sh/uv/) to manage Python dependencies:

```bash
uv sync
uv run jupyter lab
```


## Working on the Workshop

There are two main ways to use the workshop materials:

- **GitHub Codespaces (recommended during the workshop):** Launch a ready-to-use development environment in your browser, configured through the repository's `.devcontainer` configuration.
- **Local installation:** Clone the repository and set up the development environment on your own machine.



### Option 1: GitHub Codespaces

1. Open this repository on GitHub.
2. Click the **Code** button.
3. Select the **Codespaces** tab.
4. Click **Create codespace on main**.
5. Wait for the development environment to build and initialize.
6. Open the relevant workshop notebook and run the cells interactively.

The Codespace uses the configuration defined in `.devcontainer`. The initial setup may take a few minutes.

> **Note:** Your Codespace runs in a cloud-hosted environment. Commit and push any changes you want to preserve in the repository.

### Option 2: Local Installation

Clone the repository:

```bash
git clone https://github.com/OWI-Lab/SHM-of-Offshore-Structures.git
cd SHM-of-Offshore-Structures
```


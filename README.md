# VMware Tools Dashboard for vRealize Operations

This repository provides a set of dashboards and views for monitoring VMware Tools status, state, and inventory in VMware vRealize Operations Manager. These tools help you gain insights into the operational state of VMware Tools across your virtual environment.

## Features
- **Comprehensive VMware Tools Summary**: Overview of VMware Tools status and state.
- **Inventory Management**: Detailed insights into running and non-running VMware Tools instances.
- **Distribution Views**:
  - VMware Tools versions.
  - VMware Tools running state distribution.
  - VMware Tools running status distribution.

## Prerequisites
- **VMware vRealize Operations Manager**: Version 7.x or 8.x.
- **Access**: Ensure you have administrative access to import dashboards and views.

## Installation

### Import Dashboards
1. Navigate to `Dashboards` > `Actions` > `Manage Dashboard` > `Import`.
2. Select the file: 
   - `dashboard-Operations-VMware-Tools-Summary.zip`

### Import Views
1. Navigate to `Views` > `Import`.
2. Import the following files:
   - `Operations VMware Tools Summary.zip`
   - `Operations VMware Tools Running Distrub state.zip`
   - `Operations VMware Tools Running Distrub status.zip`
   - `Operations VMware Tools Not Running.zip`
   - `Operations VMware Tools Version distrib bar.zip`

## Usage
After importing, the dashboards and views will be accessible under their respective sections in VMware vRealize Operations. Use these dashboards to:
- Monitor VMware Tools statuses.
- Identify discrepancies in tool versions.
- Gain insights into operational states for better management.

## Repository Contents
- **Dashboards**: Pre-configured dashboard files to summarize VMware Tools data.
- **Views**: Additional visual insights for specific VMware Tools attributes.

## Authors
- **Eran Maor**  
  Initial work and development of dashboards. [GitHub Profile](https://github.com/emaor23)

## Contributions
Contributions are welcome! Feel free to fork the repository, make changes, and submit a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
For any issues or feature requests, please open an issue in the repository.

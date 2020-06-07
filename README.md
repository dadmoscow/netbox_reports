# Custom [NetBox](https://github.com/digitalocean/netbox) Reports

[![CodeFactor](https://www.codefactor.io/repository/github/dadmoscow/netbox_reports/badge)](https://www.codefactor.io/repository/github/dadmoscow/netbox_reports)

## Reports

### DeviceAndTemplate

Check for differences in the template and corresponding devices

* **test_count_interfaces** - Checks and displays the number of physical interfaces between the device and its template
* **test_interface_name** - Checks and displays the names of physical interfaces between the device and its template

### InterfaceConnection

Check for lost physical interface connections

* **test_interface_connection** - Checks and displays the names of unconnected physical interfaces for the device

## How-To

1. Reports must be saved as files in the REPORTS_ROOT path (in `configuration.py`). Which defaults to `netbox/reports/`.
2. Copy `reports/custom_reports.py` to REPORTS_ROOT
3. Open in web UI path Organization - Reports
4. Open report and press "Run Report"

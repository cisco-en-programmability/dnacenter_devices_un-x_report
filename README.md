
# Cisco DNA Center un-X Devices report

This application will identify all Cisco DNA Center devices that are in one of these 'un-x' states:
    - un-claimed in the PnP inventory
    - un-assigned to a site
    - un-reachable by Cisco DNA Center
    It will create a report with the hostname and platform id for these devices

**Cisco Products & Services:**

- Cisco DNA Center
- Cisco network devices managed by Cisco DNA Center

**Tools & Frameworks:**

- Python environment to run the application
- Cisco DNA Center Python SDK - https://github.com/cisco-en-programmability/dnacentersdk

**Usage**

This application will identify all Cisco DNA Center devices that are in one of these 'un-x' states:
    - un-claimed in the PnP inventory
    - un-assigned to a site
    - un-reachable by Cisco DNA Center
It will create a report with the hostname and platform Id for these devices

Sample Output:

```
"un-x_devices_report.py" App Run Start,  2021-01-21 15:53:45


Unclaimed devices found:
Device Hostname                Device PID                    
AP70F3.5A7A.6310               AIR-AP1800S-B-K9              
AP70F3.5A7A.6418               AIR-AP1800S-B-K9              


Unreachable devices found:
Device Hostname                Device PID                    
AP70F3.5A7A.6310               AIR-AP1800S-B-K9              
AP70F3.5A7A.6418               AIR-AP1800S-B-K9              
NYC-ACCESS                     C9300-24UX                    
NYC-RO                         CSR1000V                      
SP                             CSR1000V                      


Unassigned devices found:
Device Hostname                Device PID                    
PDX-RN                         CSR1000V                      
SP                             CSR1000V                      
PDX-CORE1                      WS-C3850-24U-E                
NYC-ACCESS                     C9300-24UX                    

"un-x_devices_report.py" App Run End,  2021-01-21 15:53:47
```
 
This sample code is for proof of concepts and labs

**License**

This project is licensed to you under the terms of the [Cisco Sample Code License](./LICENSE).



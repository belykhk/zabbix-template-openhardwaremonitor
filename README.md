# zabbix-template-openhardwaremonitor
A Zabbix Template to get sensor information from OpenHardwareMonintor via WMI.

## Installation

 - Install Open Hardware Monitor on machine you wany to monitor and make sure it set on `Run on Windows startup`
 - Import the template in `/template` to your Zabbix Server instance, and assign it to a host running OpenHardwareMonitor that has WMI accessible.

## Support

 - None. I will not help you troubleshoot WMI. I had issues with WMI, which required me to update OpenHardwareMonitor to v0.8.0.3, however that may just have been a case of Error: ID10T.

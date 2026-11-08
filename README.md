# GRC103-Technical-Risk-Treatment-Lab
GRC103 Technical Risk Treatment Lab
Faith Mathapelo Letsoara

Evidence Mapping

Baseline_Validation.png
- Baseline validation showing:
  - Port 80 active
  - Port 8080 active
  - Archive accessible
  - Legacy application accessible

Evidence_02_Legacy_Service_Removed.png
- Validation of avoidance treatment
- Legacy service removed
- Port 8080 no longer accessible

Evidence_03_Archive_Hardened.png
- Validation of archive hardening
- Archive moved outside web root
- HTTP request returns 404

Evidence_04_UFW_Configuration.png
- UFW firewall configuration
- Default deny incoming
- HTTP traffic allowed

Evidence_05_Backup_Created.png
- Backup archive successfully created

Evidence_06_Portal_Removed_Before_Restore.png
- Portal content intentionally removed
- Recovery test failure state

Evidence_07_Recovery_Success.png
- Backup restoration successful
- Portal functionality restored

Evidence_13_NGINX_Access_Log.png
- NGINX access log validation
- Recorded requests captured successfully

Additional Supporting Evidence
- Ubuntu_IP_Address.png
- NGINX_Running.png
- Northbridge_Portal.png
- Archive_Accessible.png
- Kali_Network_Interfaces.png
- Network_Connectivity_Test.png

Notes
- Risk treatments implemented: Avoidance, Mitigation, Transfer, and Acceptance.
- Backup and recovery testing completed successfully.
- Logging validation completed using NGINX access logs.
- Financial analysis values were provided as assignment assumptions.

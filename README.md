# printer-management-automation
A script to check toner levels of networked printers

In addition to the ps1 file, there must also be a printers.txt file, which should include both the printer name (or IP address) and the corresponding OID separated by a Tab
for example:
printer1_ip	1.3.6.1.2.1.43.11.1.1.9.1
printer2_ip	1.3.6.1.2.1.43.11.1.1.9.1
printer3_ip	1.3.6.1.2.1.43.11.1.1.9.1

where printer1_ip is either the printer name or the printer IP address and the 1.3.6.1.2.1.43.11.1.1.9.1 is the OID for toner for your specific printer make/model

# SNMP-Prober
The script is to probe an SNMP agent and find the rate of change for several counters between successive probes/ samples and the OID's are of type Counter32, Counter64, Guage, Octet_Str and this code handles the system wrap around that is when the OID goes from high value to low value and system restart and SysUpTime.

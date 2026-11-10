# Printer shows "Offline" — but it is switched on

1. **Check the printer's own display.** If it shows an error (paper jam, toner, no Wi-Fi), fix that first — Windows only repeats what the printer reports.
2. **Wi-Fi printers:** check the printer is on the same Wi-Fi as the PC. After a router restart or password change, the printer often stays offline until it rejoins.
3. **Turn off "Use Printer Offline":** Settings → Bluetooth & devices → Printers & scanners → your printer → Open print queue → Printer menu → untick "Use Printer Offline" if it is set.
4. **Check the SNMP trap (very common):** Printer properties → Ports → Configure Port → untick "SNMP Status Enabled". With SNMP on, Windows marks many printers offline even though they print fine.
5. **Restart both** the printer and the Print Spooler service (see `Clear-PrintQueue.ps1` in the it-support-toolkit repo).
6. **Still offline?** Print the printer's network configuration page from its own menu and compare the IP address with the port in Windows — after a router change they often no longer match.

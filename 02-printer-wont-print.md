# The printer won't print — step by step

1. **The basics:** printer is on, has paper, no error light, and (for Wi-Fi printers) is connected to the same network as the PC.
2. **Check the queue.** Settings → Bluetooth & devices → Printers & scanners → your printer → Open print queue. Cancel any job showing "Error".
3. **Make sure it is the default** and not set to "Use Printer Offline" (in the queue window's Printer menu, untick it if set).
4. **Restart the Print Spooler** — or run `Clear-PrintQueue.ps1` from the it-support-toolkit repo in this profile.
5. **Print a test page** from the printer properties.
6. **Still stuck?** Remove the printer in Settings and add it again — this reinstalls the driver cleanly and fixes most remaining cases.

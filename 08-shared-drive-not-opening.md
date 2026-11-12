# Shared drive / network folder will not open

1. **Read the exact error.** "Access denied", "network path not found" and "the account is locked" are three different problems with three different fixes.
2. **Check you are on the right network** — office LAN, office Wi-Fi or VPN. A home Wi-Fi without VPN cannot see office drives.
3. **Try the address directly:** press `Win + R`, type the path (e.g. `\\server\share`) and Enter. If that works but the drive letter does not, only the mapping is broken — disconnect and re-map the drive.
4. **Wrong saved password is very common** after a password change: open Credential Manager → Windows Credentials, remove the old entry for that server, then open the folder again and sign in fresh.
5. **Restart the PC once.** A stale connection from before a password or VPN change often clears only with a real Restart.
6. **Everyone affected?** Then it is the server or the network, not your PC — report it once to IT with the exact error text and time, instead of everyone trying fixes.

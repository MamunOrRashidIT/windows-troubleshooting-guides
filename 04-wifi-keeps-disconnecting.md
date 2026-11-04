# Wi-Fi keeps disconnecting

1. **Restart both** the PC and the router (unplug the router for 30 seconds). This alone fixes most drops.
2. **Forget and rejoin the network.** Settings → Network & internet → Wi-Fi → Manage known networks → Forget, then connect again and re-enter the password.
3. **Move the adapter off power-saving.** Device Manager → your Wi-Fi adapter → Properties → Power Management → untick "Allow the computer to turn off this device to save power".
4. **Update the Wi-Fi driver** from the laptop maker's website (not a driver-booster tool).
5. **Check distance and band.** 5 GHz is faster but shorter-range; if you are far from the router, try the 2.4 GHz network.
6. **Renew the connection** with `Reset-Network.ps1` from the it-support-toolkit repo in this profile.
7. **Does every device drop?** Then it is the router or the line, not your PC — that is a call to the internet provider.

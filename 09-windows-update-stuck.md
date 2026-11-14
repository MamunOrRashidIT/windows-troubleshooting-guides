# Windows Update is stuck at the same percentage

1. **Wait once, properly.** A big feature update can sit at one percentage for a long time while the disk is working. If the disk light/activity is busy, give it at least 2 hours.
2. **Restart once** — a real Restart, then check Settings → Windows Update again. Many "stuck" updates finish during that restart.
3. **Free up space:** an update needs roughly 10 GB free on C:. If the drive is nearly full, updates stall silently (see guide 01 and `Check-DiskSpace.ps1`).
4. **Disconnect extra USB devices** (drives, docks, printers) and try again — a device driver can block the update.
5. **Check the error code** shown under the failed update and note it exactly — e.g. 0x80070005 and 0x800f081f need completely different fixes.
6. **Still stuck after all that?** Do not force power off repeatedly and do not use "update fixer" downloads from forums. Give IT the error code, the update's KB number and since when it has been stuck.

# Outlook is not sending emails

1. **Look at the Outbox.** If a message with a very large attachment is stuck there, everything behind it waits. Move it to Drafts, send the small mails, then deal with the large one separately.
2. **Check the status bar** at the bottom of Outlook: if it says "Working Offline", go to the Send/Receive tab and click **Work Offline** to switch it off.
3. **Press Send/Receive (F9)** and read any error message in full — the error code is the best clue.
4. **Check your internet** in the browser. Outlook cannot send if the network is down.
5. **Restart Outlook**, then restart the PC if that does not help.
6. **Still failing?** Create a new Outlook profile (Control Panel → Mail → Show Profiles → Add) — a damaged profile is a frequent cause, and a new profile keeps all server mail intact for Exchange/Microsoft 365 accounts.

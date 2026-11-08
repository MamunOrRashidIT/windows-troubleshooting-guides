# Blue screen (BSOD) — first steps before panicking

1. **Write down the stop code** shown at the bottom (e.g. MEMORY_MANAGEMENT, IRQL_NOT_LESS_OR_EQUAL). The code is the single best clue — note it exactly.
2. **Let it restart.** One single blue screen after an update is often a one-off. Note the date and time.
3. **What changed just before?** New hardware, a new driver, a Windows update or a new app in the last days is the most common trigger. Uninstall or roll back that one thing first.
4. **Check for updates again** — Settings → Windows Update. A faulty update is often fixed by the next one.
5. **Run a memory check:** press `Win + R`, type `mdsched.exe`, choose "Restart now and check for problems". Faulty RAM causes repeat blue screens.
6. **It keeps happening?** Open Event Viewer → Windows Logs → System and look for red errors at the crash times. Give support the stop code, the times, and what changed — that shortens the repair a lot.
7. **Do not** install "driver booster" tools or registry cleaners — they make blue screens worse, not better.

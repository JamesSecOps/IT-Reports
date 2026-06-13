# Windows Update broke Drivers
Updates 2026-05 Preview Update (KB5089573) (26200.8524), 2026-05 NET Framework
Preview Update (KB5092427), and 2026-02 Critical Update (KB5078674) were installed
successfully. After the updates, 9 devices were without drivers.

#Client Reported Issue:
Client stated the computer ran laggy and no sound after doing Windows updates.

#Root Caused Analysis:
Updates 2026-05 Preview Update (KB5089573) (26200.8524), 2026-05 NET Framework
Preview Update (KB5092427), and 2026-02 Critical Update (KB5078674) were installed
successfully. After the updates, 9 devices were without drivers.
After identifying all missing device, I downloaded all missing latest drivers and installed
them. This resolves the audio issue and performance issue.

#Diagnostics Performed:
-Action: Installed all missing drivers
Results: Installed correctly. All devices are working properly.
Notes: Video Card, Chipsets, and SerialIO had missing drivers. Video card was passing the
audio through the HDMI cable. This is why the client had no sound.

-Action: Performed System File Check
Results: 0 files were corrupted.
Notes: Windows integrity not compromised.

-Action: Virus, Malware, etc scans
Results: No threats detected.
Notes: System clean and no quarantine files.

-Action: O/S Hardening
Results: All Apps and O/S is fully updated.
Notes: Windows Updates, MS Store Updates, & Terminal: Winget upgrades

-Action: Dust Removal
Results: PC internal systems cleaned.
Notes: removed buildup layers of dust inside the PC.

#Repair Outcome:
After installing all missing drivers, the computer returned back to normal operations.
Client was pleased with the results.
=End of Report=

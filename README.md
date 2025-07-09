============================
PathSeer v1.04.1 (Kernel Rev 1.05)
Created by: Entity_of_Fire
Compiled: July 2025
Platform: Windows 98SE
============================

Overview:
---------
PathSeer is a native Win32 utility that lists active processes and their associated file paths. 
Built for legacy environments, this release finalizes core functionality while introducing new 
ritual triggers and cleaner snapshot logic. Designed for 98SE

What's New (Kernel Rev 1.05):
-----------------------------
- Process path bug fixed (no longer shows PathSeer.exe for all entries)
- Per-process snapshot enumeration using TH32CS_SNAPMODULE
- Ambient trigger: Press Ctrl + Shift + V to play 'The Microsoft Sound.wav'
- Hidden lore dialog displays internal build revision and timestamp
- Enhanced version stamping in EXE metadata and About dialog
- Saves full path listing to PathSeer_Log.txt

System Requirements:
---------------------
- Windows 98SE (recommended); Windows ME/2000/XP untested
- Optional: .NET Framework 2.0 and Windows Installer 2.0 (included)
- At least 16MB RAM
- Sound card required for ambient playback
- Admin access not required; runs natively

Files Included:
---------------
- PathSeer.exe
- The Microsoft Sound.wav (optional trigger)
- Optional: dotnetfx20.exe
- Optional: WinInstaller20.exe


Usage:
------
Run PathSeer.exe from installed folder.  
Listbox populates with active processes and their EXE paths.  
Click "Save to File" to export process info to PathSeer_Log.txt  
Press Ctrl + Shift + V while focused to activate internal ritual dialog.

Notes:
------
- Windows 95 is not supported.
- If sound doesn't play, ensure 'winmm.dll' is present and audio drivers are installed.
- The .NET Framework installer is optional and only needed for certain UI enhancements.

License:
--------
Released as-is. Use, adapt, and preserve freely.
May be archived, forked, or bundled with other digital relics.

(c) 2025 Entity_of_Fire

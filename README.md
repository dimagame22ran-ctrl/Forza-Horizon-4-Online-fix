# Forza-Horizon-4-Online-fix
FH4 Online Fix is a lightweight tool for Forza Horizon 4 Steam Edition. It helps diagnose and fix common multiplayer connection errors, Xbox Live issues, and Teredo problems. Features one-click network repair, automatic backups, and easy restoration. No game files are modified.
FH4 ONLINE FIX v1.1 - STEAM / WINDOWS 10-11
===========================================

A small Windows network troubleshooting utility for Forza Horizon 4 (Steam).
It is NOT a replacement for game servers or a game patch. It cannot guarantee
an online connection when the cause is NAT, CGNAT, an ISP, account access or
remote game services.

INSTALL / USE
1. Extract the entire ZIP into a separate folder (not the game folder).
2. Close Forza Horizon 4.
3. Double-click START_FH4_FIX.cmd.
4. Click CHECK. If problems are found, use REPAIR.
5. Approve the Windows administrator prompt if you agree to the changes.
6. Restart Steam and FH4, then test multiplayer.

LANGUAGES
- First launch: English by default.
- Use the Language menu in the upper-right corner: English / Русский.
- The interface, diagnostic messages and troubleshooting help switch immediately.
- Your selection is remembered across restarts if Windows permits saving it.
- Language preference: %LOCALAPPDATA%\FH4OnlineFix\settings.json

FEATURES
- Checks IP Helper and Xbox Live network services.
- Checks DNS resolution for Steam and Microsoft (not actual matchmaking).
- Displays Teredo status without changing its configuration.
- Warns about some active VPN/virtual network adapters.
- Enables important network services only if Windows has disabled them.
- Clears the Windows DNS cache.
- Backs up changed service startup settings to
  %ProgramData%\FH4OnlineFix\service-backup.json
- RESTORE reverts changed service startup settings.
- REPORT saves a text diagnostic log in the currently selected language.

SAFETY AND LIMITATIONS
- Does not modify game EXEs, game files, Steam licences or paid DLC.
- Does not disable Windows Firewall, change router ports, open DMZ or
  reset WinSock or TCP/IP settings.
- RESTORE reverts startup types only; it does not stop services or undo a
  temporary DNS cache flush.
- ExecutionPolicy Bypass applies only to the launched PowerShell process.
- Source code can be inspected directly: FH4_Online_Fix.ps1.
- The program and its network repairs have not been verified on every Windows
  configuration. Changes require your confirmation.

IF IT DOESN'T HELP
1. Sign out and back into Microsoft/Xbox in the FH4 startup menu.
2. Verify the game files through Steam Properties > Installed Files.
3. Test without a VPN, if one is enabled.
4. Restart your PC and router, or test another network to isolate NAT/ISP.
5. Contact https://support.forzamotorsport.net/ with the saved report.

Independent community utility. Not affiliated with Microsoft, Xbox,
Steam or Playground Games.

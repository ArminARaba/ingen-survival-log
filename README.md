# InGen Survival Log

Welcome to the InGen Survival Log, an overlay and telemetry tracker built specifically for "The Isle" (Gateway Map) and integrated with the bosch-island.com map tracker.

This software consists of two parts: a large Background Controller window (used for secure, manual authentication on the Bosch Island website) and the overlay window.

---

## 🚀 Step-By-Step Launch Guide

1. Install the software to any folder on your computer.
2. Right-click `InGen Survival Log.exe` and select **Run as Administrator** (important if you are playing the game in full-screen mode). Although borderless mode is recommended if you're using the software.
3. Upon launch, two windows will open. Use the large window to log into your Bosch Island account.
4. Spawn into the map with your deino. Once the map page loads and you are spawned, the small overlay will automatically link and turn ONLINE.
5. Safely **MINIMIZE** the large controller window to your taskbar. Do not close it, as closing either window will safely exit the application.

---

## ⌨️ Global Keyboard Shortcuts (Hotkeys)

The software features powerful global hotkeys that work even while you are active inside the game window.

| Hotkey | Action | Description |
| :--- | :--- | :--- |
| **`ALT + M`** | Toggle Click-Through | **Default (Locked):** Ghost layer, clicks pass through to the game, RED border. <br>**Unlocked:** Interactive mode to drag/reposition or click buttons, YELLOW border. |
| **`ALT + C`** | Toggle Streamer Mode | Instantly hides the sensitive 'Server Name' and 'Telemetry Link' status rows to protect from stream-snipers. |
| **`ALT + L`** | Toggle Sector Info | Instantly hides or shows the 'Sector / Region' name row. |
| **`ALT + S`** | Toggle Statistics | Instantly collapses or reveals the entire vertical statistics block (Current Run, PB, Avg Survival, Ratio, Incidents, Deaths). |
| **`ALT + P`** | Toggle Path Visuals | Dynamically turns on/off the red dashed trail tracking line on the map. |
| **`ALT + 1`** | Confirm Dialog (YES) | Starts the timer when a biosignal is detected, or confirms your casualty. No mouse movement required. |
| **`ALT + 2`** | Cancel Dialog (NO) | Dismisses the spawn or death confirmation prompt. |

---

## 🛠️ OS-Specific Troubleshooting & Tips

* **Windows SmartScreen Warning:** Because this is an independent, non-commercial passion project, it does not have an expensive Microsoft digital signature. Windows Defender might block it at first with a Blue Screen. **Fix:** Click "More Info", then click "Run Anyway".
* **Hotkeys not working In-Game:** The Isle uses Easy Anti-Cheat (EAC), which occasionally intercepts keyboard hooks from third-party overlays. **Fix:** Close the app completely, right-click the executable, and select "Run as Administrator".
* **Overlay Window Frozen or Stuck:** This software is currently in its Beta phase. If an unexpected error occurs or the windows fail to close normally. **Fix:** Open Windows Task Manager (`Ctrl + Shift + Esc`), look for "InGen Survival Log", right-click it, and select "End Task".

---

## ⚖️ Legal & Privacy Disclaimer

* **Privacy:** This app acts exactly like an isolated web browser. It does not collect, log, or transmit your passwords or credentials. Your login process happens directly and securely on the official Bosch Island servers.
* **Fair Play:** This tool is 100% compliant with anti-cheat policies. It does not inject code into the game memory, modify game files, or automate any in-game actions. It is strictly a visual layout companion.

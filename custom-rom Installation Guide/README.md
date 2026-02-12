#### **Revised "Fail-Proof" Personal Reminder**

1. **Preparation:** `adb devices` -> `adb reboot bootloader`.
2. **Enter Recovery:** `fastboot boot recovery.img`.
3. **The Clean Wipe:**
   - Wipe **Dalvik** and **Cache**.s
   - **Format Data** (Type "yes").
   - **CRITICAL:** `Reboot -> Recovery` (Wait for OrangeFox to reload).
4. **Sideload:**
   - Menu -> ADB Sideload -> Swipe.
   - `adb sideload EvolutionX_spes.zip`.
5. **Post-Flash (Optional but recommended):**
   - If you want to keep OrangeFox, flash the **OrangeFox Zip** immediately after the ROM (before rebooting).
   - Go to **Wipe** and **Format Data** one last time if moving from MIUI to a Custom ROM to prevent encryption issues.
6. **Reboot:** System. 

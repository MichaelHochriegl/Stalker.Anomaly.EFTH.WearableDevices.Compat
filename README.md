# WearableDevices - EFT Health System Compatibility

Compatibility mod that brings the EFT Health System display over to the Promin device.
It removes the HUD mannequin that EFT Health System normally displays.

## Installation

1. Install EFT Health System and its prerequisites using its normal instructions.
   Resolve BHS/GAMMA health-simulation conflicts as required by EFT; this addon
   does not disable a second health simulation.
2. Install Wearable Devices and its prerequisites.
3. Install this folder as a separate MO2 mod (gamedata must be at its root).
   Place it below both mods and patches that replace the EFT overlay below.
4. In MO2's Conflicts view, this addon must win:
   - gamedata/scripts/zzzz_efth_hud_overlay.script
5. Equip a powered Promin (either tier), and use Wearable Devices' normal inspect
   and page controls. No new key binding or MCM setting is required.



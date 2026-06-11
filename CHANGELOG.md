# Changelog

All notable changes to Ally Center will be documented in this file.

## [1.3.0] - 2026-06-11

### New Features

- Restore saved hardware settings on plugin startup (RGB, CPU boost, SMT, charge limit, TDP, fan)
- Auto-detect ROG Ally vs ROG Xbox Ally X and apply matching TDP profiles (up to 35W on Xbox Ally X)

### Improvements

- Dynamic TDP slider limits based on detected device
- Added Balanced performance preset for ROG Xbox Ally X

## [1.1.0] - 2026-01-03

### New Features

- Added RGB speed slider - control how fast animated effects run (Pulse, Spectrum, Wave, Flash)
- Added CPU Settings section with SMT and CPU Boost toggles

### Bug Fixes

- Fixed fan presets - Quiet, Balanced, and Performance now work correctly
- Fixed RGB Battery Level effect to properly show green (full) to red (empty)

### Improvements

- Cleaner popup dialogs for Device Info and About screens
- Added release automation script for developers

### Removed

- Removed Controller section (gyroscope and vibration were not functional)

---

## [1.0.0] - Initial Release

### Features

- **RGB Lighting** - Color picker, brightness control, and animated effects
- **Battery Health** - Monitor battery status and set charge limits
- **Performance Profiles** - Quick TDP presets (Silent, Balanced, Turbo, Max)
- **Fan Control** - Choose between Quiet, Balanced, Performance, or Auto
- **Download Mode** - Turn off screen while downloading games
- **Device Info** - View hardware and system information
- **Persistent Settings** - All settings saved across reboots

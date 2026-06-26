# DXH Tablet Changelog

## v1.0.0 - Refactor Milestone

### Changed
- Split JavaScript into modular files
- Split CSS into modular files
- Reduced core.js to a lightweight bootstrap object
- Separated tablet, setup, popup, home and status bar logic
- Improved project structure for future expansion
- Prepared architecture for lock screen, settings and apps

### Developer Notes
- HTML remains a single index.html
- All future apps will continue using:
  - html/js/apps/
  - html/css/apps/
  - client/apps/
  - server/apps/
- New modules can now be added without modifying core.js

## v1.0.0 - Stage 7 Home App Launcher

### Added
- Installed apps server callback
- Home screen app grid
- Tablet dock
- App icon rendering
- Basic app opening/closing
- Placeholder app screens

## v1.0.0 - Stage 6 Setup Wizard

### Added
- Post-account setup wizard
- Lock method selection
- PIN setup validation
- Fingerprint setup option
- Wallpaper selection
- Light/dark mode setup
- Colour theme setup
- Portrait/landscape setup
- Sound/volume/notification setup
- Setup preference saving

## v1.0.0 - Stage 5 Account System

### Added
- Account creation
- Email exists popup
- Existing account login
- Account-to-tablet linking
- Default settings creation
- Default app installation
- Multi-device login handling

## v1.0.0 - Stage 4 Boot Flow

### Added
- Boot routing callback
- Setup screen route
- Login screen route
- Lock screen route
- Home screen route
- Basic clock/date display

## v1.0.0 - Stage 3 Tablet Metadata

### Added
- Tablet serial generation
- Tablet item metadata saving
- Device database sync
- Default tablet model/name/storage metadata

## v1.0.0 - Stage 2 SQL Foundation

### Added
- Full SQL schema
- Device table
- Account table
- Session table
- Settings table
- Installed apps table
- Permissions table
- Notifications table
- Files table
- Photos table
- Notes table
- Emails table

## v1.0.0 - Stage 1 Foundation

### Added
- Initial resource structure
- fxmanifest
- config.lua
- apps.lua
- SQL foundation
- Basic NUI tablet frame
- Boot animation
- Basic tablet item open event


---

# Current Progress

✅ Foundation
✅ SQL
✅ Device Metadata
✅ Boot Sequence
✅ Account System
✅ Setup Wizard
✅ Home Screen
✅ Modular Architecture

⬜ Lock Screen
⬜ Settings App
⬜ App Store
⬜ Email
⬜ Camera
⬜ Gallery
⬜ Files
⬜ Notes
⬜ Calculator
⬜ Permissions
⬜ Notifications
⬜ Developer Mode
⬜ Dark Web
⬜ Banking
⬜ API
⬜ Documentation
⬜ Release Candidate

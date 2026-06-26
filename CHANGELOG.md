# DXH Tablet Changelog

### Known Issues
- Change password dialog temporarily disabled while dialog input system is being stabilised.

## v1.0.0 - Stage 10D App Details

### Added
- Dedicated App Details page.
- App icon, description and developer information.
- Version information.
- Category information.
- Permissions display.
- Back navigation to the App Store.
- Install/Open button moved into the App Details page.

### Changed
- Clicking an app card now opens a detailed information page instead of immediately installing the application.
- App Store navigation now follows a mobile operating system style layout.

## v1.0.0 - Stage 10C App Store Improvements

### Added
- Featured Apps section.
- Reusable App Store card builder.
- Search improvements.
- Category filtering improvements.
- Foundation for install status handling.

### Changed
- Refactored App Store card generation into a reusable function.
- Prepared App Store architecture for dedicated application pages.

## v1.0.0 - Stage 10B App Store UI

### Added
- App Store interface
- App search
- App categories
- App cards
- Installed app status
- Install app server event
- App Store refresh after install

## v1.0.0 - Stage 10A App Registry Foundation

### Added
- Centralised tablet app registry architecture.
- App metadata support including name, description, version, category and permissions.
- Foundation for dynamic app installation and management.
- Preparation for automatic App Store population.
- Support for protected, removable and hidden applications.
- Version tracking for installed applications.
- Category support for future App Store filtering.
- Developer metadata support for future app information pages.

### Changed
- App definitions are now designed to act as the single source of truth for all tablet applications.
- Home Screen and App Store architecture prepared to read from the central app registry.
- Reduced future duplication by storing app information in one location.

### Developer Notes
- This stage introduces the foundation for the DXH Tablet package management system.
- Future app installations, updates, permissions and hidden applications will utilise this registry.

## v1.0.0 - Stage 9G Multi-Field Dialogs

### Added
- Multi-field dialog support
- Proper Change PIN dialog
- Confirm PIN validation
- Change Password dialog placeholder

### Changed
- Dialog system now supports multiple inputs

## v1.0.0 - Stage 9F Dialog System

### Added
- Reusable DXH dialog system
- Dialog support for confirmation actions
- Dialog support for text/password/PIN input
- Backwards compatibility with existing popup calls
- Foundation for future permission prompts, password changes and multi-field dialogs

### Changed
- Popup system now routes through the new dialog system

## v1.0.0 - Stage 9E Lock Settings

### Added
- Change lock method from Settings
- Set No Lock
- Set 4-digit PIN
- Set Fingerprint
- PIN validation popup
- Lock settings save to SQL

## v1.0.0 - Stage 9D Popup Improvements

### Added
- Popup input field support
- Custom wallpaper URL entry dialog
- Dynamic popup input types
- Input placeholder support
- Input maximum length support

### Changed
- Popup system now supports both confirmation dialogs and text input dialogs.
- Custom wallpaper selection now uses the in-app popup system instead of browser prompts.

## v1.0.0 - Stage 9C Wallpaper System

### Added
- Wallpaper picker in Settings
- Support for four default wallpapers
- Custom wallpaper URL support
- Live wallpaper updates
- Wallpaper persistence across tablet sessions
- Wallpaper applied to both Home and Lock Screen

### Changed
- Wallpaper system now updates instantly without reopening the tablet.
- Home Screen and Lock Screen now share the same wallpaper source.

## v1.0.0 - Stage 9B Functional Settings

### Added
- Generic save setting system
- Live theme saving
- Live accent colour saving
- Orientation saving
- Sound toggle saving
- Volume saving
- Notification toggle saving
- Lock method saving
- Logout account support

### Changed
- Settings app now reads and refreshes live account/device data

## v1.0.0 - Stage 9A Settings UI

### Added
- Settings app layout
- Settings sidebar navigation
- Account settings page
- Personalisation page
- Display page
- Sound & Notifications page
- Storage & Files page
- Security & Privacy page
- Device Info page
- Developer Options placeholder

## v1.0.0 - Stage 8B.2 Lock Screen

### Added
- Standby-style lock screen
- Notification centre preview
- Tap-to-unlock behaviour
- Bottom-sheet PIN authentication
- Bottom-sheet fingerprint authentication
- Wrong PIN shake feedback
- Back button from authentication sheet

### Changed
- Lock screen no longer shows keypad/fingerprint immediately
- All lock screen behaviour remains inside lockscreen.js/css

## v1.0.0 - Stage 8B.1 Lock Screen

### Added
- Lock screen method routing
- No-lock unlock button
- 4-digit PIN keypad
- PIN dot indicators
- Incorrect PIN feedback
- Wrong PIN shake animation
- Fake fingerprint hold-to-unlock
- Lock screen notification placeholder

## v1.0.0 - Stage 8A OS State Manager

### Added
- Tablet OS state manager
- Central state tracking
- CLOSED, BOOT, SETUP, LOGIN, LOCK, HOME and APP states
- Cleaner page routing
- App close now returns through HOME state

### Changed
- Boot routing now uses `setState`
- Home loading now happens from the HOME state

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

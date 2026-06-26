# 📱 DXH Tablet

> A modern, modular, Android-inspired tablet resource for FiveM built for QBCore.

DXH Tablet is designed to behave like a **real tablet**, not just another menu. Every tablet is a physical inventory item with its own serial number, while players can securely sign into their own account to access their personal data from any compatible tablet.

Whether you're roleplaying as a police officer, mechanic, racer, criminal, or business owner, DXH Tablet aims to become the central hub for everyday roleplay.

---

# ✨ Features

## Device System

* 📱 Physical usable tablet item
* 🔢 Unique serial number for every tablet
* 💾 Device metadata stored on the tablet
* 🔄 First-time boot sequence
* 🔐 Optional screen lock
* 📂 Configurable tablet models
* ⚙️ Fully configurable through `config.lua`

---

## Account System

* Create a DXH account
* Login using an existing account
* Email based authentication
* Password protected accounts
* Move your account between tablets
* Sign out before selling or lending your tablet
* Optional single-device login
* Optional multiple-device login

---

## Setup Wizard

When a tablet is used for the first time:

* Create or login to an account
* Choose lock method
* Select wallpaper
* Select theme
* Choose accent colour
* Choose portrait or landscape
* Configure sound
* Configure notifications

Exactly how you would set up a real tablet.

---

## Home Screen

* Android-inspired layout
* App dock
* Dynamic app grid
* Real-time clock
* Dynamic date
* Smooth animations
* Portrait & Landscape support

---

## App Store

Install only the apps you need.

Server owners can configure:

* Default installed apps
* Available apps
* Hidden apps
* Job-specific apps

Perfect for keeping the tablet clean while still allowing hundreds of optional applications.

---

# 📦 Planned Core Apps

* ⚙️ Settings
* 📧 Email
* 📷 Camera
* 🖼 Gallery
* 📁 Files
* 📝 Notes
* 🧮 Calculator
* 🌐 Browser
* 🛒 App Store
* 🏦 Banking
* 🔔 Notifications

---

# 👮 Job Applications

DXH Tablet has been designed to support dedicated applications for every role.

Examples include:

* Police MDT
* Mechanic
* Real Estate
* Ambulance
* Taxi
* Dealership
* Storage Units
* Racing
* Businesses
* Government
* Administration

Server owners can install only the apps they require.

---

# 🌑 Hidden Features

Not every feature is visible...

Developer Mode can be enabled by repeatedly tapping the tablet version inside Settings, unlocking hidden functionality.

Examples include:

* Developer Options
* VPN
* Hidden applications
* Dark Web

The Dark Web application can then be installed through the App Store, opening entirely new roleplay opportunities.

---

# 📸 Media System

Players will be able to:

* Take photos
* Switch between front and rear cameras
* Store photos
* Share photos between supported apps
* Email photos
* Upload photos to supported social media apps
* Use photos as roleplay evidence

---

# 🔔 Notification System

A modern notification system inspired by Android.

* Live notifications
* Notification history
* Permission requests
* Silent mode
* Notification settings
* Per-app notifications

---

# 🔒 Security

Choose how your tablet unlocks.

* No Lock
* 4 Digit PIN
* Fingerprint

Future updates may include additional security options.

---

# 🎨 Personalisation

Every player can customise their tablet.

* Light Mode
* Dark Mode
* Multiple accent colours
* Built-in wallpapers
* Custom wallpaper URLs
* Portrait mode
* Landscape mode

---

# ⚙️ Configuration

Almost everything can be customised through the configuration file.

Examples include:

* Default apps
* Default wallpapers
* Default theme
* Tablet models
* Storage size
* Single or multiple logins
* Notification defaults
* Sound defaults
* Wi-Fi behaviour
* Internet settings
* Developer options
* Job applications

---

# 🧩 Modular Architecture

DXH Tablet has been designed from the ground up to be modular.

```
dxh_tablet
│
├── client/
│   ├── main_cl.lua
│   └── apps/
│
├── server/
│   ├── main_sv.lua
│   └── apps/
│
├── html/
│   ├── index.html
│   ├── css/
│   │   ├── core.css
│   │   ├── setup.css
│   │   ├── home.css
│   │   ├── lockscreen.css
│   │   └── apps/
│   │
│   ├── js/
│   │   ├── core.js
│   │   ├── setup.js
│   │   ├── home.js
│   │   ├── tablet.js
│   │   └── apps/
│
├── shared/
├── sql.sql
├── config.lua
└── README.md
```

Every application follows the same modular structure, making future updates and customisation simple.

---

# 🔌 API

DXH Tablet has been built to work alongside other resources.

Future API support will allow resources to:

* Register applications
* Open applications
* Send notifications
* Request permissions
* Upload files
* Upload photos
* Save application data
* Communicate through events

This allows developers to create powerful integrations without modifying the core resource.

---

# 🚀 Roadmap

## Foundation

* ✅ Resource structure
* ✅ SQL database
* ✅ Device metadata
* ✅ Boot sequence
* ✅ Account system
* ✅ Setup wizard
* ✅ Modular architecture

## In Progress

* ⏳ Lock screen
* ⏳ Settings
* ⏳ App launcher

## Planned

* 📧 Email
* 📷 Camera
* 🖼 Gallery
* 📁 Files
* 📝 Notes
* 🧮 Calculator
* 🛒 App Store
* 🏦 Banking
* 🌐 Browser
* 🌑 Dark Web
* 👮 Job Apps
* 📱 Social Media
* 🔌 Public API
* 📖 Full documentation

---

# ❤️ Design Philosophy

DXH Tablet isn't intended to replace roleplay.

It's designed to enhance it.

Instead of opening menus, players interact with a device that behaves like a real tablet. Accounts persist across devices, applications are installed through an App Store, permissions work similarly to Android, and future applications can integrate seamlessly with other resources.

The goal is to create a tablet that feels believable, immersive, and enjoyable to use while remaining highly configurable for server owners and straightforward for developers to extend.

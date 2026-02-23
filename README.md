<!-- Improved compatibility of back to top link -->
<a id="readme-top"></a>

<p align="center">
<a href="https://github.com/hliriano03/rmz-modmenu-framework-public/stargazers">
<img alt="Stargazers" src="https://img.shields.io/github/stars/hliriano03/rmz-modmenu-framework-public.svg?style=for-the-badge" />
</a>
<a href="https://github.com/hliriano03/rmz-modmenu-framework-public/issues">
<img alt="Issues" src="https://img.shields.io/github/issues/hliriano03/rmz-modmenu-framework-public.svg?style=for-the-badge" />
</a>
<a href="https://github.com/hliriano03/rmz-modmenu-framework-public/blob/main/LICENSE">
<img alt="License" src="https://img.shields.io/badge/license-Closed%20Source-blue.svg?style=for-the-badge" />
</a>
</p>

<!-- PROJECT LOGO -->
<div align="center">
<h1 align="center">RMZ ModMenu Framework</h1>
<p align="center">
A modern, dark-themed mod menu framework for iOS
<br />
<br />
<a href="https://github.com/hliriano03/rmz-modmenu-framework-public/releases/latest"><strong>Download Latest Release</strong></a>
<br />
<br />
<a href="https://github.com/hliriano03/rmz-modmenu-framework-public/issues">Report Bug</a>
&middot;
<a href="https://github.com/hliriano03/rmz-modmenu-framework-public/issues">Request Feature</a>
</p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
<summary>Table of Contents</summary>
<ol>
<li><a href="#about-the-project">About The Project</a></li>
<li><a href="#features">Features</a></li>
<li>
<a href="#getting-started">Getting Started</a>
<ul>
<li><a href="#prerequisites">Prerequisites</a></li>
<li><a href="#installation">Installation</a></li>
</ul>
</li>
<li><a href="#usage">Usage</a></li>
<li><a href="#roadmap">Roadmap</a></li>
<li><a href="#license">License</a></li>
<li><a href="#contact">Contact</a></li>
</ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project

<!-- Replace with new v2 screenshots -->
<div align="center">
<img src="https://github.com/hliriano03/rmz-modmenu-framework-public/assets/39392181/REPLACE_WITH_NEW_SCREENSHOT" alt="RMZ ModMenu v2 Screenshot" style="width:30%;" />
</div>

<br />

RMZ ModMenu Framework v2 is a complete redesign of the original mod menu, built from the ground up with a focus on a clean, modern dark UI that feels native to iOS. The framework provides a fully featured overlay menu system with smooth animations, responsive scaling, and an intuitive layout — all while staying lightweight and non-intrusive.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- FEATURES -->
## Features

### Dark Modern Interface
A sleek dark theme with carefully chosen colors — deep blacks, charcoal grays, and vibrant accent colors for different information types (green for success, red for errors, blue for info). Rounded corners and subtle shadows give the menu a polished, native feel.

### Floating Action Button
A draggable floating button that serves as the entry point to the menu. It auto-snaps to the nearest screen edge after 2 seconds of inactivity and can be made invisible with a long press for a completely clean screen — tap the invisible zone to bring it back.

### Four Cheat Control Types
| Control | Description |
|---------|-------------|
| **Toggle** | Standard on/off switch with persistent state |
| **Slider** | Adjustable value range with live preview and configurable min/max/step |
| **Text Field** | Custom text input with keyboard-aware positioning |
| **Button** | One-tap action trigger for instant operations |

### Collapsible Sections
Cheats are organized into collapsible containers (Free / VIP) with smooth expand/collapse animations. Keeps the interface clean and uncluttered while providing quick access to everything.

### Shared Cheats
Cheats that share the same hook can be linked together — toggling one automatically toggles the others. Shared cheats are color-coded with matching overlay colors so users can easily identify which cheats act as a single group.

### Settings Submenu
A compact settings panel with five tabs:
- **Account** — User info, sign out, password management
- **Settings** — Framework preferences
- **Cheat Status** — Active cheats overview and framework version
- **About** — Framework information
- **Contact Us** — Support links

### Responsive Scaling
The UI automatically adapts to every iOS device — from iPhone SE to iPad. Smaller screens get a scaled-down layout applied to dimensions, fonts, padding, and shadows so everything stays proportional and usable.

### Smart Overlay System
The menu runs in its own overlay window with intelligent z-ordering:
- Touch passthrough when the menu isn't active — the host app works normally
- Keyboard-aware positioning — the menu moves out of the way when typing
- Orientation support — seamlessly adapts to portrait and landscape

### Alerts & Notifications
- **Alerts** — Modal dialogs with rich text support, scrollable content, and custom button layouts
- **Notifications** — Toast-style banners with blur backgrounds that stack from the top, auto-dismiss after 3 seconds, and support swipe-to-dismiss

### Smooth Animations
Every interaction is animated — spring animations on the floating button, ease-out curves on collapsible containers, fade transitions for visibility states, and smooth repositioning on orientation changes.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

Download the latest release by clicking [here](https://github.com/hliriano03/rmz-modmenu-framework-public/releases/latest).

### Prerequisites

- iOS 13.0 or later
- Jailbroken device (rootful, rootless, or roothide) **or** a sideloading method for non-jailbroken devices

### Installation

#### Jailbroken (Rootful & Rootless)

1. Download the `.deb` file from the [latest release](https://github.com/hliriano03/rmz-modmenu-framework-public/releases/latest)
2. Install using your preferred package manager (Cydia, Sileo, Zebra) or via Filza

#### Non-Jailbroken

1. Follow the tutorial [here](https://rizzmodz.com/topic/5-how-to-use-rmz-mod-menu-for-non-jailbreak-without-jit/#comment-14)
2. Use Sideloadly to install both the framework and the mod menu IPA

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->
## Usage

Once installed, launch the target app. The floating button will appear on screen:

1. **Tap** the floating button to open the menu
2. **Drag** the button anywhere on screen to reposition it
3. Browse cheats in the **Free** and **VIP** collapsible sections
4. Use **toggles**, **sliders**, **text fields**, or **buttons** to activate cheats
5. Access **Settings** from the menu footer for account and framework options
6. **Long press** the floating button to hide it for a clean screen

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/hliriano03/rmz-modmenu-framework-public/issues) for a list of proposed features and known issues.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->
## License

This project is closed source. All rights reserved.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->
## Contact

RizzModz — [rizzmodz.com](https://rizzmodz.com)

Project Link: [https://github.com/hliriano03/rmz-modmenu-framework-public](https://github.com/hliriano03/rmz-modmenu-framework-public)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

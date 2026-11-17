<div align="center">

# Atmosphère

### Custom Firmware for Nintendo Switch

An open-source custom firmware project for the Nintendo Switch, built around modular system components and homebrew support.

[Official GitHub Repository](https://github.com/Atmosphere-NX/Atmosphere) · [Releases](https://github.com/Atmosphere-NX/Atmosphere/releases) · [NH Switch Guide](https://switch.hacks.guide/)

</div>

## Product Overview

Atmosphère is an open-source custom firmware (CFW) for Nintendo Switch. It modifies and extends the Horizon operating system through a collection of components that replace or modify different parts of the console's software environment.

The project provides infrastructure for homebrew applications, custom system modules, filesystem modifications, and emulated NAND configurations.

The latest official release identified is **Atmosphère 1.12.2**, released November 11, 2026. It adds basic support for Nintendo Switch firmware 23.5.0.

## Technical Architecture

Atmosphère uses a modular architecture consisting of several major components:

- **Fusée:** First-stage loader responsible for loading and validating the second-stage custom TrustZone and system package.
- **Exosphère:** Customized TrustZone implementation providing a modified secure monitor.
- **Thermosphère:** Provides EL2-based emuNAND support, allowing NAND images to be redirected and virtualized.
- **Stratosphère:** Collection of custom system modules that extend kernel functionality and modify important system services.
- **Troposphère:** Application-level Horizon OS patches that implement additional CFW features.

## Key Features

- Custom firmware environment for Nintendo Switch.
- Homebrew application support.
- Custom system module support.
- EmuMMC and NAND redirection through Thermosphère.
- System-level patches and service modifications.
- Layered filesystem support for compatible game modifications.
- Integrated Homebrew Launcher components.
- Custom kernel and secure-monitor implementations.
- Cheat engine functionality through the included `dmnt` component.
- Compatibility updates for newer Horizon OS firmware releases.

## Module Overview

| Component | Primary Function |
|---|---|
| Fusée | First-stage bootloader |
| Exosphère | Customized secure monitor |
| Thermosphère | EmuNAND and virtualized NAND support |
| Stratosphère | Custom system modules |
| Troposphère | Application-level system patches |
| `dmnt` | Cheat engine functionality |
| Homebrew Launcher | Homebrew application launching |
| hbmenu | Homebrew Menu interface |

## Supported Platforms

- Nintendo Switch family running compatible Horizon OS firmware.
- Compatible original Switch hardware configurations.
- Compatible modchip-based Switch configurations.

Atmosphère is designed for Nintendo Switch. It is not a Nintendo Switch 2 custom firmware.

## Compatibility Information

The latest identified Atmosphère release is **1.12.2**.

| Item | Compatibility |
|---|---|
| Atmosphère version | 1.12.2 |
| Latest documented firmware support | 23.5.0 |
| Homebrew Launcher | 2.4.5 |
| Homebrew Menu | 3.6.1 |
| Boot payload | `fusee.bin` |
| Bootloader integration | hekate |
| EmuMMC | Supported |
| Custom system modules | Supported |

Firmware compatibility does not guarantee that every third-party sysmodule, overlay, theme, or homebrew application will work. Check the compatibility requirements of each additional component before updating.

## Technical Specifications

| Specification | Details |
|---|---|
| Project | Atmosphère |
| Developer | Atmosphere-NX contributors |
| Latest identified version | 1.12.2 |
| Platform | Nintendo Switch |
| Operating system environment | Horizon OS |
| Architecture | ARM64 |
| Project type | Custom firmware |
| License | GPL-2.0, with documented exceptions |
| Main language | C and C++ |
| Boot payload | `fusee.bin` |
| Homebrew support | Yes |
| EmuMMC support | Yes |

## Installation Guide

1. Check the console's hardware compatibility and current firmware version.
2. Read the current NH Switch Guide instructions for the appropriate hardware configuration.
3. Prepare a compatible microSD card using the guide's recommended format and partition layout.
4. Download the official Atmosphère release package.
5. Extract the package contents to the root of the microSD card.
6. Obtain the matching `fusee.bin` payload from the official release.
7. Prepare the compatible bootloader configuration, such as hekate, if required by the selected setup.
8. Follow the appropriate boot procedure for the console's hardware.
9. Launch Atmosphère and verify the installed version in the system environment.

For existing installations, follow the official update guide and check all component compatibility before updating system firmware.

## FAQ

### What is Atmosphère?

Atmosphère is an open-source custom firmware for Nintendo Switch that modifies and extends the Horizon OS environment.

### Does Atmosphère support homebrew?

Yes. It includes Homebrew Launcher components and supports compatible homebrew applications.

### What is emuMMC?

emuMMC is an emulated NAND environment. Atmosphère provides its underlying support through Thermosphère.

### Is hekate required?

Atmosphère and hekate are separate projects. The boot method depends on the console's hardware and configuration.

### What is `fusee.bin`?

It is Atmosphère's boot payload. The older `fusee-primary` payload is obsolete and should not be used with current releases.

### Does Atmosphère support firmware 23.5.0?

Yes. Atmosphère 1.12.2 added basic support for firmware 23.5.0.

### Does Atmosphère work on Nintendo Switch 2?

No. Atmosphère is a Nintendo Switch project and should not be treated as Switch 2 firmware.

### Where can I download Atmosphère?

Use the official Atmosphere-NX GitHub repository and its releases page.

## SEO Keywords

Atmosphère, Atmosphere CFW, Nintendo Switch custom firmware, Switch homebrew, Switch CFW, Atmosphère 1.12.2, Nintendo Switch homebrew launcher, emuMMC, Thermosphère, Exosphère, Fusée, Stratosphère, Horizon OS, hekate integration, Switch firmware 23.5.0

<div align="center">

---

**Atmosphère** · Nintendo Switch Custom Firmware

[Official GitHub Repository](https://github.com/Atmosphere-NX/Atmosphere)

</div>

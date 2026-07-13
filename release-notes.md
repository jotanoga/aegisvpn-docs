
# AegisVPN Release Notes

**Version:** 1.0  
**Release Date:** July 10, 2026

---

# Overview

Version 2.0 introduces significant improvements to security, performance and usability. This major release includes a redesigned interface, enhanced connection stability, new privacy features and expanded platform support.

Users are encouraged to update to the latest version to benefit from improved security and compatibility.

---

# What's New

## Redesigned User Interface

The application has been completely redesigned to improve usability and navigation.

Highlights include:

- Modern dashboard
- Simplified navigation
- Faster access to frequently used settings
- Improved accessibility
- Dark and Light themes

---

## Smart Server Selection

A new **Smart Server** option automatically connects users to the fastest available server based on:

- Current location
- Server load
- Latency
- Network conditions

---

## Multi-Hop VPN

Added support for **Multi-Hop connections**.

Traffic can now be routed through two VPN servers instead of one, providing an additional layer of privacy.

---

## Threat Protection

New integrated protection against:

- Malicious websites
- Phishing domains
- Known malware hosts
- Advertising trackers

Threat Protection can be enabled from:

**Settings → Privacy & Security**

---

## Connection Diagnostics

Added a built-in diagnostics tool that helps users identify:

- Network issues
- DNS problems
- VPN protocol conflicts
- Firewall restrictions

Diagnostic reports can be shared directly with Support.

---

## Expanded Server Network

New server locations added:

- Argentina
- Chile
- Portugal
- South Korea
- Singapore
- South Africa

---

# Improvements

## Faster Connection Times

Connection speed has been improved by approximately **30%** when using WireGuard®.

---

## Better Server Switching

Switching between VPN servers is now smoother and no longer requires restarting the application.

---

## Reduced Memory Usage

Optimized background services reduce memory consumption by approximately **20%** on Windows and macOS.

---

## Improved Auto-Connect

Auto-Connect now detects:

- Trusted Wi-Fi networks
- Public Wi-Fi
- Ethernet connections
- Network changes

More reliable automatic reconnection has also been implemented.

---

## Enhanced Split Tunneling

Split Tunneling now supports:

- Individual applications
- Entire folders
- Custom executable paths

Configuration is also easier thanks to the redesigned interface.

---

## Improved Notifications

Notifications have been redesigned to provide clearer information while reducing unnecessary alerts.

---

# Security Updates

- Updated encryption libraries.
- Improved certificate validation.
- Enhanced DNS leak protection.
- Stronger authentication process.
- Updated VPN protocol implementations.
- Various security hardening improvements.

---

# Bug Fixes

Resolved issues including:

- Application freezing after sleep mode.
- Incorrect connection status display.
- Occasional login failures after password reset.
- Slow server list loading.
- Rare DNS leak affecting specific configurations.
- Auto-Connect failing after Windows startup.
- Crash when changing VPN protocols during an active session.
- Incorrect language selection after updates.
- Notification duplication.
- Improved application stability across all supported platforms.

---

# Platform Support

## Added

- Windows 11 25H2
- macOS Sequoia
- Ubuntu 24.04 LTS

## Improved

- Android 16 compatibility
- iOS 20 compatibility

---

# Known Issues

The following issues are currently under investigation:

- Multi-Hop is not available on Linux.
- Some public Wi-Fi networks may require reconnecting after captive portal authentication.
- Split Tunneling is not supported for Microsoft Store applications on Windows.
- Threat Protection may conflict with certain third-party DNS filtering services.

These issues will be addressed in future releases.

---

# Upgrade Notes

No manual configuration is required when upgrading from Version 1.x.

User settings, preferences and saved servers will be preserved automatically.

Users are nevertheless encouraged to:

- Restart their device after upgrading.
- Verify that Auto-Connect and Kill Switch remain enabled.
- Review the new Threat Protection settings.

---

# Deprecated Features

The following features have been removed:

- Legacy OpenVPN configuration importer.
- Automatic protocol selection based solely on connection speed.

These features have been replaced by Smart Server Selection and the new protocol management engine.

---

# Looking Ahead

Version 2.1 is expected to include:

- Browser extension improvements
- Dedicated gaming servers
- Expanded Threat Protection capabilities
- Additional language support
- Performance optimizations for Linux
- Improved enterprise deployment tools

---

# Need Help?

If you experience issues after updating:

- Review the [Troubleshooting Guide](troubleshooting-guide.md).
- Visit the [Knowledge Base](knowledge-base-md).
- Contact [AegisVPN Support](mailto:support@aegisvpn.com) with your diagnostic report.
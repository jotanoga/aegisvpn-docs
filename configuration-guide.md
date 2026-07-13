# AegisVPN Configuration Guide

**Version:** 1.0  
**Last updated:** July 10, 2026

---

# Overview

This guide explains how to configure AegisVPN after installation.

Proper configuration ensures the best balance between security, privacy and performance according to your personal or business requirements.

---

# Before You Begin

Before configuring AegisVPN:

- Install the latest version of the application.
- Sign in to your account.
- Verify that your subscription is active.
- Ensure your device has Internet access.

---

# Open the Settings Menu

1. Launch **AegisVPN**.
2. Sign in if prompted.
3. Click the **Settings** icon in the upper-right corner.
4. Select the category you want to configure.

---

# VPN Protocol

## Overview

AegisVPN supports multiple VPN protocols. Each one offers different advantages depending on your needs.

Available protocols include:

- WireGuard®
- OpenVPN UDP
- OpenVPN TCP
- IKEv2

---

## Recommended Settings

### WireGuard®

Best for:

- Everyday browsing
- Streaming
- Gaming
- Maximum performance

### OpenVPN UDP

Best for:

- General security
- Stable connections
- Public Wi-Fi

### OpenVPN TCP

Best for:

- Restricted networks
- Corporate environments
- Firewalls

### IKEv2

Best for:

- Mobile devices
- Network switching
- Stable mobile connections

---

## Change the VPN Protocol

1. Open **Settings**.
2. Select **Connection**.
3. Click **VPN Protocol**.
4. Choose your preferred protocol.
5. Save your changes.

Reconnect to apply the new protocol.

---

# Auto-Connect

## Overview

Auto-Connect automatically establishes a VPN connection whenever predefined conditions are met.

---

## Enable Auto-Connect

1. Open **Settings**.
2. Select **Connection**.
3. Enable **Auto-Connect**.

---

## Available Options

Automatically connect when:

- Windows starts
- The application launches
- Joining unsecured Wi-Fi
- Joining any Wi-Fi network
- Ethernet disconnects

---

# Kill Switch

## Overview

Kill Switch blocks all Internet traffic if the VPN connection unexpectedly disconnects.

This prevents accidental IP exposure.

---

## Enable Kill Switch

1. Open **Settings**.
2. Select **Privacy & Security**.
3. Enable **Kill Switch**.

---

## Recommended

Keep Kill Switch enabled at all times unless troubleshooting connectivity issues.

---

# Split Tunneling

## Overview

Split Tunneling lets you decide which applications use the VPN connection.

Applications not selected continue using your normal Internet connection.

---

## Configure Split Tunneling

1. Open **Settings**.
2. Select **Split Tunneling**.
3. Enable the feature.
4. Add applications.

Example:

| Application | VPN |
|--------------|-----|
| Chrome | Yes |
| Microsoft Teams | No |
| Steam | Yes |
| Outlook | No |

---

# DNS Settings

## Overview

AegisVPN uses encrypted private DNS servers by default.

This prevents:

- DNS leaks
- ISP monitoring
- DNS manipulation

---

## Available Options

- AegisVPN Secure DNS (Recommended)
- Automatic DNS
- Custom DNS

---

## Configure Custom DNS

1. Open **Settings**.
2. Select **DNS**.
3. Choose **Custom DNS**.
4. Enter the server addresses.
5. Save.

---

# Dedicated IP

## Overview

A Dedicated IP assigns a permanent VPN IP address exclusively to your account.

Benefits include:

- Easier access to corporate systems
- Fewer CAPTCHA challenges
- Reduced login verification requests
- Stable remote access

---

## Enable Dedicated IP

1. Open **Server Selection**.
2. Select **Dedicated IP**.
3. Choose your assigned location.
4. Connect.

---

# Launch on Startup

To launch AegisVPN automatically:

1. Open **General Settings**.
2. Enable **Launch at Startup**.

---

# Notifications

Configure application notifications:

- Connection established
- Connection lost
- Available updates
- Security alerts

Notifications can be enabled or disabled individually.

---

# Appearance

Available themes:

- Light
- Dark
- System Default

Language options can also be configured from this menu.

---

# Check for Updates

To manually check for updates:

1. Open **Settings**.
2. Select **About**.
3. Click **Check for Updates**.

Keeping AegisVPN updated ensures optimal security and performance.

---

# Restore Default Settings

If you experience configuration issues:

1. Open **Settings**.
2. Select **Advanced**.
3. Click **Restore Default Settings**.
4. Confirm.

This restores all configuration options while keeping your account information intact.

---

# Best Practice Recommendations

For most users, the recommended configuration is:

- WireGuard® protocol
- Kill Switch enabled
- Auto-Connect enabled
- AegisVPN Secure DNS
- Automatic updates enabled
- Launch at startup enabled

This configuration provides the best balance between performance, security and ease of use.

---

# Troubleshooting Configuration Issues

## Changes are not applied

Disconnect and reconnect the VPN.

---

## Auto-Connect is not working

Verify that:

- Auto-Connect is enabled.
- The operating system allows background startup.
- AegisVPN is allowed during startup.

---

## Internet stops after disconnecting

If Kill Switch is enabled:

1. Reconnect to the VPN.

or

2. Disable Kill Switch temporarily.

---

## Split Tunneling does not work

Verify that:

- The application has been added correctly.
- The application has been restarted after configuration.

---

# Related Documentation

- [Getting Started Guide](getting-started-guide.md)
- [Installation Guide](installation-guide.md)
- [User Guide](user-guide.md)
- [Troubleshooting Guide](troubleshooting-guide.md)
- [Frequently Asked Questions](frequently-asked-questions.md)
- [Knowledge Base](knowledge-base.md)
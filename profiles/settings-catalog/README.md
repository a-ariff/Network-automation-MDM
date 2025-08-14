# Settings Catalog Profiles

This directory contains configuration profiles using Intune's Settings Catalog format.

## Overview

Settings Catalog provides a modern approach to managing device settings in Microsoft Intune, offering:
- Granular control over device configurations
- Easy-to-use interface for policy creation
- Better visibility into configured settings
- Support for the latest Windows features

## Profile Types

- **Security Settings**: Baseline security configurations
- **Application Settings**: App-specific configurations
- **Network Settings**: Wi-Fi, VPN, and network configurations
- **Device Restrictions**: Feature and functionality limitations

## Usage

1. Import profiles into Microsoft Intune admin center
2. Customize settings as needed for your environment
3. Assign to appropriate device/user groups
4. Monitor deployment status

## File Naming Convention

- Use descriptive names: `[Category]-[Purpose]-[Version].json`
- Example: `Security-Baseline-v1.0.json`

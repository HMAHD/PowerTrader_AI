# Installation

PowerTrader AI provides easy-to-use installers for both Windows and macOS platforms.

## Choose Your Platform

=== "Windows"

    ### Windows Installer (Recommended)

    1. Download `PowerTrader_AI_Setup.exe` from [GitHub Releases](https://github.com/HMAHD/PowerTrader_AI/releases)

    2. Double-click the installer to run it

    3. If Windows SmartScreen appears, click "More info" then "Run anyway"
        - This warning is normal for unsigned open-source software

    4. Follow the installation wizard:
        - Accept the license agreement
        - Choose installation location (default: `C:\Program Files\PowerTrader_AI`)
        - Select optional desktop shortcut
        - Click Install

    5. Launch PowerTrader AI:
        - From Start Menu: Search for "PowerTrader AI"
        - From Desktop: Double-click the PowerTrader AI icon (if selected)

    ### Portable Version (Advanced)

    1. Download `PowerTrader_AI-Windows-x64.zip`
    2. Extract to your preferred location
    3. Run `PowerTrader_AI\PowerTrader_AI.exe`

=== "macOS"

    ### DMG Installer (Recommended)

    1. Download the appropriate DMG for your Mac:
        - Intel Macs: `PowerTrader_AI-Intel.dmg`
        - Apple Silicon (M1/M2/M3): `PowerTrader_AI-ARM64.dmg`

    2. Double-click the DMG file to mount it

    3. Drag the PowerTrader AI icon to the Applications folder

    4. Eject the DMG

    5. Launch PowerTrader AI:
        - Open Applications folder
        - Right-click (or Control+click) on PowerTrader AI
        - Select "Open" from the menu
        - Click "Open" in the security dialog

        !!! note "First Launch Only"
            The right-click method is only needed the first time. After that, you can double-click normally.

    ### Portable Version (Advanced)

    1. Download the appropriate ZIP:
        - Intel: `PowerTrader_AI-macOS-Intel.zip`
        - Apple Silicon: `PowerTrader_AI-macOS-ARM64.zip`

    2. Extract the ZIP file
    3. Move `PowerTrader_AI.app` to Applications
    4. Right-click and "Open" (first time only)

## Verification

After installation, verify PowerTrader AI launches correctly:

1. Start the application
2. You should see the main GUI window
3. The window may show warnings about missing configuration files - this is normal

## Next Steps

- [Quick Start Guide](quick-start.md) - Set up your API keys
- [System Requirements](requirements.md) - Detailed system requirements

## Troubleshooting

### Windows

**Issue**: "Windows protected your PC" message

**Solution**: Click "More info" and then "Run anyway". This is a standard warning for unsigned applications.

**Issue**: Antivirus blocks the installer

**Solution**: Add an exception for PowerTrader AI in your antivirus software. The software is open-source and safe.

### macOS

**Issue**: "PowerTrader AI cannot be opened because it is from an unidentified developer"

**Solution**: Right-click the app and select "Open" instead of double-clicking.

**Issue**: Application won't start

**Solution**: Check Console.app for error messages. Common issues:
- Missing dependencies (usually auto-included)
- Insufficient permissions (check file permissions)

### Still Having Issues?

- Check the [Troubleshooting Guide](../user-guide/troubleshooting.md)
- [Open an issue](https://github.com/HMAHD/PowerTrader_AI/issues) on GitHub
- Search [existing issues](https://github.com/HMAHD/PowerTrader_AI/issues?q=is%3Aissue)

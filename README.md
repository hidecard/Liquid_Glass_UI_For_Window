# DWMBlurGlass User Guide

DWMBlurGlass is a free and open-source application that enables customizable blur effects for Windows title bars and borders, bringing back the classic Aero glass effect with modern enhancements.

## Features

- **Custom Blur Effects**: Apply blur effects to window title bars and borders
- **Windows 10/11 Support**: Works on both Windows 10 and Windows 11
- **Aero Reflection**: Enable classic Windows 7-style Aero reflection effects
- **Color Customization**: Customize blend colors for light and dark modes
- **Symbol File Management**: Automatic symbol file downloading and management
- **Multiple Languages**: Supports 15+ languages including English, Chinese, Japanese, Korean, German, French, Spanish, and more

## Installation

1. **Download** the latest release from the releases page
2. **Extract** the files to a directory outside your user folder (not in `C:\Users\` or subdirectories)
3. **Run** the application as administrator
4. **Click Install** to install the DWM modifications
5. **Download symbols** from the "Symbol" tab if prompted

⚠️ **Important**: Due to DWM security restrictions, the application must be placed outside user directories.

## Usage

### General Settings
- **Install/Uninstall**: Enable or disable DWMBlurGlass effects
- **Blur Radius**: Adjust the global blur intensity
- **Override DWMAPI**: Override Windows 11 Mica effects with custom blur
- **Extend to Borders**: Apply effects to window borders (Windows 10)

### Advanced Settings
- **Aero Reflection**: Enable Windows 7-style reflection effects
- **Title Bar Buttons**: Restore classic Windows 7 button styling and glow effects
- **Color Modes**: Customize colors for light and dark themes
- **Blend Colors**: Set custom title bar blend colors for active/inactive states

### Symbol Files
- **Auto-Download**: Automatically download required symbol files from Microsoft servers
- **Status Check**: Verify if current symbols are valid for your Windows version
- **Manual Refresh**: Re-download symbols after Windows updates

### Configuration
- **Export/Import**: Save and restore your settings
- **Reset**: Restore default configuration
- **Language**: Change interface language

## Troubleshooting

### Common Issues

**Installation Failed**
- Ensure the application is not in a user directory
- Run as administrator
- Check Windows version compatibility

**Symbols Invalid**
- Go to Symbol tab and download fresh symbols
- Required after Windows updates
- Check internet connection for downloads

**Effects Not Working**
- Verify installation status shows "Installed"
- Download valid symbol files
- Restart Windows after installation

### Error Messages

- `MiaoUI initialization failed`: UI library error - try restarting as admin
- `Symbol loading failed`: Download symbols from Symbol tab
- `DWM authorization isolation`: Move application outside user directories

## System Requirements

- Windows 10 version 1903 or later
- Windows 11 (all versions)
- Administrator privileges required
- Internet connection for symbol downloads

## License

This software is licensed under LGPLv3 - see the About section for details.

## Support

For issues and feature requests, please visit the project repository or check the About section for more information.
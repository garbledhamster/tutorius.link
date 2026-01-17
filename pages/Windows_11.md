# Windows 11 Quick Reference Guide

## Essential Keyboard Shortcuts

### Navigation & Window Management
- **Win + D** - Show/Hide Desktop
- **Win + E** - Open File Explorer
- **Win + L** - Lock Computer
- **Win + Tab** - Open Task View
- **Win + I** - Open Settings
- **Alt + Tab** - Switch between open apps
- **Win + Arrow Keys** - Snap windows (Left/Right/Up/Down)
- **Win + Shift + Arrow** - Move window to another monitor

### Multitasking & Productivity
- **Win + V** - Open Clipboard History (must be enabled)
- **Win + Period (.)** - Open Emoji Picker
- **Win + Semicolon (;)** - Open Emoji Picker (alternative)
- **Win + A** - Open Quick Settings
- **Win + N** - Open Notification Center
- **Win + W** - Open Widgets Panel
- **Win + Z** - Open Snap Layouts (new in Windows 11)

### Virtual Desktops
- **Win + Ctrl + D** - Create new Virtual Desktop
- **Win + Ctrl + F4** - Close current Virtual Desktop
- **Win + Ctrl + Left/Right** - Switch between Virtual Desktops

### Screenshot & Screen Recording
- **Win + Shift + S** - Open Snipping Tool
- **Win + PrtScn** - Take full screenshot (saves to Pictures/Screenshots)
- **Win + Alt + R** - Start/Stop recording with Xbox Game Bar
- **Win + G** - Open Xbox Game Bar

## File Explorer Tips

### Quick Access Shortcuts
- **Ctrl + N** - Open new window
- **Ctrl + W** - Close current window
- **Ctrl + E** - Focus search box
- **Alt + D** - Select address bar
- **Alt + Up** - Go up one folder level
- **Alt + Left/Right** - Navigate back/forward
- **F2** - Rename selected item
- **F11** - Toggle full screen

### Navigation & Selection
- **Ctrl + A** - Select all items
- **Ctrl + Shift + N** - Create new folder
- **Shift + Delete** - Permanently delete (bypass Recycle Bin)
- **Ctrl + Shift + Click** - Select range of items

## Command Line Quick Start

### Opening Terminal/PowerShell
- **Win + X, then I** - Open Windows Terminal (Admin)
- **Win + X, then A** - Open PowerShell/Terminal (Admin)
- In File Explorer: Type `cmd` or `powershell` in address bar

### Essential Commands
```powershell
# System Information
systeminfo
Get-ComputerInfo

# Network
ipconfig /all
Test-Connection google.com

# File Management
Get-ChildItem  # List files (like ls)
Copy-Item      # Copy files
Move-Item      # Move files
Remove-Item    # Delete files

# Process Management
Get-Process
Stop-Process -Name "processname"
```

## Settings & Customization

### System Settings Quick Access
1. **Start → Settings → System → Display** - Adjust screen resolution, brightness
2. **Start → Settings → Personalization** - Themes, colors, backgrounds
3. **Start → Settings → Apps → Startup** - Manage startup programs
4. **Start → Settings → Privacy & Security** - Privacy controls

### Enable Hidden Features
**Clipboard History:**
Settings → System → Clipboard → Turn on "Clipboard history"

**Focus Assist:**
Settings → System → Focus assist → Set your preferences

**God Mode:**
Create folder named: `GodMode.{ED7BA470-8E54-465E-825C-99712043E01C}`

## Troubleshooting & Maintenance

### Common Issues

**Slow Performance:**
1. Press **Win + X** → Task Manager
2. Check CPU, Memory, Disk usage
3. End unnecessary processes
4. Check "Startup" tab to disable startup programs

**Windows Update Issues:**
1. Open Settings → Windows Update
2. Click "Check for updates"
3. Run Windows Update Troubleshooter
4. If stuck: `wuauclt.exe /updatenow` in Command Prompt

**Network Problems:**
```powershell
# Reset network
ipconfig /release
ipconfig /renew
ipconfig /flushdns
netsh winsock reset
```

### Disk Cleanup
1. Search "Disk Cleanup"
2. Select drive (usually C:)
3. Check items to delete
4. Click "Clean up system files" for more options

### System File Checker
```cmd
# Run as Administrator
sfc /scannow
DISM /Online /Cleanup-Image /RestoreHealth
```

## Touch Gestures (for Touchscreen/Touchpad)

### Touchpad Gestures
- **Two-finger tap** - Right-click
- **Two-finger scroll** - Scroll up/down
- **Pinch zoom** - Zoom in/out
- **Three-finger swipe up** - Task View
- **Three-finger swipe down** - Show Desktop
- **Three-finger swipe left/right** - Switch between apps
- **Four-finger tap** - Open Action Center

## Quick Tips

### Productivity Hacks
1. **Pin frequently used apps** to Taskbar (right-click app → Pin to taskbar)
2. **Use Windows Search** - Just press Win and start typing
3. **Customize Start Menu** - Right-click tiles to resize or unpin
4. **Enable Dark Mode** - Settings → Personalization → Colors → Dark
5. **Set up Multiple Desktops** for different workflows (Work, Personal, etc.)

### Security Best Practices
- Keep Windows updated
- Enable Windows Defender
- Use a Standard account for daily tasks
- Enable BitLocker for drive encryption
- Use a password manager
- Enable Windows Hello (Fingerprint/Face recognition)

## Additional Resources

### Built-in Apps Worth Using
- **Snipping Tool** - Screenshots with annotations
- **Windows Terminal** - Modern command-line interface
- **PowerToys** - Microsoft's free utility toolkit
- **Quick Assist** - Remote assistance tool
- **Your Phone** - Connect Android phone

### Keyboard Shortcut Cheat Sheet
Press **Win + F1** to open Windows Help (or search "Windows keyboard shortcuts")

---

*Last updated: 2025*

# macOS Quick Reference Guide

## Essential Keyboard Shortcuts

### Navigation & Window Management
- **⌘ + Space** - Open Spotlight Search
- **⌘ + Tab** - Switch between apps
- **⌘ + `** - Switch between windows of same app
- **⌘ + Q** - Quit application
- **⌘ + W** - Close current window
- **⌘ + M** - Minimize window
- **⌘ + H** - Hide application
- **⌘ + Option + H** - Hide all other apps
- **Control + ←/→** - Switch between Spaces/Desktops
- **Control + ↑** - Mission Control

### Mission Control & Spaces
- **F3** or **Control + ↑** - Open Mission Control
- **Control + ←/→** - Navigate between Desktops
- **Control + ↓** - Show all windows of current app
- **Control + F3** - Show Desktop
- **⌘ + Mission Control** - Show Desktop

### Finder Shortcuts
- **⌘ + N** - New Finder window
- **⌘ + T** - New Finder tab
- **⌘ + Shift + N** - New folder
- **⌘ + Delete** - Move to Trash
- **⌘ + Shift + Delete** - Empty Trash
- **⌘ + Option + Shift + Delete** - Empty Trash without confirmation
- **⌘ + Shift + G** - Go to folder (type path)
- **⌘ + Shift + .** - Show/Hide hidden files

### Common Locations
- **⌘ + Shift + H** - Home folder
- **⌘ + Shift + D** - Desktop
- **⌘ + Shift + O** - Documents
- **⌘ + Shift + U** - Utilities
- **⌘ + Shift + A** - Applications
- **⌘ + Shift + C** - Computer

### Text Editing
- **⌘ + C** - Copy
- **⌘ + V** - Paste
- **⌘ + X** - Cut
- **⌘ + Z** - Undo
- **⌘ + Shift + Z** - Redo
- **⌘ + A** - Select all
- **⌘ + F** - Find
- **⌘ + ←/→** - Move to beginning/end of line
- **Option + ←/→** - Move by word
- **⌘ + ↑/↓** - Move to beginning/end of document

### Screenshots & Screen Recording
- **⌘ + Shift + 3** - Full screenshot
- **⌘ + Shift + 4** - Select area screenshot
- **⌘ + Shift + 4, then Space** - Capture window
- **⌘ + Shift + 5** - Screenshot & screen recording options
- **⌘ + Shift + 6** - Capture Touch Bar (MacBooks with Touch Bar)

### Spotlight & Search
- **⌘ + Space** - Open Spotlight
- **⌘ + Option + Space** - Open Finder search window

## Finder Tips & Tricks

### View Options
- **⌘ + 1** - Icon view
- **⌘ + 2** - List view
- **⌘ + 3** - Column view
- **⌘ + 4** - Gallery view
- **⌘ + J** - Show view options

### File Management
- **Space** - Quick Look (preview file)
- **Option + Space** - Quick Look in full screen
- **⌘ + O** - Open selected item
- **⌘ + I** - Get Info
- **⌘ + D** - Duplicate
- **⌘ + L** - Make Alias
- **⌘ + E** - Eject

### Advanced Features
- **Option + Drag** - Copy item (instead of move)
- **⌘ + Drag** - Move item without copying
- **⌘ + Click title** - Show path to current folder
- **⌘ + Click Dock icon** - Reveal in Finder

## Terminal Basics

### Opening Terminal
1. **⌘ + Space**, type "Terminal"
2. **⌘ + Shift + U** → Double-click Terminal
3. Finder → Applications → Utilities → Terminal

### Essential Commands
```bash
# Navigation
pwd                    # Print working directory
ls                     # List files
ls -la                # List all files with details
cd /path/to/folder    # Change directory
cd ~                   # Go to home directory
cd ..                  # Go up one level

# File Management
mkdir folder_name      # Create directory
touch file.txt        # Create file
cp source dest        # Copy file
mv source dest        # Move/rename file
rm file.txt           # Delete file
rm -rf folder/        # Delete folder (be careful!)

# System Information
top                    # Show processes
system_profiler       # System information
df -h                 # Disk usage
du -sh *              # Folder sizes

# Network
ping google.com       # Test connection
ifconfig              # Network configuration
curl url              # Download from URL

# Homebrew (Package Manager)
brew install package  # Install package
brew update          # Update Homebrew
brew upgrade         # Upgrade packages
brew list            # List installed packages
```

### Useful Terminal Shortcuts
- **Control + C** - Cancel current command
- **Control + D** - Exit terminal
- **Control + L** - Clear screen
- **Control + A** - Move to beginning of line
- **Control + E** - Move to end of line
- **Control + U** - Clear line before cursor
- **Control + K** - Clear line after cursor
- **Tab** - Auto-complete

## System Settings & Customization

### System Preferences Quick Access
1. ** → System Settings** (or **System Preferences** on older macOS)
2. Use Spotlight: **⌘ + Space**, type setting name

### Essential Settings

**Desktop & Dock:**
- Adjust Dock size and position
- Enable/disable auto-hide
- Configure hot corners

**Displays:**
- Resolution settings
- Night Shift (blue light filter)
- True Tone (color adjustment)

**Trackpad:**
- Enable tap to click
- Configure gestures
- Adjust tracking speed

**Keyboard:**
- Modifier keys
- Keyboard shortcuts
- Text replacements

**Privacy & Security:**
- App permissions
- FileVault encryption
- Firewall settings

### Hidden Features

**Enable path bar in Finder:**
```bash
View → Show Path Bar
```

**Enable status bar in Finder:**
```bash
View → Show Status Bar
```

**Create custom keyboard shortcuts:**
System Settings → Keyboard → Keyboard Shortcuts → App Shortcuts

**Take screenshot directly to clipboard:**
Add **Control** to any screenshot shortcut (e.g., **⌘ + Control + Shift + 3**)

## Trackpad Gestures

### Basic Gestures
- **One finger click** - Select
- **Two finger click** - Right-click (or Control + Click)
- **Two finger scroll** - Scroll vertically/horizontally
- **Pinch** - Zoom in/out

### Advanced Gestures
- **Two finger swipe left/right** - Navigate pages (Safari, etc.)
- **Three finger swipe up** - Mission Control
- **Three finger swipe down** - App Exposé
- **Four finger swipe left/right** - Switch between Desktops
- **Four finger pinch** - Show Desktop
- **Spread with thumb + 3 fingers** - Launchpad

## Spotlight Search Power Tips

### Quick Calculations
- Type math expressions: `45 * 89`, `sqrt(144)`, `25% of 200`

### Unit Conversions
- `50 USD to EUR`
- `10 miles to km`
- `72 fahrenheit to celsius`

### Dictionary & Definitions
- Type any word to see definition
- `define:[word]` for detailed definition

### File Search Operators
- `kind:pdf` - Find PDF files
- `created:today` - Files created today
- `modified:yesterday` - Files modified yesterday
- `author:name` - Files by author
- `size:>100MB` - Large files

## Troubleshooting & Maintenance

### Force Quit Applications
- **⌘ + Option + Esc** - Open Force Quit window
- Select app and click "Force Quit"
- Or in Terminal: `killall [app name]`

### Reset SMC (System Management Controller)
**For Macs with T2 chip or Apple Silicon:**
1. Shut down Mac
2. Wait 30 seconds
3. Turn on Mac

**For older Intel Macs:**
1. Shut down
2. Press Shift + Control + Option + Power for 10 seconds
3. Release and turn on

### Reset NVRAM/PRAM
1. Shut down Mac
2. Turn on and immediately press **⌘ + Option + P + R**
3. Hold for about 20 seconds
4. Release when you hear startup sound (or logo appears twice)

### Disk Utility
1. **⌘ + Space**, type "Disk Utility"
2. Select drive
3. Click "First Aid" to check/repair disk

### Safe Mode
1. Shut down Mac
2. Turn on and immediately hold **Shift**
3. Release when you see login window
4. To exit, restart normally

### Activity Monitor
- **⌘ + Space**, type "Activity Monitor"
- Check CPU, Memory, Energy, Disk, Network usage
- Force quit unresponsive apps

## Built-in Apps Worth Using

### Productivity
- **Preview** - View/edit PDFs and images (signatures, annotations)
- **Notes** - Quick note-taking with iCloud sync
- **Reminders** - Task management
- **Calendar** - Schedule management
- **Time Machine** - Automatic backups
- **TextEdit** - Simple text editor

### Utilities
- **Activity Monitor** - System resource monitoring
- **Console** - View system logs
- **Disk Utility** - Manage drives
- **Terminal** - Command line
- **Screenshot** - Advanced screenshot tools
- **Digital Color Meter** - Pick colors from screen

### Tips for Productivity
1. **Use Spotlight for everything** - Launch apps, calculate, convert
2. **Set up Hot Corners** - Quick access to Desktop, Mission Control
3. **Master Spaces** - Multiple desktops for different tasks
4. **Enable iCloud Drive** - Seamless file sync across devices
5. **Use Tags in Finder** - Color-code and organize files
6. **Learn Touch Bar shortcuts** (if applicable)

## Security Best Practices

- Keep macOS updated
- Enable FileVault disk encryption
- Use a strong user password
- Enable Firewall (Settings → Network → Firewall)
- Review app permissions regularly
- Use Safari's privacy features
- Enable Find My Mac
- Create Time Machine backups
- Be cautious with downloaded apps
- Use Touch ID/Face ID when available

## Additional Resources

### Homebrew (Package Manager)
Install from: [brew.sh](https://brew.sh)
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

### Useful Third-Party Apps
- **Rectangle** - Window management (free)
- **Alfred** - Spotlight replacement
- **iTerm2** - Terminal replacement
- **The Unarchiver** - Extract any archive
- **AppCleaner** - Completely remove apps

---

*Last updated: 2025 - Compatible with macOS Sonoma (14.x) and Sequoia (15.x)*

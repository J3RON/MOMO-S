# MOMO'S - Windows System Administration Toolkit

A comprehensive collection of batch scripts for Windows system administration, troubleshooting, and maintenance tasks.

## 🚀 Quick Start

1. Download or clone this repository
2. Run `MENU.bat` as Administrator
3. Select the tool you need from the menu

## ✨ Features

### 🌐 Network Tools
- IP renewal and release
- DNS cache flush
- Network interface reset
- Complete network diagnostics
- Connectivity testing
- One-press network repair

### 🛠️ System Maintenance
- **SFC Scan**: System File Checker for corrupted files
- **DISM Image Cleanup**: Check and restore system image health
- **Windows Update Reset**: Fix Windows Update service errors
- **RAM Diagnostics**: Memory testing utility

### 📊 System Information
- Full system report generation
- Hardware information (CPU, RAM, Disk)
- Network adapter details
- Installed software list
- Active processes and services
- Battery health reports

### 🔑 License Management
- Windows activation status checker
- Office license verification (Office 2010-2019)
- Product key display

### ⚙️ Service & Process Management
- Start/Stop/Restart Windows services
- Force-kill applications
- System restore access

### 👤 User Management
- Create new user accounts
- Add users to administrator group
- Custom workgroup assignment

### 🔒 Security & Storage
- BitLocker disable utility
- System event log collection

### 📦 Software Management
- Install software via WinGet
- Update all installed applications
- Bulk software updates

## 📋 Requirements

- **OS**: Windows 7 or later
- **Privileges**: Administrator rights (automatically requested)
- **Optional**: WinGet for software management features

## 🗂️ Project Structure

```
MOMO'S_TOOL_CMD PRO_VER/
├── MENU.bat                              # Main menu interface
└── ALL-TOOLS/
    ├── NETWORK/
    │   └── FIX-NETWORK-PB.CMD           # Network troubleshooting
    ├── STATUS/
    │   └── WINDOWS_AND_OFFICE_STATUS_x86_x64.bat
    ├── SYSTEM/
    │   ├── SERVICE/                      # Service management
    │   ├── UPDATE/                       # Update utilities
    │   ├── SYSFIX/                       # System repair tools
    │   ├── SYSINFO/                      # System information
    │   ├── USER/                         # User management
    │   ├── DISABLEBIT/                   # BitLocker tools
    │   └── TASKMANGER/                   # Process management
    └── MOOOM/                            
```

## 💻 Usage Examples

### Network Troubleshooting
```
1. Run MENU.bat
2. Select option 1 (NETWORK-PB)
3. Choose from 7 network repair options
```

### Creating a New User
```
1. Run MENU.bat
2. Select option 11 (USER-ADD)
3. Enter username, password, and workgroup
```

### System Health Check
```
1. Run MENU.bat
2. Select option 10 (SFC-SCAN) or option 9 (SYS-IMAGE-CLEAN-UP)
3. Wait for the scan to complete
```

## ⚠️ Important Notes

- **Always run as Administrator** - The script will automatically request elevation
- **System Restore Point** - Consider creating a restore point before running system repair tools
- **Backup Important Data** - Some operations may require system restart
- **Network Operations** - May temporarily disconnect your internet connection

## 👨‍💻 Author

**J3R0N**

## 🐛 Known Issues

- Some features require specific Windows versions or configurations

THANK YOU

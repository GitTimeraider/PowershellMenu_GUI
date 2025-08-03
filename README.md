# PowerShell Menu GUI

## 🎩 Overview

Welcome to a whimsical world where PowerShell scripts don their finest GUI attire! This repository provides a graphical menu system for PowerShell.

**A Mad Observation:** Why click through endless folders when you can have all your scripts dancing before you in a proper menu? Madness? Perhaps. Efficient? Absolutely!

## 🍄 Features

- **Visual Script Selection**
- **Customizable Menus**
- **User-Friendly Interface**
- **PowerShell Integration**

## 🐰 Requirements

Before tumbling down this particular rabbit hole, ensure you have:

- Windows PowerShell 5.1 or later
- .NET Framework (for GUI components)
- Administrative privileges (for certain script operations)
- A touch of madness (optional but recommended)

## 🫖 Installation

### Step 1: Download the Repository

Clone or download this repository to your preferred location:

`git clone https://github.com/GitTimeraider/PowershellMenu_GUI.git`

### Step 2: Unblock the Scripts

*"Why, sometimes I've believed as many as six impossible things before breakfast... but Windows security policies aren't one of them!"*

`Get-ChildItem -Path ".\PowershellMenu_GUI" -Recurse | Unblock-File`

### Step 3: Run the Main Script

Execute the main menu script:

`.\PowershellMenu_GUI.ps1`

## ⚙️ Configuration

*"Take your time," said the Hatter. "Configure it properly, or you'll be late for everything!"*

### Menu Structure

The menu system can be customized by editing the configuration sections:

| Component | Purpose |
|-----------|---------|
| Menu Items | Define which scripts appear in the GUI |
| Categories | Group related scripts together |
| Descriptions | Add helpful text for each menu option |
| Icons | Customize visual elements (if supported) |

### Adding Your Own Scripts

1. Place your PowerShell scripts in the designated folder
2. Update the menu configuration to include your scripts
3. Restart the GUI to see your changes

## 🎪 Usage

### Basic Navigation

- **Click** menu items to execute scripts
- **Hover** for descriptions and tooltips
- **Right-click** for additional options (if implemented)

### Advanced Features

- Script parameters can be passed through the GUI
- Output is displayed in a dedicated console window
- Error handling prevents the entire menu from crashing

## 🔧 Customization

*"I've had an idea! Not a good idea, mind you, but an idea nonetheless!"*

### Theming

Modify the appearance by adjusting:
- Color schemes
- Font styles
- Window dimensions
- Button layouts

### Extending Functionality

The framework supports:
- Adding new menu categories
- Implementing sub-menus
- Creating custom dialog boxes
- Integrating with other PowerShell modules

## ⚠️ Mad Warnings

- Some antivirus software may flag PowerShell GUIs as suspicious (they're just jealous of the pretty buttons)
- Running scripts with elevated privileges requires proper caution
- The GUI may behave unexpectedly if scripts take too long to execute

## 🐛 Troubleshooting

### Common Issues

**GUI Won't Launch**
- Check PowerShell execution policy: `Get-ExecutionPolicy`
- Ensure .NET Framework is installed
- Verify script isn't blocked by Windows

**Scripts Don't Execute**
- Confirm script paths are correct
- Check for required permissions
- Review error messages in the output window

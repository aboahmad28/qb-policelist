# QB-PoliceList

## Overview
QB-PoliceList is a comprehensive police management system for FiveM servers using the QBCore framework. This script provides law enforcement officers with a dynamic and interactive interface to manage their duties, track fellow officers, respond to emergencies, and coordinate operations efficiently.

[Preview](https://youtu.be/FRT327GHDjE?si=2qwLa6TcqCGz2Lx7)

Created by Coast Side Dev (Abo Ahmad, For4, and Abo Tahsin), this resource enhances the roleplay experience for police departments by offering real-time officer tracking, panic button functionality, and department-specific organization.

## Features

### Core Functionality
- **Real-time Officer Tracking**: View all on-duty officers with their current status, location, and department
- **Interactive Map**: See officer positions on a custom map of Los Santos
- **Panic Button System**: Emergency alert system for officers in distress
- **Activity Log**: Track important events and officer activities
- **Multi-department Support**: Separate sections for LSPD, SAHP, and BCSO
- **Duty Management**: Toggle duty status directly from the interface
- **Radio Integration**: Join radio channels with a single click

### User Interface
- **Customizable Sidebar**: Resize and position the interface to your preference
- **Responsive Design**: Clean and modern UI that adapts to different screen sizes
- **Bilingual Support**: Full support for both English and Arabic languages
- **Custom Notifications**: Built-in notification system with sound alerts

### Advanced Features
- **Officer Status Tracking**: See if officers are available, busy, or acting as dispatch
- **Transport Information**: Shows if officers are on foot, in vehicles, or aircraft
- **Callsign Management**: Set and update officer callsigns
- **Settings Persistence**: User preferences are saved between sessions
- **Permission System**: Role-based access to different features

## Requirements
- QBCore Framework
- pma-voice (for radio functionality)
- A FiveM server running GTA5

## Installation

1. **Download the Resource**:
   - Download the `qb-policelist` folder

2. **Place in Resources**:
   - Add the folder to your server's resources directory

3. **Configure Server.cfg**:
   - Add `ensure qb-policelist` to your server.cfg file
   - Make sure it loads after `qb-core` and other dependencies

4. **Configure the Script**:
   - Open `config.lua` to customize settings according to your server's needs
   - Adjust department names, job grades, and UI preferences as needed

5. **Restart Your Server**:
   - Restart the server or use the `refresh` and `ensure qb-policelist` commands

## Usage

### Basic Controls
- **F6**: Open the police list interface
- **F7**: Open the interface with cursor enabled
- **ESC**: Hide the cursor but keep the interface open

### Officer Management
1. **View Officers**:
   - See all on-duty officers organized by department
   - Check their status, location, and callsign

2. **Update Your Status**:
   - Open Settings to toggle duty status, busy status, or dispatch mode
   - Update your callsign

3. **Emergency Response**:
   - Use the Panic Button when in danger
   - Respond to other officers' panic alerts
   - Set waypoints to officer locations

### Map Features
1. **Open the Map**:
   - Click the map icon in the top bar
   - View all officer positions on the Los Santos map

2. **Interact with Officers**:
   - Click on officer markers for more information
   - See vehicle information and heading direction

### Settings
Access the settings panel to configure:
- Duty status and availability
- UI appearance (transparent background)
- Call notifications and sounds
- Auto-delete time for panic alerts

## Configuration
The script is highly configurable through the `config.lua` file:

### General Settings
- Resource name, framework, and job name
- Update intervals and debug mode
- Default callsign and radio settings

### Department Settings
- Configure department names, icons, and colors
- Set up department mappings based on job grades

### Keybind Settings
- Customize keys for opening and closing the interface

### UI Settings
- Adjust colors, animations, and sidebar dimensions
- Configure notification type and duration

### Map Settings
- Enable/disable the map feature
- Set default zoom levels and marker appearances

### Advanced Settings
- Configure permissions based on rank
- Set up integrations with other resources
- Adjust performance and security settings

## Troubleshooting

### Common Issues
1. **Interface Not Showing**:
   - Ensure you have the police job assigned
   - Check keybinds in the config file
   - Verify the resource is started in your server.cfg

2. **Officers Not Appearing**:
   - Make sure officers have the correct job name (default: "police")
   - Check that they are on duty

3. **Panic Button Not Working**:
   - Verify that the panic button is enabled in the config
   - Check that you have dispatch permissions

4. **Map Not Loading**:
   - Ensure the map files are properly installed
   - Check browser console for any errors

### Support
For additional support or questions, contact the developers:
- Created by Coast Side Dev (Abo Ahmad, For4, and Abo Tahsin)

## License
This resource is protected under a commercial license. Unauthorized distribution or modification is prohibited.

---

*QB-PoliceList v1.0.0 - Enhancing police roleplay one officer at a time.*

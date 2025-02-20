# MST Data Usage Plugin for PHPNuxBill

## Overview
MST Data Usage is a powerful monitoring plugin for PHPNuxBill that provides real-time data usage tracking for Mikrotik hotspot users. This plugin seamlessly integrates with your PHPNuxBill dashboard, offering an intuitive interface to monitor and manage user connections.

## Features
- **Real-time Monitoring**: Track active hotspot users and their data usage in real-time
- **Data Usage Statistics**:
  - Download usage in human-readable format
  - Upload usage in human-readable format
  - Uptime tracking for each connection
- **User Management**:
  - View active connections
  - One-click user disconnection
  - MAC address tracking
  - IP address monitoring
- **Clean Interface**:
  - Integrated in PHPNuxBill's Network menu
  - Modern and responsive design
  - Easy-to-read data format

## Requirements
- PHPNuxBill version 2.0.0 or higher
- PHP version 7.2 or higher
- Mikrotik router with:
  - API access enabled
  - Hotspot configured
  - API port accessible (default: 8728)
- Valid router credentials in PHPNuxBill settings

## Installation
1. Download the `mst_data_usage.zip` file
2. Extract the contents
3. Copy files to your PHPNuxBill installation:
   ```
   system/plugin/mst_data_usage.php → [phpnuxbill]/system/plugin/
   system/plugin/ui/mst_data_usage.tpl → [phpnuxbill]/system/plugin/ui/
   ```
4. Clear your browser cache
5. Refresh your PHPNuxBill admin panel

## Configuration
1. Ensure your Mikrotik router is properly configured in PHPNuxBill:
   - Go to Settings > Router
   - Verify IP address is correct
   - Check API credentials
   - Make sure API port is accessible

## Usage Guide

### Accessing the Plugin
1. Log in to your PHPNuxBill admin panel
2. Navigate to Network > Data Usage Monitor

### Monitoring Users
The main interface displays:
- Username
- IP Address
- MAC Address
- Connection Duration (Uptime)
- Download Usage
- Upload Usage
- Action buttons

### Managing Connections
To disconnect a user:
1. Locate the user in the table
2. Click the "Disconnect" button in the Actions column
3. Confirm the disconnection

### Troubleshooting
If you encounter issues:
1. Verify Mikrotik router settings:
   - API access is enabled
   - Correct IP and port
   - Valid username and password
2. Check PHPNuxBill router configuration
3. Ensure hotspot is properly configured
4. Verify network connectivity between PHPNuxBill and router

## Support
For support:
- Create an issue in our GitHub repository
- Contact us at: [mycosoftofficial@gmail.com]
- Visit our website: [https://mycosofttechnologies.com]
- Whatsapp: [+256750501151]

## Contributing
We welcome contributions! Please:
1. Fork the repository
2. Create a feature branch
3. Submit a pull request

## License
This plugin is released under the MIT License.

## Credits
Developed by  Mycosoft Technologies:
- Website: [https://mycosofttechnologies.com/]
- Email: [mycosoftofficial@gmail.com]
- GitHub: [https://github.com/mycosoft]
- WhatsApp: [+256750501151]

## Changelog
### Version 1.0.0 (2024-02-20)
- Initial release
- Real-time data usage monitoring
- User disconnection feature
- Formatted data display
- Network menu integration

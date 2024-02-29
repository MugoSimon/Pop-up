---

# PowerShell Payment Monitoring Script

## Overview

This PowerShell script monitors a specific file (`cheq.out`) for changes and extracts relevant payment information. It provides real-time notifications and logging capabilities, making it suitable for monitoring payment transactions in various scenarios.

## Features

- **File Monitoring**: Monitors `cheq.out` file for changes related to payment transactions.
  
- **Notification System**: Displays popup notifications containing transaction details upon detecting changes.

- **Logging Functionality**: Logs script activities, including payment status changes and errors, to `cheqLogs.txt`.

- **Automatic File Handling**: Automatically creates log file and receipt directory if not found.

- **Timed Notifications**: Popup notifications automatically close after 5 seconds for a non-intrusive user experience.

## How to Run

1. **Clone the Repository**: Clone this repository to your local machine using `git clone`.

2. **Navigate to Directory**: Open PowerShell and navigate to the directory where the script is located.

3. **Run the Script**: Execute the following command to run the script:
   ```powershell
   .\payment_monitoring_script.ps1
   ```

4. **Ensure File Availability**: Make sure the `cheq.out` file is present in the specified location (`C:\Arcus2\cheq.out`).

5. **Monitor Notifications**: Once the script is running, it will continuously monitor the `cheq.out` file for changes and display popup notifications for payment transactions.

6. **Check Logs**: The script logs activities to `cheqLogs.txt`, located in `C:\scripts\`. Check this file for detailed information on script execution.

## Requirements

- PowerShell (Version 5.1 or higher)
- Windows Operating System

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

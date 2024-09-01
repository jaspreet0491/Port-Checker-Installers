# Port Checker Application

A versatile, cross-platform application developed using Python and PyQt5 to monitor and diagnose TCP and UDP ports on local and remote machines. This tool is designed to enhance network troubleshooting by providing an intuitive interface and real-time feedback on the status of network ports.

## Features

- **Local and Remote Port Checks**: Check the status of specified TCP and UDP ports on both local and remote machines, displaying whether they are open or closed.
- **Custom Port Checks**: Specify custom ports and IP addresses for targeted network diagnostics.
- **Ping Test**: Test the reachability of remote hosts to quickly assess network connectivity.
- **Interactive UI**: A clean and user-friendly interface built with PyQt5, offering clear results and error notifications.
- **Cross-Platform Executables**: The application is packaged as executables for Windows, macOS, and Linux using GitHub Actions for CI/CD and PyInstaller.

## Installation

### Prerequisites
- Python 3.x
- PyQt5
- psutil

### Clone the Repository
```bash
git clone https://github.com/yourusername/port-checker.git
cd port-checker

Usage
Check Local Ports: Click on 'Check Local Machine Ports' to verify the status of predefined TCP and UDP ports on your local machine.
Check Remote Ports: Enter a remote IP address and click 'Check Remote Machine Ports' to check the status of ports on a remote machine.
Ping Test: Enter an IP address and click 'Check Ping' to verify the reachability of the target machine.
Custom Port Check: Enter a specific port and IP address (optional for remote checks) to check the status of that port.
CI/CD with GitHub Actions
This project uses GitHub Actions for Continuous Integration and Continuous Deployment. Executables are automatically built for Windows, macOS, and Linux using PyInstaller.

GitHub Actions Workflow
The workflow is triggered on push or pull requests to the main branch. It includes the following steps:

Checkout Code: Clones the repository.
Set Up Python: Sets up the required Python environment.
Install Dependencies: Installs Python dependencies.
Build Executable: Uses PyInstaller to create executables for each OS.
Upload Artifacts: The built executables are uploaded as artifacts for easy download.
Tools and Technologies
Python: Core programming language.
PyQt5: For building the graphical user interface.
socket: Used for network communications.
psutil: For accessing system and network information.
GitHub Actions: For CI/CD pipelines.
PyInstaller: For packaging the application into standalone executables.

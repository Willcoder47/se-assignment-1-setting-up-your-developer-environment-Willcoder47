# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

5. Install Package Managers:
   If applicable, install package managers like pip (Python).

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 

## My Developer Environment Setup

A. Windows 10 Installation:

1. Preparation
Check System Requirements

Processor: 1 gigahertz (GHz) or faster processor or SoC
RAM: 1 GB for 32-bit or 2 GB for 64-bit
Hard disk space: 16 GB for 32-bit OS or 20 GB for 64-bit OS
Graphics card: DirectX 9 or later with WDDM 1.0 driver
Display: 800x600

Backup Your Data

Use external storage or cloud services to backup important files.
Consider using tools like Windows Backup and Restore or third-party software.
Product Key

Ensure you have a valid Windows 10 product key for activation.
2. Downloading Windows 10
Access the Windows 10 Download Page

Visit the official Microsoft Windows 10 Download Page.
Download the Media Creation Tool

Click on “Download tool now”.
Save the Media Creation Tool executable to your computer.
Run the Media Creation Tool

Locate the downloaded file and run it.
Accept the license terms.
Create Installation Media

Select “Create installation media (USB flash drive, DVD, or ISO file) for another PC”.
Choose the language, edition, and architecture (64-bit or 32-bit).
Select Media Type

Choose USB flash drive or ISO file (for DVD).
For USB: Insert a USB flash drive with at least 8 GB of space and select it.
For ISO: Save the ISO file to your computer and later burn it to a DVD.
3. Installing Windows 10
Boot from Installation Media

Insert the USB flash drive or DVD into the computer.
Restart the computer.
Press the key to enter BIOS/UEFI (usually F2, F12, Delete, or Esc).
Change the boot order to boot from the USB or DVD first.
Save changes and exit BIOS/UEFI.
Start Installation Process

Windows 10 setup will start.
Select your language, time, and keyboard preferences.
Click “Next” and then “Install Now”.
Enter Product Key

Enter your Windows 10 product key when prompted.
Click “Next”.
Accept License Terms

Read and accept the license terms.
Click “Next”.
Choose Installation Type

Select “Custom: Install Windows only (advanced)” for a fresh installation.
Partition the Hard Drive

Select the partition where you want to install Windows 10.
Format the partition if needed.
Click “Next”.
Install Windows 10

Windows will start copying files and installing features and updates.
The computer will restart several times during the process.
4. Post-Installation
Set Up Windows 10

Choose your region and keyboard layout.
Connect to a network.
Set up your account (Microsoft account or local account).
Customize your privacy settings.
Install Updates

Open Settings > Update & Security > Windows Update.
Check for updates and install any available updates.
Install Drivers

Go to the manufacturer’s website to download and install the latest drivers for your hardware components.
Reinstall Applications

Reinstall any applications you were using before the installation.
Restore your backed-up files to the new installation.
5. Activation
Activate Windows 10
Open Settings > Update & Security > Activation.
Enter your product key if you haven’t already.
Activate Windows 10.
6. Security and Final Checks
Install Antivirus Software

Install your preferred antivirus software.
Update virus definitions and run a full system scan.
Configure System Settings

Adjust system settings to your preference.
Customize the Start menu, taskbar, and other settings.
Final Backup

Create a system image or restore point for future use.
Regularly back up your important data.

B. Step-by-Step Outline to Download and Install Visual Studio Code (VS Code)
Navigate to the VS Code Website:

Go to the official Visual Studio Code website: https://code.visualstudio.com/.
Download VS Code Installer:

Click on the "Download for [Your Operating System]" button (e.g., Windows, macOS, Linux).
Run the Installer:

Once the installer file is downloaded, locate it in your downloads folder or browser downloads.
Double-click the installer file to start the installation process.
Begin Installation:

Follow the prompts in the installation wizard.
Typically, you will be asked to confirm installation permissions (on Windows, macOS, or Linux).
Select Installation Options:

Choose the installation location if prompted (or accept the default location).
On some systems, you might have options to add VS Code to the PATH variable for easier command-line access.
Complete the Installation:

Wait for the installer to complete the installation process.
This may involve extracting files and configuring settings.
Launch VS Code:

Once installed, you can usually launch VS Code from your desktop or from the Start menu (Windows) or Applications folder (macOS).
Initial Setup:

On first launch, VS Code may ask you to install recommended extensions or configure settings.
Customize these options based on your preferences.
Update VS Code (Optional):

Periodically check for updates by going to Help -> Check for Updates within VS Code.
Follow the prompts to update to the latest version if available.
Start Using VS Code:

Once installed and set up, you can start using VS Code for coding, debugging, and other development tasks.

C. Step-by-Step Outline: Downloading and Installing Git for Windows
Navigate to Git for Windows Official Website

Go to the Git for Windows website.
Download Git Installer

Click on the download link prominently displayed on the homepage.
Choose Git Distribution

You may have options such as 32-bit or 64-bit versions. Select according to your system requirements.
Run the Git Installer

Once the download completes, locate the downloaded installer file (typically Git-X.X.X.X-architecture.exe).
Start Installation

Double-click the installer file to begin the installation process.
Configure Installation Settings

Follow the installation wizard steps:
Choose the installation location (default is recommended).
Select components to install (default options are usually sufficient for most users).
Choose the default editor used by Git (e.g., Vim, Nano, Notepad++, etc.).
Adjust other settings as desired.
Adjust PATH Environment

Select the option "Use Git from the Windows Command Prompt" to add Git to your PATH environment. This option allows you to use Git from the command line and other applications seamlessly.
Choose HTTPS Transport Backend

Select the default option for HTTPS transport backend (typically OpenSSL).
Configure Line Ending Conversions

Choose how Git should handle line endings in text files (Checkout Windows-style, commit Unix-style line endings is generally recommended for Windows).
Complete Installation

Click "Install" to begin the installation process.
Wait for the installation to complete. This may take a few minutes.
Finish Installation

Once installation finishes, click "Finish" to exit the setup wizard.

Ci. Steps to Create a GitHub Account
Navigate to GitHub Website

Open a web browser and go to github.com.
Sign Up

Click on the "Sign up" button located on the GitHub homepage.
Enter Your Information

Fill out the sign-up form:
Username: Choose a unique username.
Email Address: Provide a valid email address.
Password: Create a strong password.
Complete CAPTCHA

Complete any CAPTCHA challenge if prompted to verify you're not a robot.
Choose Plan

Select a plan based on your needs:
Free Plan: Suitable for individual developers and small projects.
Pro Plan: Offers advanced features for professional developers and teams.
Verify Your Email Address

GitHub will send a verification email to the address you provided. Click the verification link in the email to activate your account.
Set Up Your Profile

Once logged in, you can customize your profile:
Add a profile picture.
Provide a brief bio.
Optionally, link to your personal website or social media accounts.
Explore GitHub

Familiarize yourself with GitHub's interface and features:
Explore repositories.
Join communities and discussions.
Follow developers and projects of interest.
Configure Account Settings

Go to your account settings to customize preferences, such as notification settings, security options, and privacy settings.
Start Using GitHub

Create your first repository to store your projects.
Learn to use Git commands or GitHub Desktop for version control.
Collaborate with others by inviting collaborators to your repositories.

D. Step-by-Step Outline: Downloading and Installing Python on Windows
Preparation:
Check System Requirements:
Ensure your system meets the minimum requirements for the Python version you intend to install.
Downloading Python:
Navigate to the Python Website:

Go to the official Python website at python.org.
Choose the Python Version:

Select the version of Python you want to download (e.g., Python 3.9.7).
Download the Installer:

Click on the download link for the Windows installer (.exe file).
Installing Python:
Run the Installer:

Locate the downloaded .exe file and double-click to run it.
Configure Installation Options:

Select "Install Now" to use the default settings, or choose "Customize installation" to modify the installation location or components.
Wait for Installation:

Wait for the installer to extract and install Python on your system. This may take a few moments.
Post-Installation Setup:
Add Python to PATH:

If prompted during installation or if not added automatically, select the option to "Add Python to PATH". This step is crucial for using Python from the command line.
Verify Installation:

Open a command prompt (cmd) and type python --version or python3 --version (depending on your installation) to verify that Python has been installed correctly. You should see the version number printed.

E. Outline: Installing pip for Python on Windows
Check Python Installation

Verify if Python is already installed on your system and note down the version.
Download Python Installer (if needed)

If Python isn't installed, download the latest Python installer from the official Python website.
Choose the appropriate version (typically Python 3.x) for your system (32-bit or 64-bit).
Run Python Installer

Execute the downloaded installer (e.g., python-3.x.x.exe).
Ensure to check the option "Add Python to PATH" during the installation process.
Click "Install Now" and wait for Python to be installed.
Verify Python Installation

Open Command Prompt (cmd) and type python --version.
Ensure that the correct Python version is displayed to confirm a successful installation.
Upgrade pip (if needed)

It's recommended to upgrade pip to the latest version. Run:
css
Copy code
python -m pip install --upgrade pip
Install pip (if not installed with Python)

If pip is not installed by default with Python, download the get-pip.py script.
Save the script to a directory on your computer.
Install pip Using get-pip.py

Open Command Prompt and navigate to the directory where get-pip.py is located.
Run the following command:
arduino
Copy code
python get-pip.py
Verify pip Installation

To verify pip installation, type pip --version in Command Prompt.
Confirm that pip's version is displayed without errors.

F. Step-by-Step Outline to Download and Install MySQL Database
Download MySQL Installer:

Navigate to the official MySQL website.
Download the MySQL Installer appropriate for your operating system (Windows, macOS, Linux).
Run MySQL Installer:

Locate the downloaded installer file and run it.
If prompted by security settings, allow the installer to run.
Choose Setup Type:

Select the setup type. Common options include:
Developer Default: Installs MySQL Server and other development tools.
Server Only: Installs only the MySQL Server.
Custom: Allows you to select specific components to install.
Check System Requirements:

Ensure your system meets the minimum requirements for MySQL installation.
Adjust installation options based on system capabilities if needed.
Installation Process:

Follow the installer prompts to proceed with the installation.
Accept the license agreement if prompted.
Configure MySQL Server:

During installation, you may be prompted to configure MySQL Server.
Set the root password for MySQL Server. Choose a strong password and remember it.
Choose MySQL Products to Install:

Select additional MySQL products or features to install if required (e.g., MySQL Workbench, connectors).
Complete Installation:

Allow the installer to complete the installation process.
Verify that all selected components were installed successfully.
Start MySQL Server:

After installation, start MySQL Server using the appropriate method for your operating system:
On Windows, use Windows Services or MySQL Notifier.
On macOS or Linux, use terminal commands to start MySQL Server (sudo systemctl start mysql or sudo service mysql start).
Verify Installation:

Open MySQL Command Line Client or MySQL Workbench.
Connect to the MySQL Server using the root username and password you set during installation.
Verify connectivity and basic operations (e.g., creating a database, executing queries).

G. Exploring Extentions

1. Accessing Extensions
Open VS Code: Launch Visual Studio Code (VS Code).
2. Navigating to Extensions Marketplace
Extensions View: Click on the Extensions view icon on the Activity Bar (or press Ctrl+Shift+X).
Search Bar: Use the search bar at the top to find extensions.
3. Finding Relevant Extensions
Categories: Browse or search within categories like "Popular", "Recommended", or specific categories (e.g., "Linters", "Themes").
Search Queries: Use specific keywords (e.g., "Python", "Git", "React") to find extensions tailored to your needs.
4. Installing Extensions
Installation: Click on the extension you want to install, then click "Install".
Confirmation: Wait for the installation to complete. VS Code may prompt you to reload to enable the extension.

#Deliverables:
- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
- A reflection on the challenges faced during setup and strategies employed to overcome them.

#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:**
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.

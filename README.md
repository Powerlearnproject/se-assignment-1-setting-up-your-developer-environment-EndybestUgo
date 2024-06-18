[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15293907&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

ANSWER: Step 1: Select Your Operating System (OS)
Choose an operating system that best suits your preferences and project requirements. In this case, you are choosing Windows 11.

Step 2: Download Windows 11 ISO
Visit the Microsoft Software Download Page:
Go to the Windows 11 Download Page.

Download the Windows 11 ISO:

Scroll down to the "Download Windows 11 Disk Image (ISO)" section.
Select "Windows 11" from the drop-down menu.
Click "Download."
Choose your preferred language and confirm.
Click the "64-bit Download" button to start downloading the ISO file.
Step 3: Prepare a Bootable CD
Burn the Windows 11 ISO to a CD:
Insert a blank DVD into your CD/DVD writer.
Use a DVD burning software like Windows Disc Image Burner (built-in in Windows) or third-party software like ImgBurn.
Open the software and select the downloaded Windows 11 ISO file.
Choose the CD/DVD drive and start the burning process.
Step 4: Install Windows 11
Insert the Bootable CD:

Insert the bootable Windows 11 CD into the CD/DVD drive of the computer where you want to install Windows 11.
Restart Your Computer:

Restart the computer and enter the BIOS/UEFI settings (usually by pressing a key like F2, F12, Delete, or Esc during startup).
Set the CD/DVD drive as the first boot device.
Boot from the CD:

Save the BIOS/UEFI settings and restart the computer.
The computer should now boot from the Windows 11 CD.
Begin Windows 11 Installation:

Follow the on-screen instructions to start the Windows 11 installation process.
Select your language, time, and keyboard preferences, then click "Next."
Click "Install Now."
Enter the Product Key:

Enter your Windows 11 product key when prompted, or choose "I don't have a product key" to enter it later.
Accept License Terms:

Read and accept the Microsoft Software License Terms, then click "Next."
Choose Installation Type:

Select "Custom: Install Windows only (advanced)" to perform a clean installation.
Select the Drive:

Choose the drive/partition where you want to install Windows 11. Format the drive if necessary.
Click "Next" to start the installation.
Complete the Installation:

The installation process will copy files, install features, and configure settings. Your computer will restart several times.
Follow the on-screen prompts to personalize your settings and complete the setup.
Step 5: Finalize Setup
Set Up Your Account:

Create a user account and set up a password.
Customize your privacy settings.
Install Updates:

Once the installation is complete, connect to the internet and install any available Windows updates to ensure your system is up to date.
By following these steps, you can download, create a bootable CD, and install Windows 11 on your computer.
 
2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
   
   STEPS INVOLVE IN INSTALLING:
   Step 1: Download Visual Studio Code
Visit the Official VS Code Download Page:

Go to the Visual Studio Code Download Page.
Select Your Operating System:

Choose the version of Visual Studio Code that corresponds to your operating system (Windows).
Download the Installer:

Click the appropriate download button to start downloading the VS Code installer for your OS.
Step 2: Install Visual Studio Code on Your System
For Windows:
Run the Installer:

Locate the downloaded VS Code installer (VSCodeSetup-x.y.z.exe) in your Downloads folder and double-click to run it.
Accept the License Agreement:

Read and accept the license agreement, then click "Next."
Select the Destination Location:

Choose the destination folder where you want to install VS Code, then click "Next."
Select Additional Tasks:

Check the additional tasks you want the installer to perform, such as creating a desktop icon, adding to PATH, and associating with file types. Click "Next."
Install VS Code:

Click "Install" to begin the installation process.
Launch VS Code:

Once the installation is complete, check the option to launch Visual Studio Code, then click "Finish."
   
4. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com
   STEPS INVOLVE IN INSTALLING AND CONFIGURING
   Step 1: Install Git and Configure It ON MY Local Machine
Download Git:

Visit the official Git website.
Click on the "Download for Windows" button to download the Git installer.
Run the Git Installer:

Locate the downloaded Git installer (Git-x.y.z-x64.exe or similar) in your Downloads folder and double-click to run it.
Follow the installation steps, selecting the desired options. The default options are usually fine. Key points include:
Choosing the default editor used by Git (typically Vim or Nano, but you can select another editor like Visual Studio Code if preferred).
Adjusting your PATH environment (use "Git from the command line and also from 3rd-party software" for broader compatibility).
Configuring the line ending conversions (select "Checkout Windows-style, commit Unix-style line endings").
Configure Git:

Open Git Bash (a command-line interface for Git) by searching for "Git Bash" in the Start menu.
Set your user name and email address. These details will be associated with your commits.
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"

Step 2: Create a GitHub Account for Hosting Your Repositories
Sign Up for GitHub:
Visit GitHub and click on the "Sign up" button in the top-right corner.
Follow the instructions to create a new account. You'll need to provide a username, email address, and password.
Step 3: Initialize a Git Repository for Your Project and Make Your First Commit
Create a New Project Folder:

Open File Explorer and navigate to the location where you want to create your project folder.
Right-click in the directory and select "New > Folder."
Name the folder (e.g., my-project).
Open Git Bash in Your Project Folder:

Right-click the project folder you created (my-project) and select "Git Bash Here." This opens Git Bash in your project directory.
Initialize a Git Repository:

Initialize a new Git repository in your project folder by running the following command in Git Bash: git init
Create a New File:

Create a new file in your project directory. For example, create a README.md file:
echo "# My Project" > README.md
Stage the File:

Add the file to the staging area: git add README.md
Make Your First Commit:

Commit the file to the repository
git commit -m "Initial commit"
Step 4: Push Your Repository to GitHub
Create a New Repository on GitHub:

Log in to your GitHub account and click on the "+" icon in the top-right corner, then select "New repository."
Provide a name for your repository and optionally add a description.
Choose between public and private visibility.
Click "Create repository."
Add the GitHub Repository as a Remote:

Copy the URL of the new repository from GitHub.
In Git Bash, add the GitHub repository as a remote to your local Git repository
Push Your Local Repository to GitHub:

git push -u origin master
For following these steps, I successfully install and configure Git on my Windows machine, create a GitHub account, initialize a Git repository for your project, make your first commit, and push your repository to GitHub.

6. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

Step-by-Step Guide to Install Python
Download Python Installer:

Visit the official Python website to download the Python installer.
Select the Python Version:

Choose the version of Python that suits your project requirements. Typically, it's recommended to download the latest stable version unless you have specific compatibility requirements with older versions.
Run the Python Installer:

Once the installer is downloaded, locate the downloaded file (e.g., python-3.9.exe for Windows).
Double-click the installer to start the installation process.
Customize Installation (Optional):

During the installation process, i was presented with options to customize the installation. Here are some common options:
Add Python to PATH: Select this option to allow Python to be accessible from the command line (recommended).
Install launcher for all users: Install the Python launcher (py) which helps manage multiple Python versions installed on your system.
Add Python to environment variables: Ensures Python is recognized globally by your system.
Complete the Installation:

Follow the prompts in the installer to complete the installation process. The installer will install Python and necessary dependencies.
Verify Python Installation:

Open a command prompt (for Windows, press Win + R, type cmd, and press Enter).
Type the following command to check the installed Python version
python3 --version or python --version

7. Install Package Managers:
   If applicable, install package managers like pip (Python).
   STEPS TO INSTALL PIP
   Steps to Install pip
Check if pip is Already Installed:

Open a command prompt or terminal.

Type the following command: pip --version
Then type 
pip install upgrade pip

9. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html
   Steps to Download and Install MySQL Server on Windows
Download MySQL Installer

Visit the MySQL Community Downloads page.

Scroll down to find the MySQL Community Server section.

Click on "Download" for the MySQL Installer suitable for your Windows version (usually mysql-installer-community-<version>.exe).

You may need to create or log in to a MySQL account to proceed with the download.

Run the MySQL Installer

Once the installer is downloaded, locate the mysql-installer-community-<version>.exe file and double-click it to start the installation process.

If prompted by User Account Control (UAC), click "Yes" to allow the installer to make changes to your device.

Choose Setup Type

When the MySQL Installer launches, it will prompt you to choose an installation type. Select "Developer Default" for a typical installation suitable for development purposes. You can also choose "Custom" to customize the installation further.
Select Products to Install

In the Product Selection window, ensure that "MySQL Server" is selected. You can also choose additional MySQL products or tools based on your requirements.
Installation Configuration

Click "Next" to proceed to the Installation Configuration step.

Review the configuration options. Typically, the defaults are suitable for most users. Ensure that "MySQL Server" is configured to run as a Windows Service and set to start automatically.

Configure MySQL Server

Set a root password for MySQL. This is important for securing your MySQL installation.

Optionally, configure advanced settings such as port number, server data directory, and authentication method.

Start Installation

Click "Execute" to start the installation process. The installer will download and install MySQL Server and any selected components.
Complete the Installation

Once the installation completes successfully, click "Next."

Optionally, register for MySQL updates using your MySQL account.

Click "Finish" to exit the installer.

Verify MySQL Installation

Open a command prompt or PowerShell.

Type the following command to verify the MySQL server version: mysql --version.


11. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

12. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

13. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 

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

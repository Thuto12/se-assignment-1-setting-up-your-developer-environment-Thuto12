[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15288393&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11
   
Download Microsoft Office installer from the official website.
Open the downloaded file and run the installer.
Sign in with your Microsoft account.
Follow on-screen instructions to complete the installation.
Launch Office applications from the Start menu or desktop.

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
Download Visual Studio Installer

Visit the Visual Studio website.
Click on the "Download" button for the version you want (e.g., Community, Professional, Enterprise).
Save the installer file to your computer.
Run the Installer

Open the downloaded installer file (e.g., vs_installer.exe).
Allow the installer to make changes to your device if prompted by User Account Control.
The Visual Studio Installer will launch.
Select Workloads

In the Visual Studio Installer, you'll see a list of workloads (e.g., ASP.NET and web development, Desktop development with C++, etc.).
Check the boxes next to the workloads you need for your projects.
Optionally, click on "Individual components" to select specific tools and libraries.
Install Visual Studio

Click the "Install" button after selecting your desired workloads and components.
The installer will download and install the required files. This process may take some time depending on the components selected and your internet speed.
Once installation is complete, click the "Launch" button to start Visual Studio.
Initial Configuration

On first launch, sign in with your Microsoft account if prompted.
Choose your development settings (e.g., General, Python, Web, etc.) to customize your IDE layout and keybindings.
Select a color theme (e.g., Blue, Dark, Light) for your development environment.
Visual Studio will open with your chosen settings. You can start creating or opening projects.
Optional: Install Extensions

Go to "Extensions" in the menu bar and click on "Manage Extensions".
Browse the marketplace for extensions that enhance your development experience (e.g., ReSharper, Python tools, etc.).
Download and install the extensions you need.
Restart Visual Studio to activate the new extensions.
Configure Source Control

If you use Git, open "Team Explorer" from the "View" menu.
Click on "Connect" to manage your repositories.
Clone a repository, create a new one, or connect to an existing local repository.
Configure global Git settings like username and email under "Settings".
Set Up Debugging and Build Configurations

Open a project or create a new one.
Configure build settings via the "Build" menu.
Set breakpoints and configure debugging options via the "Debug" menu.
Test your configurations by running and debugging your project.

3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

   Download and Install Git

Windows: Visit Git for Windows, download the installer, and run it.
Verify Installation
Open a terminal (Command Prompt or Git Bash on Windows).
Run the command git --version to check if Git is installed correctly.
Configure User Information
Set your username and email address, which will be used for your commits.
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
Set Up Default Text Editor
Configure your preferred text editor for Git (replace code with your editor of choice, e.g., nano, vim, notepad, etc.).
git config --global core.editor "code --wait"
Create a test repository and make your first commit to ensure everything is set up correctly.
mkdir my-test-repo
cd my-test-repo
git init
echo "# My Test Repo" > README.md
git add README.md
git commit -m "Initial commit"

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.
  Install Python
Windows
Download Python Installer

Visit the official Python downloads page.
Download the latest Python installer (e.g., python-3.12.exe).
Run the Installer

Open the downloaded installer file.
Important: Check the box "Add Python to PATH" before clicking "Install Now".
Follow the prompts to complete the installation.
Verify Installation

Open Command Prompt.
Run the command:
python --version
You should see the Python version you installed.


5. Install Package Managers:
   If applicable, install package managers like pip (Python).
   Installing pip
pip usually comes pre-installed with Python, but if it's not available or you need to upgrade it, follow these steps:

Check if pip is already installed:
vt running this command
pip --version

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html
   To install and configure MySQL on a Windows operating system, follow these steps:

Step 1: Download MySQL Installer
Visit the MySQL website:
Go to the MySQL download page.

Download the MySQL Installer:
Choose the MySQL Installer for Windows (either web or offline installer). The web installer is smaller and downloads only the required components, while the offline installer includes all components.

Step 2: Run the MySQL Installer
Launch the Installer:
Double-click the downloaded installer file to launch the MySQL Installer.

Choose Setup Type:
Select the setup type. For most users, "Developer Default" is sufficient, but you can choose "Server only" if you only need the MySQL server.

Check for Requirements:
The installer will check for and install any required software (e.g., Visual Studio Redistributable).

Installation:
Click "Execute" to download and install the selected components.

Step 3: Configure MySQL Server
Configure MySQL Server:
After installation, the MySQL Installer will launch the configuration wizard. Click "Next" to begin configuration.

High Availability:
Choose "Standalone MySQL Server" and click "Next".

Type and Networking:

Choose "Development Machine" if this is for development, "Server Machine" for server use.
Leave TCP/IP enabled and set the port to the default (3306). Ensure "Open Windows Firewall port for network access" is checked.
Click "Next".
Authentication Method:

Choose the authentication method. The default (Use Strong Password Encryption) is recommended.
Click "Next".
Accounts and Roles:

Set the root password and add any additional user accounts you need.
Click "Next".
Windows Service:

Ensure "Configure MySQL Server as a Windows Service" is checked.
You can change the service name if needed.
Choose "Standard System Account" to run the service.
Click "Next".
Apply Configuration:

Review the configuration settings and click "Execute" to apply them.
Once done, click "Finish".

Step 4: Verify MySQL Installation
Open Command Prompt:
Open a Command Prompt window (search for "cmd" in the Start menu).

Connect to MySQL Server:
Run the following command to connect to the MySQL server using the root account:

mysql -u root -p
Enter Password:
Enter the root password you set during configuration.

Check MySQL Version:
Once logged in, you can check the MySQL version with:

SELECT VERSION();

Step 5: Basic Configuration and Database Setup
Create a Database:

CREATE DATABASE mydatabase;
Create a User:

CREATE USER 'myuser'@'localhost' IDENTIFIED BY 'mypassword';
Grant Privileges to the User:

GRANT ALL PRIVILEGES ON mydatabase.* TO 'myuser'@'localhost';
FLUSH PRIVILEGES;

Exit MySQL:
EXIT;

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

   Enhancing the functionality of your text editor or Integrated Development Environment (IDE) can significantly improve your productivity and coding experience.These enhancements can provide features such as syntax highlighting, linting, code formatting, and version control integration, making development faster, easier, and more efficient.

Exploring Available Extensions
Visual Studio Code (VSCode)
Marketplace: Visit the Visual Studio Code Marketplace to explore available extensions.
In-Editor Search: Open VSCode, press Ctrl+Shift+X to open the Extensions view, and use the search bar to find extensions.
Popular Categories:
Syntax Highlighting: Look for language-specific extensions.
Linting: Search for linters like ESLint for JavaScript, Pylint for Python.
Code Formatting: Extensions like Prettier.
Version Control: GitLens for Git integration.

Sublime Text
Package Control: Install Package Control, the package manager for Sublime Text.
Browse Packages: Use the Command Palette (Ctrl+Shift+P), type Install Package, and browse available packages.

Installing and Configuring Extensions
Visual Studio Code (VSCode)
Installation:
Open the Extensions view (Ctrl+Shift+X).
Search for the desired extension.
Click Install.
Configuration:
Go to File > Preferences > Settings.
Search for the extension name and adjust settings as needed.

Sublime Text
Installation:
Open the Command Palette (Ctrl+Shift+P).
Type Install Package.
Search for the desired package and press Enter to install.
Configuration:
Go to Preferences > Package Settings.
Find the package and adjust settings.


9. Document Your Setup:
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

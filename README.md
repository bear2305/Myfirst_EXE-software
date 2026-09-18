# Myfirst_EXE-software
A simple login applicatation for Windows created with C++




C++ Windows Login Application (GROUP 11 APP)

A native C++ Windows desktop application featuring temporary session-based user authentication, dynamic profile management, and an admin override system. Originally developed as an academic group assignment, this project was completely rewritten from the ground up to refine the application logic and package it as a deployable Windows desktop app.
🌟 Key Features

    In-Memory User Management: Dynamic user registration system stored using associative containers (std::map / key-value structures) for runtime account lookup without requiring an external database.

    Persistent Admin Account: Hardcoded master administrator account (username: admin / password: admin) that grants immediate system access and developer profile views.

    Session Lifecycle Control: Supports full login, log out, and new user sign-up workflows within a active application session. Account state resets safely upon closing the app.

    Developer Info Panel: Dedicated dashboard showcasing user metadata, student index credentials, and application information.

    Installer-Ready: Packaged with a standalone Windows installer setup to allow seamless installation and registration in the Windows Control Panel / Installed Apps list.

🛠️ Built With

    Language: C++

    GUI Framework: C++/CLI / Windows Forms (WinForms) / Win32 API

    IDE: Visual Studio

🚀 Getting Started
Installation via Windows Setup

    Download the Setup.exe or Installer.msi file from the Releases section.

    Run the installer and follow the standard Windows setup wizard.

    Once installed, launch GROUP 11 APP directly from your Desktop or Start Menu.

    (Optional) Manage or uninstall the app anytime via Settings > Apps > Installed apps or Control Panel.

Building from Source

    Clone the repository:
    Bash

    git clone https://github.com/your-username/cpp-login-app.git
    cd cpp-login-app

    Open LoginApp.sln in Visual Studio.

    Ensure the .NET desktop development or Desktop development with C++ workload is installed.

    Build in Release | x86 or Release | x64 configuration.

    Press Ctrl + F5 to build and launch.

🔑 Demo Credentials
Role	Username	Password	Notes
Admin	admin	admin	Default built-in profile
Temporary User	User-defined	User-defined	Active during current session only

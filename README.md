# SteamAutoDropper
SteamAutoDropper is a script-based tool designed to automate the process of launching Steam games for the purpose of obtaining free in-game drops. This tool is ideal for users who want to efficiently run multiple games simultaneously for a short period to receive rewards without manual intervention.
# Features
Automated Game Launching: Launches up to four Steam games simultaneously for a predefined duration.
Headless Operation: Runs games in the background without the need for a graphical user interface.
Scheduled Execution: Utilizes system schedulers (Task Scheduler on Windows or cron on Linux) to run the games at regular intervals.
Easy Configuration: Simple setup and configuration for different game IDs and scheduling preferences.
# Requirements
SteamCMD: Steam Console Client for executing Steam commands.
Windows or Linux: Compatible with both operating systems with appropriate scripts.
Valid Steam Account: A Steam account with login credentials.
Setup Instructions
Install SteamCMD:

Download SteamCMD and follow the installation instructions for your operating system.
Configure the Script:

Modify the script (run_games.bat for Windows or run_games.sh for Linux) with your Steam login credentials and the game IDs you want to automate.
Schedule the Script:

Windows: Use Task Scheduler to run the run_games.bat script every three hours.
Linux: Use cron to schedule the run_games.sh script to run every three hours.
Usage
Clone the repository:

sh
Copy code
git clone https://github.com/QRage/SteamAutoDropper.git
cd SteamDropAutoRunner
Edit the script with your Steam credentials and game IDs.

Set up the task scheduler or cron job to automate the script execution.

# Contributing
Contributions are welcome! If you have any improvements, bug fixes, or new features, please feel free to submit a pull request.

# License
This project is licensed under the MIT License. See the LICENSE file for details.

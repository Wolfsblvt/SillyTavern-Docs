---
order: 10
label: Windows
---
# Windows Installation

!!!warning
DO NOT INSTALL INTO ANY WINDOWS CONTROLLED FOLDER (Program Files, System32, etc).

DO NOT RUN START.BAT WITH ADMIN PERMISSIONS

INSTALLATION ON WINDOWS 7 IS IMPOSSIBLE AS IT CAN NOT RUN NODEJS 18.16
!!!

## Installing via Git
  1. Install [NodeJS](https://nodejs.org/en) (latest LTS version is recommended)
  2. Install [Git for Windows](https://gitforwindows.org/)
  3. Open Windows Explorer (`Win+E`)
  4. Browse to or Create a folder that is not controlled or monitored by Windows. (ex: C:\MySpecialFolder\)
  5. Open a Command Prompt inside that folder by clicking in the 'Address Bar' at the top, typing `cmd`, and pressing Enter.
  6. Once the black box (Command Prompt) pops up, type ONE of the following into it and press Enter:

- for Release Branch: `git clone https://github.com/SillyTavern/SillyTavern -b release`
- for Staging Branch: `git clone https://github.com/SillyTavern/SillyTavern -b staging`

  7. Once everything is cloned, double-click `Start.bat` to make NodeJS install its requirements.
  8. The server will then start, and SillyTavern will pop up in your browser.

## Installing via SillyTavern Launcher
 1. Install [Git for Windows](https://gitforwindows.org/)
 2. Open Windows Explorer (`Win+E`) and make or choose a folder where you wanna install the launcher to
 3. Open a Command Prompt inside that folder by clicking in the 'Address Bar' at the top, typing `cmd`, and pressing Enter.
 4. When you see a black box, insert the following command: `git clone https://github.com/SillyTavern/SillyTavern-Launcher.git`
 5. Double-click on `installer.bat` and choose what you wanna install
 6. After installation double-click on `launcher.bat`

## Installing via GitHub Desktop
(This allows git usage **only** in GitHub Desktop, if you want to use `git` on the command line too, you also need to install [Git for Windows](https://gitforwindows.org/))
  1. Install [NodeJS](https://nodejs.org/en) (latest LTS version is recommended)
  2. Install [GitHub Desktop](https://central.github.com/deployments/desktop/desktop/latest/win32)
  3. After installing GitHub Desktop, click on `Clone a repository from the internet....` (Note: You **do NOT need** to create a GitHub account for this step)

  ![image](/static/windows-1.png)

  4. On the menu, click the URL tab, enter this URL `https://github.com/SillyTavern/SillyTavern`, and click Clone. You can change the Local path to change where SillyTavern is going to be downloaded.

  ![image](/static/windows-2.png)

  6. To open SillyTavern, use Windows Explorer to browse into the folder where you cloned the repository. By default, the repository will be cloned here: `C:\Users\[Your Windows Username]\Documents\GitHub\SillyTavern`
  
  7. Double-click on the `start.bat` file. (Note: the `.bat` part of the file name might be hidden by your OS, in that case, it will look like a file called "`Start`". This is what you double-click to run SillyTavern)

  ![image](/static/windows-3.png)

  8. After double-clicking, a large black command console window should open and SillyTavern will begin to install what it needs to operate.
  
  9. After the installation process, if everything is working, the command console window should look like this and a SillyTavern tab should be open in your browser:

  ![image](/static/windows-4.png)

  10. Connect to any of the [supported APIs](https://docs.sillytavern.app/usage/api-connections/) and start chatting!

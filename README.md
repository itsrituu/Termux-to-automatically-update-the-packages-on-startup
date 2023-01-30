# Termux-to-automatically-update-the-packages-on-startup
Every time you start Termux, the script will run and update your packages automatically.
To use this script, follow these steps:

Open Termux and type nano update.sh to create a new script file.
Copy and paste the code above into the file.
Save the file by pressing CTRL + X, then Y, and then ENTER.
Make the script executable by typing chmod +x update.sh.
Add the script to the Termux startup by typing termux-wake-lock, followed by nano ~/.bashrc.
Add the line sh ~/update.sh to the bottom of the file.
Save the file and exit by pressing CTRL + X, then Y, and then ENTER.
Now, every time you start Termux, the script will run and update your packages automatically.

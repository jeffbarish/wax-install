Clone wax, wax-config, and wax-install (from the home directory):

    git clone https://github.com/jeffbarish/wax.git
    git clone https://github.com/jeffbarish/wax-config.git
    git clone https://github.com/jeffbarish/wax-install.git

cd into wax-install and run the program "installer.root" as root:

    sudo ./installer.root

Run installer as youself:

    ./installer

installer.root:

- runs apt to install several packages. 

- puts starter scripts for wax and waxconfig in /usr/local/bin.

installer:

- puts the theme in ~/.themes.

- creates a virtual environment in ~/.venv and installs several packages.

- creates wax subdirectories in ~/wax/.config

When the installer finishes, type "wax" to run wax or "waxconfig" to run waxconfig.

I tested the code on Ubuntu 24.04 running on an Intel processor and on Debian GNU/Linux 12 (Raspberry Pi OS) running on Raspberry Pi 4B. Note that you will need GTK and GStreamer on whatever OS you choose.

You can also install wax on Windows 11 using WSL 2. However, there are limitations. It is not possible to access a CD-drive as a device from WSL, so ripping in Wax on WSL is not possible. Instead, rip using Media Player, put the sound files in the transfer folder of Wax, and import them. Media Player does not embed cover art, so you will need to find cover art (at Amazon, for example) and copy-and-paste it into Wax.

Do not run installer over an existing installation.

To create your first recording after installing Wax, insert a CD in your CD drive and go to Edit mode. Select the appropriate genre for your CD using the button in the top left. Click the Create button in the right panel. While the CD is ripping, fill in the boxes on the left panel at least for the primary metadata. Some of the boxes might have been filled in automatically after you initiated the rip using metadata from MusicBrainz. Click the "Save new" button at the bottom when you are ready to save the recording. When the ripping finishes, change the Mode to Select. Your new recording will already be selected. Drag it to the play queue (the right panel). The play button will appear in the top right. Click it to start play. Congratulations. You have just created the first recording in your Wax database.

The [manual](https://wax-manual.readthedocs.io/en/latest/introduction.html) provides *much* more information, but do not feel intimidated. Each section starts with an "Essential reading" section that directs you to a few paragraphs with the salient information.

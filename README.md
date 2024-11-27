Clone wax, wax-config, and wax-install (from the home directory):

    git clone https://github.com/jeffbarish/wax.git
    git clone https://github.com/jeffbarish/wax-config.git
    git clone https://github.com/jeffbarish/wax-install.git

cd into wax-install and run the program "installer" as root:

    sudo ./installer

The installer

- runs apt to install several packages. 

- puts starter scripts for wax and waxconfig in /usr/local/bin.

- puts the theme in ~/.themes.

- creates a virtual environment in ~/.venv and installs several packages.

When the installer finishes, type "wax" to run wax or "waxconfig" to run waxconfig.

I tested the code on Ubuntu 24.04 running on an Intel processor and on Debian GNU/Linux 12 (Raspberry Pi OS) running on Raspberry Pi 4B. Note that you will need GTK and GStreamer on whatever OS you choose.

Do not run installer over an existing installation.

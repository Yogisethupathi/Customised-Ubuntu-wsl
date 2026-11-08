# Customised-Ubuntu-wsl
 Made User friendly Ubuntu coustomised WSL for devops learning !!!
 
![Static Badge](https://img.shields.io/badge/Ubuntu-wsl-orange) 

Requirements❤️

1. Download the wsl from https://ubuntu.com/wsl.
2. Run the wsl.
3. configure your user data

> [!WARNING]
> never forget your password !! 😢

Create your bash config

1. touch ~/.bashrc
2. nano ~/.bahrc

download these and insall in your wsl  𓆝 𓆟 𓆞 ·｡

![Static Badge](https://img.shields.io/badge/starship-silver)
![Static Badge](https://img.shields.io/badge/ble.sh-gold)


> [!NOTE]
> Follow he steps !!

STEP 1: Install Starship
curl -sS https://starship.rs/install.sh | sh

STEP 2: Open Bash configuration
nano ~/.bashrc

STEP 3: Add this line inside .bashrc
eval "$(starship init bash)"

STEP 4: Reload configuration
source ~/.bashrc

STEP 5: Verify installation
starship --version     

STEP 6: Config the file 
nano ~/.config/starship.toml

SETP 7: The config data is in readme file in the project

Untill now 👌

directory  : Displays your current folder
git_branch : Displays the current Git branch
git_status  : Displays Git changes
character    : Customizes the prompt symbol
style Changes : terminal text colours

STEP 8: Clone ble.sh from GitHub
git clone --recursive --depth 1 --shallow-submodules https://github.com/akinomyoga/ble.sh.git

STEP 9: Install ble.sh
make -C ble.sh install PREFIX="$HOME/.local"

STEP  10 : Open Bash configuration
nano ~/.bashrc

STEP 11 : Add this line inside .bashrc
source ~/.local/share/blesh/ble.sh

STEP 12 : Reload Bash
source ~/.bashrc

run this comment to verify built 
ls ~/.local/share/blesh/

COUSTOM SKIN FOR UBUNTU 
1.sudo apt install hyfetch Installs HyFetch.

2.hyfetch Runs HyFetch.

3.hyfetch --version Checks its version

check the file image for the screem model.

> [!IMPORTANT]
> for the awsome look in terminal ....!

1 .mkdir -p ~/.config = Creates the configuration folder if needed.
2. nano ~/.config/fox.txt = Creates and opens the fox text file.
3 .Add ASCII fox Writes your custom artwork.
4 .hyfetch --ascii-file ~/.config/fox.txt = Displays your fox logo.

FOR THE ASCII ARE WORK I SUGGEST CHOOSE A SMALL ONE

> [!TIP]
> USE THIS LINKK FOR COOL ASCII ARTS
https://emojicombos.com/ascii-art 

# Workstation

## Setup
- Update OS
- Enable Flathub "flatpak remote-modify --no-filter --enable flathub"
- Install Ansible
- Create Ansible Vault 
- Run Anisible Playbook
- Swamp FFMPEG "sudo dnf swap ffmpeg-free ffmpeg --allowerasing"

## Final Tasks
- Restore backup
- Setup Firefox
- Setup Thunderbird accounts (d.verbeek@uu.nl / dverbeek84@gmail.com / dannyenmirella@gmail.com / d.verbeek@dotnow.nl)
- Login to GitHub
- Login to Google (dverbeek84@gmail.com / dannyenmirella@gmail.com / d.verbeek@dotnow.nl)
- Login to Spotify

- Configure keepassxc
- Connect Bose headset
- Install oc and openshift-installer
- Login JetBrains ToolBox
- Install Pycharm / Goland
- Enable Flathub

## Change directory chmod if moved from windows
find Backup -type d -exec chmod 755 {} \;
find Backup -type f -exec chmod 644 {} \;

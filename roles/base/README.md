# Base Role
This role provides several defaults which should be useful in any install

## Changes

1. Sets the `pacman` configuration file
1. Sets the hostname
1. Install bash, bash-completion, zsh, zsh-completion
1. Creates user, group and sets password
1. Creates user log directory and sets up logrotate
1. Install sudo, add user to wheel group, and set sudoers file
1. Install base packages
1. Create pacman mirrorlist update hook
1. Create aur directory, install cower, and base aur packages
1. Create and enable pacman cache cleanup service
1. Set systemd journal configuration file

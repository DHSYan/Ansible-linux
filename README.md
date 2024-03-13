# Ansible Linux Dev Playbook
This is a playbook that sets up my Fedora Linux Experiences
This will be Fedora for now, though all my experiences were with Debian Based,
Macs only have Asahi Fedora For now, so I will be setting this for now. 
I think it might be possible to have separate plays that run only 
on spefici systems, and other stuff that is universal like my .dotfiles, zsh
tmux, neovim could still run universally.

# Precondition
1. Install Ansible
2. Have Git (to clone this repo)

# Usage

```
$ ansible-galaxy install -r requirements.yml
$ ansible-playbook main.yml
```

# Dotfiles (Universal)
- Neovim
- zsh
- ssh and ssh keys

# Applications (Non-Universal)
- cmake
- neovim
- Stow
- Wezterm
- ALacritty
- Kitty
- Brave
- Obsidian
- Spotify
- Discord

# Window Manager (Universal?)
- I think Fedora also use x11?

# Terminal Setup (Wezterm, Alacritty, Kitty)
- Oh my zsh
- zsh

# Key Repeat Rate 


# Resources
https://opensource.com/article/18/3/manage-workstation-ansible
https://fedoramagazine.org/using-ansible-setup-workstation/

# Chat GPT
[https://chat.openai.com/share/e7956d20-e60d-4e80-8d65-751cc6beceae]

A large portion of this project was made by Chat GPT. 


# Archetiure Matters

# Latex
```
sudo dnf install 'tex(beamer.cls)' 
sudo dnf install 'tex(hyperref.sty)'
```
- Is how you install indivisual packages
# TODO 

`xrandr --output eDP-1 --brightness .5`
  - this sets the screen brightness to 50%
  - I should use skhd to map this command to some keybind 

fix The Reduncey in the Code

Create a script that fetches .dotfiles, ansible-linux and runs the playbook 
if the Ansible-linux has changes.  This will make sure whatever is on my PC
will be on the other.

Install Fonts

- Weylus
- Lorien (Infinite Canvas Thing)


- TPM

- Install DWM

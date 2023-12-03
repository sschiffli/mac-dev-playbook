## Fix keyboard modifier keys

swap command and control

## Copy Fonts to ~/Library/Fonts

## Setup yabai

Disable SIP https://github.com/koekeishiya/yabai/wiki/Disabling-System-Integrity-Protection
Setup scripting addons https://github.com/koekeishiya/yabai/wiki/Installing-yabai-(latest-release)#configure-scripting-addition
yabai --start-service
skhd --start-service

## Install gcloud cli

https://cloud.google.com/sdk/docs/install

## Import Yubikey GPG keys

https://developer.okta.com/blog/2021/07/07/developers-guide-to-gpg#move-your-gpg-keys-to-a-yubikey
gpg --edit-card
fetch
quit

gpg --list-secret-keys (Copy key id)
gpg --edit-key <key id>
trust
5
q

## FZF extras
To install useful keybindings and fuzzy completion:
  /opt/homebrew/opt/fzf/install


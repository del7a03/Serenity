This is my window manager project called Serenity.

To get started with development, install wsl on your computer. 

Next, download nixos.wsl from [the latest release](https://github.com/nix-community/NixOS-WSL/releases/tag/2511.7.1). 
Or, run this command. sh <(curl -L https://nixos.org/nix/install) --no-daemon
(You will need to make sure virtualization is suppported and enabled on your computer)

Also, make sure you have devenv. Run this command in the nix shell to install it. 
nix-env --install --attr devenv -f https://github.com/NixOS/nixpkgs/tarball/nixpkgs-unstable

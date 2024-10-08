### How to build

```
sh <(curl -L https://nixos.org/nix/install)
git clone https://github.com/nhuphucnguyen/nix.git ~/.config/nix
nix run nix-darwin --extra-experimental-features "nix-command flakes" -- switch --flake ~/.config/nix#darwin
```

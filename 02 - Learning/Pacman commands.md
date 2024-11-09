#linux

sudo **pacman -S** package-name | Installs package "package-name"
sudo **pacman -R** package-name | Removes package "package-name"
sudo **pacman -Q** package-name | Searches for package "package-name"

sudo **pacman -Rns** $(pacman -Qtdq) | Removes all orphan packages
### Pacman commands

Install packages

> `pacman -S <package_name>`

Remove packages

> `pacman -R <package_name>`

System update

> `pacman -Syu`

Removing unwanted pacman packages

> `sudo pacman -R $(pacman -Qtdq)`

Removing unwanted yay packages

> `yay -R $(yay -Qtdq)`

Clearing pacman cache

> `sudo pacman -Scc`

Clearing yay cache

> `yay -Scc`

# Heav-Dotfiles for Hyprland
### Hyprland Dots | HyprDots

![image]()

> [!IMPORTANT]
> Se trata de una primera versiòn de mis archivos de configuraciòn sobre Hyprland.
> Este repositorio se encuentra en desarrollo de nuevas caracteristicas como traducciòn al ingles, nuevas funcionalidades personalizadas en Waybar, desarrollo de script de instalaciòn, menù de personalizaciòn del sistema y agregar a la configuraciòn personalizaciones para code, dolphin y firefox entre otros.
> Cualquier recomendaciòn, sugerencia o comentario serà bien recibido.

> [!CAUTION]
> Este repositorio se encuentra en desarrollo por lo que podrìa contener fallas.
> En caso de encontrar alguna, por favor dar aviso para una rapida correcciòn.

## Instalaciòn mediante Script

> [!CAUTION]
> Actualmente en desarrollo. Disponible en proxima versiòn.

## Instalaciòn Manual

> PLEASE NOTE: Esta guìa da por sentado que està utilizando Arch Linux. Tenga en cuenta que si su distribuciòn es distinta, es probable que tenga que realizar algunos ajustes.

> [!CAUTION]
> Considere que para la configuraciòn manual, serà necesario tener ya instalado ohmyzsh y powerlevel10k.

> Instale las dependencias del repositorio
```shell
sudo pacman -Syu zsh hyprlock hyprpaper kitty nwg-bar waybar wofi pavucontrol lsd bat
```

> Descargue el repositorio de la rama master
```shell
git clone --depth=1 https://github.com/nachoheav/Hyprdots.git
cd Hyprdots
```

> Cree una copia de su configuraciòn actual.
```shell
mkdir ~/.config/Hyprdots-backup
cp -r ~/.config/hypr ~/.config/kitty ~/.config/nwg-bar ~/.config/waybar ~/.config/wofi ~/.p10k.zsh ~/.zshrc ~/.config/Hyprdots-backup/
```

> Cargue la nueva configuraciòn
```shell
cp -r ~/Hyprdots/config/* ~/.config/
cp ~/Hyprdots/p10k.zsh ~/.p10k.zsh
cp ~/Hyprdots/zshrc ~/.zshrc
```

> [!TIP]
> Se recomienda cerrar la sesiòn y volver a abrirla para efectuar todos los cambios.

## Keybindings

> Entre parentesis aplicaciòn predeterminada actual

<div align="center">

| Keys | Action |
| :--- | :--- |
| <kbd>Super</kbd> + <kbd>RETURN</kbd> | Terminal (Kitty) |
| <kbd>Super</kbd> + <kbd>R</kbd> | Menu de aplicaciones (Wofi) |
| <kbd>Super</kbd> + <kbd>F</kbd> | Gestor de archivos (Dolphin) |
| <kbd>Super</kbd> + <kbd>W</kbd> | Navegador (Brave)  |
| <kbd>Super</kbd> + <kbd>C</kbd> | Editor de codigo (VSCode)  |
| <kbd>Super</kbd> + <kbd>Q</kbd> | Cerrar ventana actual |
| <kbd>Super</kbd> + <kbd>L</kbd> | Bloquear el equipo |
| <kbd>Super</kbd> + <kbd>M</kbd> | Cerrar sesiòn actual |
| <kbd>Super</kbd> + <kbd>←</kbd><kbd>→</kbd><kbd>↑</kbd><kbd>↓</kbd> | Mover foco de ventana |
| <kbd>Super</kbd> + <kbd>[0-9]</kbd> | Mover entre workspaces |
| <kbd>Super</kbd> + <kbd>Shift</kbd> + <kbd>[0-9]</kbd> | Mover ventana actual a otro workspace |
| <kbd>Super</kbd> + <kbd>MouseScroll</kbd> | Moverse entre workspaces utilizados |
| <kbd>Super</kbd> + <kbd>LeftClick</kbd> | Mover ventana actual |
| <kbd>Super</kbd> + <kbd>RightClick</kbd> | Redimensionar ventana actual |

</div>
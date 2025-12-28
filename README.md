# 🔧 Mis Dotfiles (Arch Linux + Sway)

Bienvenido a mi repositorio personal de configuraciones (dotfiles). Aquí guardo la configuración de mi entorno de trabajo basado en **Sway (Wayland)** para replicarlo fácilmente en cualquier máquina.

## 💻 Sistema
* **OS:** Lap: Arch Linux / PC: Manjaro
* **WM:** Sway (Wayland)

## 📂 Estructura
Actualmente, este repositorio gestiona:
* **Sway Config:** Atajos de teclado, reglas de ventanas y configuración de hardware.

## 🚀 Instalación y Restauración

Pasos para restaurar/clonar esta configuración:

### 1. Clonar el repo
Descargar configuraciones en la carpeta `~/dotfiles`:

```bash
git clone git@github.com:Oddiseo/odd-dotfiles.git
```

### 2. Crear Enlaces Simbólicos (Symlinks)

Crear carpeta si no existe
`mkdir -p ~/.config/sway`

(Opcional) Respaldo la config original si existe
`mv ~/.config/sway/config ~/.config/sway/config.backup`

Crear el enlace
`ln -s ~/dotfiles/sway_config ~/.config/sway/config`
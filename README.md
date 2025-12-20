# Neovim NvChad Backup

A personal backup of my NvChad Neovim configuration, preserving custom plugins, themes, and settings.

## 📁 Structure

```
.
├── ftplugin/          # Filetype-specific settings
└── lua/
    └── custom/        # Custom NvChad configuration
        ├── chadrc.lua    # Main NvChad config
        ├── plugins.lua   # Plugin definitions
        ├── mappings.lua  # Custom key mappings
        └── configs/      # Plugin configurations
```

## ✨ Features

- Custom plugin configurations
- Personalized key mappings
- Language-specific settings via ftplugin
- Theme customizations

## 🔄 Usage

### Restore Configuration

```bash
# Backup existing config
mv ~/.config/nvim/lua/custom ~/.config/nvim/lua/custom.bak

# Clone this backup
git clone https://github.com/EhsanulHaqueSiam/neovim-nvchad-backup.git
cp -r neovim-nvchad-backup/lua/custom ~/.config/nvim/lua/
cp -r neovim-nvchad-backup/ftplugin ~/.config/nvim/
```

### Create New Backup

```bash
cp -r ~/.config/nvim/lua/custom .
cp -r ~/.config/nvim/ftplugin .
git add . && git commit -m "Update config backup"
git push
```

## 📋 Prerequisites

- [Neovim](https://neovim.io/) (v0.9+)
- [NvChad](https://nvchad.com/) installed

## 📄 License

MIT License

## 👤 Author

**Ehsanul Haque Siam**
- GitHub: [@EhsanulHaqueSiam](https://github.com/EhsanulHaqueSiam)

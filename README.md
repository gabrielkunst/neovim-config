# Installation
## Windows
- Files must go inside C:\Users\user_name\AppData\Local\nvim
- Needs packer installation by using:
  ```shell
  git clone https://github.com/wbthomason/packer.nvim "$env:LOCALAPPDATA\nvim-data\site\pack\packer\start\packer.nvim"
  ```
- After installing, go to packer.lua and exec:
  ```shell
  :so
  ```
  ```shell
  :PackerSync
  ```

## Ubuntu
- Files bust go inside ~/.config/nvim
- Needs packer installation by using:
  ```shell
  git clone --depth 1 https://github.com/wbthomason/packer.nvim\
  ~/.local/share/nvim/site/pack/packer/start/packer.nvim
  ```
- After installing, go to packer.lua and exec:
  ```shell
  :so
  ```
  ```shell
  :PackerSync
  ```

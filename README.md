# My Neovim Configuration
### Step1 :
	cd ~
	sudo apt update
	sudo apt install neovim
-----------------
###  Steps2 : 
### inside `~/.config/nvim`
- install nodejs v18.17 (google it to know how to update it)
- install npm v9.6
- install pip3 v20.0
- install jedi (pip3 install jedi)
- sudo apt install exuberant-cats
----------------
### Step3 :
### inside `~/.config/nvim`
- create a file called **coc-settings.json**:
   - past the content of the **coc-settings.json** of this repo to your local **coc-settings.json**
-----------------------
- create a file called **init.vim**:
    - Past the content of the **init.vim** of this repo to your local **init.vom**
    - Press **ESC**
    - Enter  **:PlugInstall** then press enter
    - Enter  **:CocInstall coc-python** then press enter
-------
- inside `~/.vim/plugged/coc.nvim` do this:
	- Install yarn 1.2 **(sudo npm install -g yarn)**
	- Write this command: **yarn install**

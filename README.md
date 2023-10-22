# decomp-pokeemerald
Custom pokemon emerald romhack. Decompilation .gba in C/asm.
#pokeemerald dependencies:

###requires WSL/Ubuntu, VSCODE extension below
 ms-vscode-remote.remote-wsl

### Update WSL/Ubuntu
sudo apt update && sudo apt upgrade

### Install required packages for pokeemerald
sudo apt install build-essential binutils-arm-none-eabi git libpng-dev

# poryscript build and install

### install go 
sudo apt install golang-go

### go dependencies
go get -v -t -d ./

### build script
go build -v

### check go-dev.yml for more information

#porymap
https://github.com/huderlem/porymap/releases

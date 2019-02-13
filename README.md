# Web Development Environment Setup Scripts
> Scripts for Windows 10 and macOS X to install web development tools
> Absolutely NO WARRANTIES or GUARANTEES are provided.

## Windows 10
*System Requirements:* Windows 10 Pro v1703+ with PowerShell v5.1+ 
- In Powershell, execute `install-windows-deps.ps1`

## macOS X
*System Requirements:* macOS Sierra v10.12.6+ with Terminal (Bash or Oh My Zsh)
- In the Terminal, execute `install-mac-deps.sh`

## useful npm commands
- npx: Executes CLI tools by downloading the latest version on demand or project-specific local node_modules folder. It ships with npm 5 and will allow you to run code generators that frequently update without a global install.
- rimraf: The Unix command rm -rf, but works on Windows as well. Very useful in deleting the node_modules folder, especially when Windows is unable to do so due to the nested folder structure.
- npm-update: Analyzes your project folder and reports on which package have newer versions or not, with the option to be able to update all of them, if you so wish.
- n: Dead easy to tool to switch between versions of Node quickly, without having to remember the specific version number. Unfortunately, it only works on macOS/Linux.
- http-server: Simple, zero-configuration command-line HTTP server, which is a great way to locally test static HTML/CSS pages or even the dist folder of your Angular or React project.
- npm-windows-upgrade: Necessary to upgrade npm on Windows.

## vscode extensions
- johnpapa.angular-essentials
- PKief.material-icon-theme
- formulahendry.auto-close-tag
- PeterJausovec.vscode-docker
- eamodio.gitlens
- WallabyJs.quokka-vscode
- rbbit.typescript-hero
- DSKWRK.vscode-generate-getter-setter
- esbenp.prettier-vscode

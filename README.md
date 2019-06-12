# wsl-config
My ubuntu WSL config

1 - Install [WSL + Ubuntu](https://docs.microsoft.com/en-us/windows/wsl/install-win10);  
2 - Open the Ubuntu app and create an account;  
3 - Install zsh in the ubuntu app: ```sudo apt-get install zsh``` and then run ```chsh``` , choose zsh and add ```if test -t 1; then
  exec zsh
fi``` to the .bashrc file;  
4 - Install oh my zsh with ```git clone https://github.com/bhilburn/powerlevel9k.git ~/.oh-my-zsh/custom/themes/powerlevel9k```;  
5 - Install Powerline: https://medium.com/@jrcharney/bash-on-ubuntu-on-windows-the-almost-complete-set-up-1dd3cb89b794;  
6 - Install Hyper.js;  
7 - Use .zshrc and run ```source .zshrc```;  
8 - Install Hacker Nerd Fonts ```https://github.com/ryanoasis/nerd-fonts/tree/master/patched-fonts/Hack``` (For the terminal);  
9 - Install Meslo LG M Font ```https://github.com/ryanoasis/nerd-fonts/tree/master/patched-fonts/Meslo/M/Regular/complete```; (For VSCode terminal);  


### My Hyper configuration
![hyper terminal](https://raw.githubusercontent.com/brainlulz/wsl-config/master/hyper.PNG?token=AGT2OFQ6BOUY32W4OHUHJOK5AAMXM)  

### My VSCode configuration
![vscode](https://raw.githubusercontent.com/brainlulz/wsl-config/master/vscode.PNG?token=AGT2OFSMGGGVOKQAAZ4SIEC5AAMXM)

You can check my customs themes here: https://marketplace.visualstudio.com/publishers/alexlab

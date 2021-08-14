# Install_NVM_nodejs



nvm ls - lista todas as versões instaladas em sua máquina.

nvm ls-remote - lista todas as versões disponíveis para download do Node.js.

nvm install vX.X.X - baixa e instala uma versão do Node.js. Obs.: troque "vX.X.X" por "v0.10.22".

nvm uninstall vX.X.X - desinstala uma versão Node.js de sua máquina.

nvm use vX.X.X - define uma versão Node para uso.

nvm alias default vX.X.X - define uma versão default pra ser carregada primeiro.

Para habilitar o auto-completion do nvm, edite em modo super-user (sudo ou su) o .bashrc ou .bash_profile, incluindo no final do arquivo:



``` bash source "~/.nvm/bash_completion"

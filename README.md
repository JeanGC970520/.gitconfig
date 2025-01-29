# .gitconfig
Archivo de configuración para perfil de Git para uso privado
[user]
  name = Jean García
  email = jeanpoolgarcia_97@hotmail.com
[init]
  defaultBranch = main
[core]
  editor = vscode
[alias]
  s = status -sb .
  lg = log --graph --abbrev-commit --decorate --format=format:'%C(bold blue)%h%C(reset) - %C(bold green)(%ar)%C(reset0 %C(white)%s%C(reset) %C(dim white) - %an%C(reset)%C(bold yellow)%d%C(reset)' --all 
[pull]
  rebase = True

git config --global.name <gitname>
git config --global.email <gitemail> ->> preferir usar email privado

git config --global init.defaultBranch main -> default main e não master

git config --global color.ui auto -> saida com cor

git config --global pull.rebase false

git config --global core.editor  <editor> -> serve para configurar editor padrão

//
Crie um chave ssh: 
ssh-keygen -t ed25519 -C <youremail>

Pegue ela:
cat ~/.ssh/id_ed25519.pub

em seguide vincule ao seu Git.
//


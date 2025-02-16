# versionamento-git
Repositório para praticar controle de versionamento com GIT.

Faça um fork e contribua com suas ideias.

comandos aprendidos e funções:

git init
- Adiciona o novo projeto com git

git add <nome-arquivo>/.
- Adiciona os arquivos estão prontos para serem commitados

git commit -m "mensagem commit"
- commit os arquivos no histórico

git log
- Mostra os ultimos commits, log de alterações

git status
- Revela o estado das nossas ramificações, se possui alterações a serem feitas

git diff
- Mostra o que foi alterado
- o que tem de alteração na ramificação

git branch
- Mostra em qual branch estamos

git merge
- Merge de ramificações, mescla as alterações

git checkout <nome-branch>
- muda para essa branch

git branch -b <nome-branch>
- Criar uma nova branch a partir da branch atual que estamos

git remote add <nome> <url>
- Adiciona um novo repositorio remoto

git push <nome> <nome-da-branch>
- Manda nossas alterações locais para o repositorio remoto

git pull <nome> <nome-da-branch>
- Pega as alterações do repositório remoto, e joga para nossa maquina

git fetch
- Atualiza nosso histórico local de acordo com o histórico salvo la no repositório local
- Sincronização do local com o remoto

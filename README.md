# meu projeto

git init

- iniciar novo projeto com git

git add <nome-arquivo>/.
-add os arquivos estão prontos para serem comitados

git commit -m "mensagem commit"

- comitar os arquivos no histórico

git log

- mostra os últimos commit, log de alterações

git status

- como está o estado da nossa ramificação

git diff

- mostra o que foi alterado
- o que tem de alteração na ramificação

git merge

- merge de ramificações, mescla ramificações

git branch

- mostra a branch atual

git checkout <nome-branch>

- muda pra essa branch

git branch -b <nome-da-branch>

- cria uma nova branch a partir da branch atual que estamos

git remote add <nome> <url>

- add novo repositório remoto

git push <nome> <nome-da-branch>

- manda nossas alterações locais para o repositório remoto, pra cada branch

git pull <nome> <nome-da-branch>

- pega as alterações do repositório remoto, e joga pra nossa máquina

git fetch

- atualiza o novo historico local de acordo com o histórico salvo lá no repositório.
- sincronização com o remoto

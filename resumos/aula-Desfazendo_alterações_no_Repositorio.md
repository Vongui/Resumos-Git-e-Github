# 🗒️Resumo - Desfazendo alterações no repositorio local

## ⚠️Observação 
caso ocorra de inicicalizar o versionamento do Git no repositorio(Pasta) errado, não é necessário excluir totalmente o repositorio, pode-se só dar o comando ´rm rf .git´ que o versionamento do repositorio será desfeito

## 🧑🏾‍💻Comandos
rm rf <arquivo/pasta> -> excluir recursivamente o arquivo/pasta de maneira forçada

git restore --staged <File> -> restaura o arquivo para o último commit realizado

git log -> mostra o hitórico de commits

git commit --amend -m "nova_mensagem" -> modifica a mensagem do ultimo commit realizado

git reset -> remove o arquivo/pasta da lista de trackeados

git reset --soft <hash_commit> -> reverte para o commit que foi passado o hash, e adiciona na área de preparação prontos para serem commitados denovo

git reset --mixed <hash_commit> -> reverte para os commits posteriores do que foi passado o hash, e adiciona eles na área de trabalho como "untracked files", ou seja, ainda precisam ser enviados para a área de preparação --git add <File>--

git reset --hard <hash_commit> -> ignora totalmente os arquivos dos commits anteriores, e aponta diretamente para o hash que foi passado, ou seja, arquivos que foram commitados em outro hashs a frente do que foi passado serem perdidos e excluidos do repositorio

🚨 **Observação: Utilize esses comandos antes de envia-los para o repositorio remoto, pois facilita a compreensão dos commits, para que conflitos sejam resolvidos no repositoro local**


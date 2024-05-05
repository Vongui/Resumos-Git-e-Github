# 🗒️Resumo - Enviar e Baixar Alterações do Repositório Remoto

## ⚠️Observação 
É de suma importância, antes de enviar o commit para o Repositório remoto checar se os arquivos foram todos trackeados e commitados devidamente, utilizando o comando ´git status´ e ´git log´

## 🧑🏾‍💻Comandos
git remote add *origin* <https://github.com/Vongui/Resumos-Git-e-Github.git> -> conecta o repositorio local com o repositorio remoto passado  
🚨 **Observação: origin é o padrão utilizado pelo Github, se por acaso o seu tiver sido modificado, utilizar ele ao inves de origin**

git branch -M main -> força a branch a assumir o nome de main  
🚨**Utilize somente se o seu Git estiver configurado a branch como master ou outro nome**

git push -u origin main -> envia as alterações do repositorio local para o repositorio remoto

git pull -> Baixa as alterações do repositorio remoto para o repositorio local, e mescla com os arquivos locais 



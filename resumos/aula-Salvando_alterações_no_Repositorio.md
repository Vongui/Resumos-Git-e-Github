# 🗒️Resumo - Salvando alterações no repositorio local

## 🧑🏾‍💻Comandos
git status -> checa se dentro do repositorio Git possui alguma alteração não trackeada, ou seja, se foi criado ou alterado algo dentro do repositório  

git add <File> -> adiciona o arquivo ou pasta a lista de espera para commit

git commit -m "descricao_commit" -> cria um commit para aquela versão do repositorio

## Exemplos
´´´ $ touch README.md ´´´  
´´´	$ git status ´´´  
**Retorno do comando**  
´´´ On branch main
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md/

nothing added to commit but untracked files present (use "git add" to track)
	´´´  
´´´ $ git add README.md ´´´  
´´´ $ git commit -m "add README" ´´´
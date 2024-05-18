# 🗒️Resumo - Banches

## ⚠️Observação
Cuidado ao mexer com branches, sem o devido conhecimento pode ser que você perca o seu projeto, ou acabar danificando fazendo um commit com uma feature que não foi devidamente testada.

## O QUE É?
É uma ramificação do projeto, sendo basicamente um ponteiro móvel para um commit no histórico do repositório. Podendo adicionar features no projeto sem danificar a branch principal.
![Imagem ilustrativa do funcionamento de uma branch](https://i.im.ge/2024/05/19/Kl84K0.Captura-de-tela-2024-05-18-153857.png)

## 🧑🏾‍💻Comandos 
```$ git branch -> retorna a branch que está sendo utilizada, junto das outras branches criadas```

```$ git branch checkout __teste/main__-> alterna para a branch desejada ```

```$ git checkout -b __teste__ -> cria uma nova branch```

```$ git branch -d __teste__ -> deleta a branch.```

**obs: teste é somente ilustrativo, pode ser utilizado o nome que desejar para a criação de outra branch**

```$ git branch -v -> retorna o último commit de cada Branch.```

```$ git merge __teste__ -> mescla a branch com a branch main, juntando os commits das duas branchs```

```$ git fetch origin main -> Baixa as alterações do repositório remoto para o repositório local```

```$ git diff main origin/main -> retorna as diferenças de arquivos do repositório remoto e local ```

```$ git merge origin/main -> Baixa as alterações do repositório remoto, sem que mescle com o repositório local```

```$ git clone <https://github.com/Vongui/Resumos-Git-e-Github.git> --branch _nome da branch_ --single-branch -> clona as alterações somente da branch escolhida```

```$ git stash -> Arquiva alterações que não foram instanciadas com (git add)```

```$ git stash list -> Lista as modificações arquivadas ```

```$ git stash pop -> Adiciona as modificações arquivadas na branch e deleta a pilha de modificações arquivadas```

```$ git stash apply -> Adiciona as modificações arquivadas na branch, mas não deleta a pilha de arquivas```

## **Conflito de Merge**
Conflitos podem ser comuns diversos cenários, um dos mais comuns seria o commit duplo: seu e de um colega, no qual você faz alterações nos arquivos, e o seu colega também, e quando enviam possui um erro de compatibilidade pois, os arquivos estão diferentes em ambos os casos.

| Links Úteis|
|------------| 
| [Book Branchs](https://git-scm.com/book/en/v2/Git-Branching-Branches-in-a-Nutshell)| 
|[Outros Comandos](https://git-scm.com/docs/git-branch)|
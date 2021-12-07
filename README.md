# Tutorial GIT
<div align="center">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" align="center" height="180em" width="180em" >
</div>

## Olá dev! Esse projeto ensinará você a usar o Git.

### Conceitos
* O **Git** é um sistema de controle de versões, funciona como uma espécie de máquina do tempo dos códigos, nele você pode ter acesso a todos os
seus códigos e as alterações feitas nele.

* O **GitHub** é o repositório remoto ou também chamado a rede social dos desenvolvedores.

* **Fork** é uma cópia do repositório principal ao qual você pode fazer mudanças e features neste clone, sem afetar o repositório principal.

* **Post Request** é o pedido para que o repositório original faça a ação pull (puxar) as atualizações do repositório fork ou da branch.

* **Área de Stage** é onde você controla a versão do seu repositório. Esta área não grava as mudanças, pois ela apenas inicia o repositório
com o comando git add, as mudanças são gravadas com o git commit, o foco desta separação é para gerar mais produtividade.

* **Branchs** é uma ramificação do projeto, ela representa uma versão do projeot, se pode seguir uma linha de desenvolvimento a partir de cada branch.

### Comandos Básicos
* cd .. (Retorna a pasta anterior.)
* cd + nome pasta (ela abra a pasta)
* ls (lista todas as pastas)
* git status (vê o status atual do repositório)
* git log (lista todos os commits já realizados)
* git show (mostra as alterações feitas no último commit)
* git help (imprime uma lista de comandos masi usados)
* clear (limpa a tela do terminal)
* q (sai do log ou de determinada função)
* git rm (remove arquivos)
* git -mv (move ou renomeia arquivos)
* git reset -hard (olta seu repositório para sem modificações nenhumas até o último commit)

### Conectar seu repositório local ao Git-Hub
* git init (inicia o repositório na pasta)
* git add . (adiciona todos os arquivos da pasta)
* git commit -m "mensagem" (faz a mensagem do commit)
* git remote add origin +link (adiciona no repositório do git)

### Enviar alterações para o Git-Hub
* git add . (adiciona arquivos)
* git commit -m "mensagem" (faz a mensagem do commit)
* git push -u origin master (envia o arquivo para o GitHub)

### Adicionais
* git branch -m "branch" (renomeia a branch atual)
* git checkout -b "nome-da-nova-branch" ou git checkout nome-branch (usamos para criar ou alterar a branch)
* git merge nome-da-branch (unir uma branch na outra)
* git clone link-do-repositorio (copia o repositório para sua máquina)
* git pull (atualiza o repositório copiado)



 # Semana 2 Repositório Colaborativo
## Atividade: Colaboração no Git com Branches e Contribuições no README.md
<img width="212" alt="Captura de Tela 2024-09-09 às 17 42 28" src="https://github.com/user-attachments/assets/ff68ffdf-1fc1-471a-baec-f4b6089081b6">

### Bem-vindo à Campinho Digital!

Parabéns! Você foi contratado como desenvolvedor júnior na Campinho Digital. Agora é hora de iniciar suas contribuições no repositório da empresa. Seu primeiro passo será enviar um e-mail solicitando acesso ao repositório, depois clonar o projeto e realizar suas primeiras contribuições.

Aqui estão as etapas detalhadas que você deve seguir para começar a contribuir com o repositório colaborativo da `Campinho Digital`, praticando conceitos como criação de `branches`, `commits`, `pull requests`, e `merge`.


## Objetivo
Essa atividade tem como objetivo familiarizar os participantes com o fluxo de trabalho colaborativo no Git, utilizando comandos como git branch, git checkout, git merge, além de criar, editar e resolver conflitos em branches separadas. Os alunos irão aprender a contribuir em um repositório Git colaborativo, criar branches, realizar commits e enviar suas alterações para o repositório remoto.

## O que fazer primeiro?
O primeiro passo para começar a trabalhar com o repositório da empresa é solicitar o acesso.
Envie um e-mail para o administrador de projetos da `Campinho Digital`

## O que preciso saber para começar:

Para contruibuir com o projeto `Campinho Digital`é importante conhecer o `markdown`

## O que é markdown?
Markdown é uma linguagem de marcação leve que permite que você escreva conteúdo formatado de maneira simples e intuitiva. Você pode escrever cabeçalhos, listas, links e muito mais de forma rápida, e o resultado pode ser convertido em HTML ou outros formatos.

### Características principais do Markdown:

Simplicidade: Fácil de ler e escrever.
Formato Texto Plano: Arquivos .md podem ser editados em qualquer editor de texto.
Conversão Simples: Convertido facilmente para HTML ou PDF.
Você pode consultar este guia para aprender mais sobre Markdown.

## Descrição da Atividade
### 1. Preparação do Ambiente
Pré-requisito: Tenha o Git instalado no seu computador.
Editor sugerido: Recomendo o uso do VSCode para edição de código e execução de comandos Git, ou o terminal, caso prefira.
### 2. Clonando o Repositório
O repositório onde vocês irão colaborar está disponível no GitHub. Primeiro, você deve clonar esse repositório no seu ambiente local.

Acesse o repositório no GitHub.

`Copie o link SSH`

No terminal, rode o comando abaixo para clonar o repositório:


~~~javascript
git clone <URL_DO_REPOSITORIO>
~~~

Navegue até a pasta do repositório:


~~~
cd webfrontend-2024-2-semana-1
~~~

### 3. Criando e Trocando de Branches
Para garantir um fluxo de trabalho colaborativo eficiente, cada participante deve criar sua própria branch para adicionar contribuições. Isso evita conflitos diretos no branch principal (geralmente chamado de main ou master).

Criar um novo branch para sua contribuição:

Escolha um nome descritivo para sua branch, como minha-contribuicao.


~~~
git checkout -b minha-contribuicao
~~~

Verifique em qual branch você está:

~~~
git branch
~~~

Isso exibirá uma lista das branches locais. A branch no qual você está atualmente será marcado com um *.

### 4. Fazendo Contribuições 
Agora que você está em uma nova branch, pode fazer alterações no repositório.

- crie um arquivo seu_nome.md no editor de sua escolha.

- Adicione uma seção no final do arquivo com seu nome, e uma apresentação sobre você.



~~~
Olá, somos a campinho digital... etc
~~~

### 5. Commitando as Alterações
Agora que você fez uma alteração, vamos salvar (commitar) essa mudança no Git.

Adicione os arquivos modificados para o stage:
~~~
git add .
~~~

Crie um commit com uma mensagem descritiva:

~~~
git commit -m "Adicionei minha contribuição no README.md"
~~~

### 6. Enviando Suas Alterações para o Repositório Remoto
Após fazer o commit, você precisa enviar suas alterações para o repositório remoto.

Empurre (push) suas alterações para o GitHub:

~~~
git push origin minha-contribuicao
~~~
 
Isso enviará as alterações para o repositório remoto na sua branch criada.

### 7. Criando um Pull Request
   
Depois de enviar suas alterações para o GitHub, é hora de criar um Pull Request (PR). Esse é o processo de solicitar que suas alterações sejam mescladas na branch principal (main ou master).

Acesse o repositório no GitHub.

Você verá um botão para criar um novo `Pull Request` com base na branch que você enviou (minha-contribuicao).

Preencha o título e a descrição da PR, explicando as alterações que você fez.

Envie a PR para revisão.
### 8. Revisando e Aceitando Pull Requests
Se for o proprietário do repositório ou tiver permissões de revisão, siga os seguintes passos:

Acesse a lista de Pull Requests.
Revise as mudanças propostas pelos colaboradores.
Se as mudanças estiverem adequadas, faça o merge para incorporar as alterações na branch principal.
Caso seja necessário, comente sobre melhorias ou faça alterações antes de aceitar.

### 9. Sincronizando Suas Alterações Locais com o Repositório Remoto
    
Se outros colaboradores fizeram mudanças na branch principal enquanto você trabalhava na sua branch, é importante garantir que sua cópia local esteja atualizada. Para isso, siga os passos abaixo:

Troque para a branch principal:

~~~
git checkout main
~~~

Puxe as mudanças mais recentes do repositório remoto:

~~~
git pull origin main
~~~

Mergir as alterações recentes na sua branch (caso necessário):


~~~
git checkout minha-contribuicao
~~~

~~~
git merge main
~~~
Resolva conflitos, se houver, e commit suas alterações.

#### Conceitos e Comandos Praticados
`git clone:` Para clonar o repositório remoto para o ambiente local.

`git branch:` Para criar e listar branches.

`git checkout:` Para trocar de branch.

`git add:` Para adicionar arquivos ao stage.

`git commit:` Para criar um commit com uma mensagem descritiva.

`git push:` Para enviar suas alterações para o repositório remoto.

`git pull:` Para obter as alterações mais recentes do repositório remoto.

`Pull Request (PR):` Para solicitar que suas alterações sejam mescladas à branch principal.

##### Desafios Adicionais
Resolução de Conflitos: Se dois ou mais contribuidores modificarem a mesma linha de código, um conflito ocorrerá. Pratique a resolução de conflitos quando fizer merge de branches.

Rebase: Experimente o comando git rebase para reordenar commits antes de fazer um merge.

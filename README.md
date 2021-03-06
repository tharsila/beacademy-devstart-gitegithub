<h1 align="center">:computer: Lista de Comandos Git</h1>
 
<h2>Tabela de Conteúdos</h2>
 <ul>
  <li><a href="#sobre-o-projeto">Sobre o projeto</a></li>
  <li><a href="#configuracoes-iniciais">Configurações iniciais</a></li>
  <li><a href="#comandos-basicos">Comandos básicos</a></li>
  <li><a href="#gestao-de-branches">Gestão de branches</a></li>
  <li><a href="#gestao-de-stash">Gestão de stash</a></li>
  <li><a href="#licença">Licença</a></li>
 </ul>
  
<h2 id="sobre-o-projeto">:page_with_curl: Sobre o projeto</h2>
<p>O projeto é composto de uma lista com alguns do principais comandos utilizáveis no Git, cuja criação foi proposta durante o programa DevStart Paylivre.<p>
<hr>

<h2 id="configuracoes-iniciais">:hammer: Configurações iniciais</h2>
<p>A primeira etapa que deve ser realizada ao instalar Git é configurar nome de usuário e endereço de e-mail.</p>

Configurar nome do usuário:
```
git config --global user.name "seu nome"
```

Configurar email:
```
git config --global user.email "email@exemplo.com"
```
<hr>

<h2 id="comandos-basicos">:large_blue_diamond: Comandos básicos</h2>

| Comando     | Descrição                           |
| :---------- | :---------------------------------- |
| `git init` | Inicia um repositório git na pasta atual |
| `git status` | Exibe as condições do diretório de trabalho e da área de staging |
| `git add` | Adiciona uma alteração no diretório ativo à área de staging |
| `git rm` | Remove arquivos individuais ou uma coleção de arquivos |
| `git commit` | Cria uma "snapshot" do repositório. Deve ser acompanhado de uma mensagem |
| `git log` | Exibe os registros log do commit |
| `git clone <url>` | Clona um repositório remoto localmente |
| `git remote` | Conecta o repositório local à um repositório remoto |
| `git push` | Envia os commits locais para o branch remoto |
| `git pull` | Sincroniza o branch remoto com o branch local |

<hr>

<h2 id="gestao-de-branches">:large_blue_diamond: Gestão de branches</h2>

| Comando     | Descrição                           |
| :---------- | :---------------------------------- |
| `git branch` | Lista todas as ramificações do repositório |
| `git branch <nome_da_branch>` | Cria uma nova ramificação especificada|
| `git checkout -b <nome_da_branch>` | A branch será criada e em seguida o checkout será feito |
| `git branch -d <nome_da_branch>` | Deleta a ramificação especificada |
| `git merge <nome_da_branch>` | É usado para mesclar duas branches |

<hr>

<h2 id="gestao-de-stash">:large_blue_diamond: Gestão de stash</h2>

| Comando     | Descrição                           |
| :---------- | :---------------------------------- |
| `git stash` | Arquiva alterações não commitadas do local de trabalho |
| `git stash --include-untracked` | Realiza o stashing dos arquivos não rastreados |
| `git stash list` | Apresenta a lista de stashes existentes |
| `git stash pop` | Aplica as mudanças de um stash no diretório de trabalho e remove o stash da pilha em seguida|
| `git stash drop` | Remove um stash específico da lista |


<h2 id="licença">:memo:Licença</h2>
<p> Feito com :blue_heart: por <strong>Tharsila Borges</strong></p>

<hr>

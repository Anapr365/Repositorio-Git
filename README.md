# Repositorio Git

 Criando o repositorio ensinando  como criar um projeto

 ## GIT – comandos básicos

O Git é um sistema de controle de versão distribuído, ele foi criado para verificar alterações no código fonte, no processo de desenvolvimento de software.

O GIT funciona em um esquema de linha do tempo, onde se tem uma linha do tempo principal, a partir desta linha do tempo pode ser criado outras linhas que são os ramos

#### Configuração Git Bashe Here

A primeira coisa que você deve fazer ao instalar Git é configurar seu nome de usuário e endereço de e-mail. Isto é importante porque cada commit usa esta informação, e ela é carimbada de forma imutável nos commits que você começa a criar:

$ git config --global user.name "Fulano de Tal"
$ git config --global user.email fulanodetal@exemplo.br
$ git config --global core.editor emacs


![Git Bash](https://github.com/Anapr365/Repositorio-Git/blob/main/imagens/Capturar1.png)


#### Git no Powershell
O terminal de linha de comando padrão no Windows (cmd.exe) não é realmente capaz de uma experiência Git personalizada, mas se tu estiveres a usar o Powershell, tu estás com sorte. Um pacote chamado Posh-Git (https://github.com/dahlbyk/posh-git) fornece poderosas instalações de preenchimento de tabulações, bem como um prompt aprimorado para ajudá-lo a permanecer em cima do status do teu repositório. 

> Set-ExecutionPolicy -Scope LocalMachine -ExecutionPolicy RemoteSigned -Force

Instalação do Modulo Posh-Git (Opcional)

Atualiza o Prompt do PowerShell

Para incluir as informações git no teu prompt, ele precisa de ser importado. Para fazeres isto automaticamente, inclui a declaração de importação no teu script de $perfil. Este script é executado toda vez que tu abres um novo prompt do PowerShell. Tem em mente que existem múltiplos scripts de $perfil. Por exemplo: um para a console e outro para o ISE.

> 'Import-Module Posh-Git' | Out-File -Append -Encoding default -FilePath $profile

### O que é o PowerShell
![PowerShell](https://github.com/Anapr365/Repositorio-Git/blob/main/imagens/powershell.PNG)


## Crie uma conta do GitHub e configure seu perfil
Se você ainda não tem uma conta do GitHub, crie uma. Identifique qualquer afiliação no seu perfil do GitHub.  A identificação nos ajuda a criar um perfil completo de todas as suas atividades.

 você precisa configurar sua própria conta do GitHub.

![Junte-se ao GitHub
crie sua conta](https://github.com/Anapr365/Repositorio-Git/blob/main/imagens/Capturar%20g.PNG)

## Configurar o GitHub Desktop
Você pode instalar o GitHub Desktop em qualquer sistema operacional compatível. Para obter mais informações, consulte "Sistemas operacionais compatíveis".

Para instalar o GitHub Desktop, acesse https://desktop.github.com/ e baixe a versão apropriada do GitHub Desktop para o seu sistema operacional. Siga as instruções para concluir a instalação. Para obter mais informações, consulte "Installing GitHub Desktop."

 Configurando a sua conta
Se você tiver uma conta no GitHub ou no GitHub Enterprise, você poderá usar GitHub Desktop para trocar dados entre os seus repositórios locais e remotos.

### O Que é GitHub Desktop
O Github tem sim muita relação com o Git. GitHub é uma plataforma para gerenciar seu código e criar um ambiente de colaboração entre devs, utilizando o Git como sistema de controle. Ele vai facilitar o uso do Git, escondendo alguns detalhes mais complicados de setup. É lá que você provavelmente vai ter seu repositório e usar no dia a dia.

![GitHub Desktop](https://github.com/Anapr365/Repositorio-Git/blob/main/imagens/Capturar.PNG)


O Github é um serviço web que oferece diversas funcionalidades extras aplicadas ao git. Resumindo, você poderá usar gratuitamente o github para hospedar seus projetos pessoais. Além disso, quase todos os projetos/frameworks/bibliotecas sobre desenvolvimento open source estão no github, e você pode acompanhá-los através de novas versões, contribuir informando bugs ou até mesmo enviando código e correções.

# GIT – comandos básicos

#### git init

#### git add index.html

#### git status

#### git commit

#### git add meu_diretorio

#### Comitar vários arquivos
git commit meu_arquivo.txt meu_outro_arquivo.txt

Adicionar um arquivo que esta listado no .gitignore (geral ou do repositório)
#### git add -f arquivo_no_gitignore.txt

#### Comitar vários arquivos
git commit meu_arquivo.txt meu_outro_arquivo.txt

Remover arquivo/diretório

### Remover arquivo
git rm meu_arquivo.txt

#### Remover diretório
git rm -r diretorio

####  histórico
git log

#### Exibir histórico com diff das duas últimas alterações
git log -p -2


git clone https://github.com/Anapr365
#### Verificar estado dos arquivos:









# Comandos Git 💻

# Configuração e Ajuda

​		• `git --version`

​				Verifica a versão instalada no dispositivo

​		• `git config` 

​				Utilizando o comando `git config` pode definir o nome de usuário e endereço de e-mail,  pois esses dados são utilizados nos commits do Git , sendo inclusive imutáveis uma vez criado o projeto. 

​							`git config --global user.name "NOME"`

​							`git config --global user.email "email"`

​				Utilizando a opção `git config --global` torna as definições permanentes para qualquer coisa que seja realizada no sistema. Pode sobrepor com outras informações de definição em projetos específicos, usando o comando sem o `--global`.

​		• `git help`

​				Fornece explicação e comandos e funções do sistema. 

​				Outras formas de obter ajuda no Git:

​					`git help {comando}`

​					`git {comando} --help`

## Criação de projetos

​		• `git init` 

​				Inicia um repositório local.

​		• `git clone` [url]

​				Clona um repositório já existente no GitHub, incluindo após o comando a URL do repositório do GitHub.

## Compartilhar e Atualizar projetos

​		• `git push `

​				Faz o upload do commit para o servidor remoto fornecido pelo endereço do repositório no site.

​		• `git pull`

​				Faz  download dos arquivos de um repositório online

## Básico

​		• `git add`

​				Adiciona os arquivos ou diretórios modificados.

​		• `git rm`

​				Remove um arquivo do diretório.

​		• `git status`

​				Ferramenta que determina o estado dos arquivos.

​		• `git commit`

​				Gera um novo commit. É usado depois de usar o comando`git add`com a flag `-m` seguida da mensagem entre aspas.

​				`git commit -m "msg..."`
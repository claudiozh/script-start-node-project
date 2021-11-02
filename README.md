# Start novo projeto em nodejs

Projeto com um arquivo de Script para montar um ambiente de 
desenvolvimento Node usando Yarn, Typescript, Eslint 
e Plugins para padronização de commits(Commitlint, Commitzen, Husky)

## Avisos

É importante executar o script depois que já tenha iniciado o repositório git na máquina local

## Como usar

* Clone o projeto em um diretório da sua máquina
* Copie o caminho absoluto dele
* Abra o arquivo .bashrc ou .zshrc 
```
sudo SEU_EDITOR_DE_TEXTO ~/.bashrc 
```

* Depois cole a seguinte linha

```
alias start-node-project='CAMINHO_ABSOLUTO_DO_ARQUIVO_SH' 
```

* Feito isso esse comando já estará disponivel de forma global na máquina
* Depois crie a pasta do projeto e inicie o git ou clone um projeto já existente e execute o seguinte comando

```
start-node-project
```

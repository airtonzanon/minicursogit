# Minicurso Git

### Contribuindo com o projeto

* Faça fork do projeto
* Em seu computador: git clone https://github.com/NOME DO SEU USUARIO/minicursogit.git
* Crie um novo branch. Ex: git checkout -b adicionando-aluno
* Entre na pasta de sua faculdade. Ex: cd fatecjales
* Crie uma pasta com seu nome e sobrenome. Ex: mkdir airtonzanon
* Entre na sua pasta. Ex: cd airtonzanon
* Crie um arquivo dados.md. Ex: vi dados.md
* Adicione seu nome e faculdade. Ex: Airton Zanon - Fatec Jales (para salvar e fechar, pressione ESC e digite :wq)
* Volte para a base do projeto. Ex: cd ../../
* Adicione os arquivos na stage. Ex: git add -A
* Faça commit. Ex: git commit -m "Adicionando novo aluno"
* Envie seus dados para seu repositório. Ex: git push origin adicionando-aluno
* Abra seu repositório no Github e faça o pull request.

### Caso precise atualizar seu repositório

* Crie seu upstream. git remote add upstream https://github.com/airtonzanon/minicursogit.git
* Faça o fetch do projeto. Ex: git fetch --all
* Realize o merge do projeto. Ex: git merge master upstream/master
* Faça as alterações desejadas

### Erros e sugestões

* Envie erros e sugestões do projeto para airtonzanon@gmail.com 

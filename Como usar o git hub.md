Esta é a minha primeira experiência no git hub.

O que se foi entendido sobre o funcionamento do git:

Como criar um repositório no GitHub:
Depois de ter criado a conta na plataforma e instalado o Git na minha máquina, agora já posso hospedar o meu primeiro projeto no GitHub.com. Para isso:

Abro o terminal de comando do meu sistema operacional;
Dentro da pasta do projeto, digito: git init
O comando acima irá criar toda a estrutura básica do repositório;
Para adicionar todos os arquivos alterados à fila de atualizações do repositório, executo o comando: git add .
Antes de sincronizar as alterações, configuro meu usuário do GitHub com os comandos:
git config --global user.name "meu nome"
git config --global "email no GitHub"
Confirmo as alterações com o comando: git commit -m "mensagem"
no qual “mensagem” geralmente é um resumo das alterações.
Adiciono o remote, ou seja, o link para o servidor do meu projeto no GitHub:
git remote add origin usuário no GitHub>/<nome do repositório>.git
Por fim, envio as alterações com o comando:
git push remote origin
Se tudo deu certo, será exibido uma mensagem confirmando o envio.
# git commit

Esse comando salva as alterações criando um check point para indicar que houve mudança no projeto. Possue um parametro -m para colocar uma mensagem indicativa da mudança.

O comando a seguir efetiva uma alteraçao no projeto e demonstra o uso do parametro -m <br> 
git commit -m "Criando um arquivo index.html simples"

A boa prática pede para colocarmos mensagens descritivas, evitando que fiquem muito grandes.

Quando dermos “Enter”, o Git Bash nos informa que este é o root-commit ou commit base dentro de um master, e exibe a mensagem que configuramos.

Também é mostrado quais foram as alterações, no caso, apenas 1, com 15 inserções (linhas).

Se executarmos git status novamente, teremos que não há nada a ser commitado, entretanto ele não mostra mais que não há commits ainda.

Executando o git commit novamente
Se fizermos outra modificação dentro do nosso arquivo index.html, teremos que salvar o nosso arquivo.

Utilizar o comando git status para verificar que há uma modificação não salva dentro do repositório Git.

Adicionar as alterações utilizando o git add, depois disso se dermos o git status novamente veremos que existem mudanças a serem commitadas.

E por fim utilizaremos novamente o comando git commit informando uma breve mensagem sobre a alteração.

Quando devo fazer um commit?
Devemos gerar um commit sempre que a nossa base de código está em um estado do qual gostaríamos de nos lembrar.

Nunca devemos ter commits de códigos que não funcionam, mas também não é interessante deixar para commitar apenas no final de uma feature.

Enfim, essa pode ser uma discussão sem fim e cada empresa ou equipe pode seguir uma estrat

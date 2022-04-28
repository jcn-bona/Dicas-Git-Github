# git add

O comando git add pertence ao sistema de controle de versões chamado de Git. Esse comando realiza a inclusão ou modificação do arquivo no diretório local, preparando ele para ser entregue ao servidor remoto para a mesma aplicação que está sincronizada na máquina local.

Dentre todos os comandos que pertencem ao Git, esse é o mais importante deles, afinal, é utilizado para sinalizar que houve interação no diretório local. Para entendermos melhor, se utilizarmos o comando git commit primeiro do que o comando git add, as alterações locais não refletirão no servidor remoto. Por isso, é importante entender a sequência correta dos comandos do Git.

O comando git add mantém o histórico de todas as ações realizadas no código, permitindo que, se algum problema ocorrer na aplicação, o comando de desfazer alteração possa ser acionado.

### Dica importante:
O comando git add pode ser utilizado a qualquer momento durante o processo de alteração do arquivo, porém, a melhor prática é realizar todas as alterações e quando tudo estiver pronto, utilizamos esse comando. Caso queira verificar quais serão as alterações que serão reproduzidas no servidor remoto, utilize o comando git status.

### Área de staging Git
Os recursos oferecidos pelo Git não se limitam apenas aos comandos de transição de mudanças nos arquivos. Um dos principais diferenciais dessa ferramenta é o recurso chamado staging area (área temporária).

O recurso staging area é um espaço temporário criado a partir da primeira inclusão ou alteração realizada no diretório local do projeto. Com isso, é possível controlar todas as interações realizadas, permitindo reverter qualquer ação indesejada a qualquer momento.

Além disso, a staging area permite que seja realizado vários commits a partir dela.

Vamos explicar como isso funciona:<br>
Nessa área temporária estarão todas as alterações realizadas no projeto. Você pode escolher um ou mais arquivos para realizar o comando git adde, em seguida, o comando git commit, permitindo maior flexibilidade e agilidade no processo de sincronização de códigos entre os servidores local e remoto.

Como usar o Git add?
Usar o comando git add é muito simples e prático. O exemplo a seguir pode ser executado diretamente no Git Bash ou em uma IDE de sua preferência:

No projeto local, crie uma branch:<br>
git branch “Aqui vai o nome da branch”<br>
Realize o checkout da nova branch:<br>
git checkout “Aqui vai o nome da branch”<br>
Adicione um ou mais arquivos;
Salve todas as alterações;
Prepara as mudanças realizadas no diretório local:
git add . “Aqui vai o nome da branch”
Enviar as alterações locais para o servidor remoto:
git commit “Aqui vai o nome da branch”
Com esse exemplo, foi possível utilizar os principais comandos do Git. Nos próximos tópicos, vamos aprender outras opções utilizadas para esse comando.


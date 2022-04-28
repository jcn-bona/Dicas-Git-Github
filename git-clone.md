# git clone 

Git clone é um dos muitos comandos do Git. Ele tem como principal proposta clonar todos os arquivos de repositório remoto para um repositório local. Por padrão, todo o histórico de commits, branches e merges são copiados também. Esse comando é muito útil para quando precisamos de uma nova cópia do projeto ou simplesmente porque queremos conferir alguns arquivos.

Para simplificar, um repositório remoto hoje em dia provavelmente está alocado em algum site famoso de Git, como o Github, GitLab e Bitbucket, etc. Sendo assim, se o repositório for público, qualquer um que esteja interessado pode clonar algum dos milhares de projetos dessas plataformas.

Um exemplo do git clone pode ser encontrado abaixo, nele é mostrado uma cópia do repositório central armazenado em um servidor com o nome de exemplo.com com o usuário do SSH fulano:

git clone ssh://fulano@exemplo.com/caminho/para/o/meu-projeto.git 
cd meu-projeto
  
O primeiro comando inicia um repositório Git novo na pasta meu-projeto na sua máquina local e a popula com os dados do servidor remoto. Então, você pode dar um cd para entrar no repositório previamente criado e começar a fazer alterações nos arquivos, commitar alterações, criar tags ou qualquer coisa do gênero. Veja que a extensão .git foi omitida no repositório clonado, isso significa que o status da cópia não é vazio.

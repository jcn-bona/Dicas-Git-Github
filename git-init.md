## git init
O comando git init cria um novo repositório do Git. Ele pode ser usado para converter um projeto existente e não versionado em um repositório do Git ou inicializar um novo repositório vazio. A maioria dos outros comandos Git não está disponível fora de um repositório inicializado, portanto, este costuma ser o primeiro comando que você executa em um novo projeto.

A execução do git init cria um subdiretório .git no diretório de trabalho atual, que contém todos os metadados Git necessários para o novo repositório. Esses metadados incluem subdiretórios para objetos, referências e arquivos de template. Também é criado um arquivo HEAD que aponta para o commit em uso no momento.

Além do diretório .git, no diretório raiz do projeto, um projeto existente permanece inalterado (diferente do SVN, o Git não requer um subdiretório .git em cada subdiretório).

Por padrão, o git init vai inicializar a configuração do Git para o caminho do subdiretório .git . O caminho do subdiretório pode ser modificado e personalizado se você quiser que ele seja hospedado em outro lugar. Você pode definir a variável de ambiente $GIT_DIR como um caminho personalizado e o git init vai inicializar os arquivos de configuração do Git lá. Ou você pode usar o argumento --separate-git-dir para o mesmo resultado. Um caso de uso comum para um subdiretório separado .git é manter os "dotfiles" de configuração do sistema (.bashrc, .vimrc, etc.) no diretório inicial, mantendo a pasta .git em outro lugar.


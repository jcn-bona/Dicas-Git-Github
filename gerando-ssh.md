
### Gerando um novo par de chaves

Caso não exista nenhum par de chaves existentes, precisamos gerar um novo par de chaves. Falamos "par de chaves" porque assim que gerarmos uma chave, serão criados dois arquivos, um público (.pub) e um privado. O conteúdo do arquivo público é o que futuramente colocaremos no github para fazer a conexão.

Para criar uma chave ed25519, executar: ssh-keygen -t ed25519 -C "your_email@example.com"
Para criar uma chave rsa, executar: ssh-keygen -t rsa -b 4096 -C "your_email@example.com"

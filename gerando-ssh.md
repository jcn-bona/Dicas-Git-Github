
### Gerando um novo par de chaves

Por padrão o nome das chaves devem ser um desses: "id_rsa.pub", "id_ecdsa.pub" ou "id_ed25519.pub".

Para gerar um novo par de chaves, o comando é

Para uma chave ed25519: ssh-keygen -t ed25519 -C "your_email@example.com"

Para uma chave rsa: ssh-keygen -t rsa -b 4096 -C "your_email@example.com"

O conteúdo do arquivo público é o que futuramente colocaremos no github para fazer a conexão.


### Adicionar chave privada no ssh-agent

O ssh-agent é um gerenciador de chaves ssh. Para que a conexão funcione, devemos adicionar a chave privada nesse gerenciador. Para isso vamos executar os códigos:

Executa o ssh-agent <br>
eval $(ssh-agent -s)
Inclui a chave privada <br>
ssh-add ~/.ssh/id_ed25519

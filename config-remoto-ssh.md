### Copiar a chave pública

Agora que já adicionamos a chave privada no ssh-agent, vamos copiar a chave pública que faz par com ela, para incluirmos no nosso github.

No mesmo terminal executar:
- No Windows: clip < ~/.ssh/id_ed25519.pub
  - Automaticamente o conteúdo da sua chave pública será copiado para a área de transferência
  
- No Linux: cat ~/.ssh/id_ed25519.pub
  - O conteúdo da chave pública aparecerá no terminal para ser selecionado e copiado

- No MacOS: pbcopy < ~/.ssh/id_ed25519.pub
 
### Adicionar chave no Github

Abra o Github e vá no ícone de perfil > Settings, no canto superior direito.<br>
Na barra lateral de configurações do usuário, clique em "SSH and GPG keys".<br>
Clique no botão "New SSH key"<br>
No campo "Título", adicione um rótulo descritivo para a nova chave. Por exemplo, se estiver usando seu computador pessoal, você pode chamar essa chave de "Computador pessoal".<br>
Cole a chave pública que está na área de transferência no campo "Chave".<br>
Clique em "Add SSH key" e pronto!

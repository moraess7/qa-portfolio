# Casos de Teste – Login

CT-001 – Login com e-mail vazio  
Pré-condição: Usuário na tela de login  

Passos:
1. Acessar a tela de login  
2. Não informar o e-mail  
3. Informar senha válida  
4. Clicar em "Entrar"  

Resultado esperado:
Sistema deve exibir mensagem informando que o e-mail é obrigatório.


CT-002 – Login com senha inválida  
Pré-condição: Usuário na tela de login  

Passos:
1. Acessar a tela de login  
2. Informar e-mail válido  
3. Informar senha inválida  
4. Clicar em "Entrar"  

Resultado esperado:
Sistema deve exibir mensagem de erro de credenciais inválidas.


CT-003 – Login com dados válidos  
Pré-condição: Usuário na tela de login  

Passos:
1. Acessar a tela de login  
2. Informar e-mail válido  
3. Informar senha válida  
4. Clicar em "Entrar"  

Resultado esperado:
Usuário deve ser redirecionado para a página inicial.

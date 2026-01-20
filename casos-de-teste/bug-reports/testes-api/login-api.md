Teste de API – Login

Método: POST  
Endpoint: /api/login  

Cenários testados:
- Login com e-mail válido  
- Login com senha inválida  
- Login com campos vazios  

Resultado esperado:
API deve retornar status 200 para login válido  
API deve retornar erro 400 para dados inválidos  

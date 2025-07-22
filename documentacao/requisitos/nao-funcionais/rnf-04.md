**RNF04 - Segurança**

* O sistema deve garantir a segurança dos dados e transações. Todos os dados sensíveis (credenciais de usuário e informações pessoais) devem ser transmitidos apenas sob conexão criptografada (HTTPS/TLS 1.2+). 

* As senhas dos usuários devem ser armazenadas usando algoritmo de hash seguro (por exemplo, bcrypt ou Argon2, com salt único por senha). 

* O sistema deve seguir as melhores práticas de segurança web para prevenir ataques comuns – por exemplo, como SQL Injection, XSS, CSRF e outros itens do OWASP Top 10 de vulnerabilidades web. 

* Além disso, deve utilizar token JWT para controle de acesso adequado no lado do servidor para impedir que usuários não autenticados ou não autorizados acessem funções administrativas ou dados de outros usuários.

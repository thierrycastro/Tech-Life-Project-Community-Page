Projeto: Tech Life – Página Comunidade

Nome do Caso de Teste: Validação de Cadastro

Descrição: Este caso de teste verifica a funcionalidade do sistema da página Comunidade. O objetivo é garantir que o sistema permita que um usuário crie uma nova conta e posteriormente faça login com credenciais válidas e bloqueie o acesso quando são fornecidas credenciais inválidas.

-----

Pré-condições:

•	O ambiente de teste deve estar configurado e acessível.

•	O navegador deve estar instalado e funcionando corretamente.

-----

Passos para a execução do teste:
1.	Abra o navegador e navegue até a página "https://techlifept.com/".
2.	Clique no link “Comunidade” no menu superior.
3.	Clique no link “Cadastre-se”.
4.	Verifique se o usuário é redirecionado para a página Novo Cadastro.
5.	Insira os dados corretamente.
6.	Clique no botão "Enviar".

 -----
 
Critérios de Aceitação:

•	O usuário deve ser redirecionado para a página inicial após fazer o cadastro.

•	Uma mensagem de erro deve ser exibida quando o usuário tentar fazer login com credenciais inválidas.

•	O sistema deve impedir o acesso a usuários não autenticados.

-----

Resultados Esperados:

•	Passo 6: O usuário é redirecionado para a página inicial.

-----

Nome do Caso de Teste: Validação de Login

Descrição: Este caso de teste verifica a funcionalidade do sistema da página Comunidade. O objetivo é garantir que o sistema permita que um usuário faça login com credenciais válidas e bloqueie o acesso quando são fornecidas credenciais inválidas.

-----

Pré-condições:

•	O ambiente de teste deve estar configurado e acessível.

•	O navegador deve estar instalado e funcionando corretamente.

-----

Passos para a execução do teste:
1.	Insira um e-mail válido no campo "E-mail".
2.	Insira uma senha válida no campo “Password”.
3.	Clique no botão "Entrar".
4.	Verifique se o usuário é redirecionado para a página inicial.
5.	Efetue o logout do usuário.
6.	Repita os passos de 1 a 3, mas insira e-mail incorreto e senha correta e depois e-mail correto e senha incorreta.
7.	Clique no botão "Entrar".
8.	Verifique se uma mensagem de erro é exibida, indicando falha na autenticação.

 -----
 
Critérios de Aceitação:

•	O usuário deve ser redirecionado para a página inicial após fazer login com credenciais válidas.

•	Uma mensagem de erro deve ser exibida quando o usuário tentar fazer login com credenciais inválidas.

•	O sistema deve impedir o acesso a usuários não autenticados.

-----

Resultados Esperados:

•	Passo 5: O usuário é redirecionado para a página inicial.

•	Passo 9: Uma mensagem de erro "Credenciais inválidas" é exibida.

-----

Notas Adicionais:

•	Verificar se a interface está conforme o design especificado.

•	Testar diferentes navegadores (Google Chrome, Mozilla Firefox) para garantir compatibilidade cross-browser.

•	Documentar qualquer comportamento inesperado encontrado durante os testes.

•	Tirar capturas de tela dos resultados esperados e reais para referência.

-----

Ambiente de Teste:

•	Sistema Operacional: Windows 10.

•	Navegadores: Google Chrome - Versão 125.0.6422.176 (x64 bits), Mozila Firefox - Versão 127.0.1 (x64 bits), Microsoft Edge - Versão 126.0.2592.81 (x64 bits).

•	Versão da Aplicação: 1.0.0

-----

Histórico de Alterações:

•	Data: 01/07/2024

    o	Descrição: Caso de teste inicial criado.
    
    o	Autor: Thierry Castro
    
•	Data: 04/07/2024

    o	Descrição: Adicionadas notas sobre compatibilidade cross-browser.
    
    o	Autor: Thierry Castro

-----

Anexos:

•	Evidence_Report_Pagina_Comunidade_PT.pdf

•	Bug_Report_Pagina_Comunidade_PT.pdf


# Neste arquivo vão está listados 10 caso de teste manual usando site The internet 

ID: CT-LOGIN-001
Título: Realizar login com usuário e senha válidos

Pré-condições:
Usuário já cadastrado no sistema
Usuário não está logado
Navegador Google Chrome aberto

Passos:

1. Acessar a página de login do sistema

2. Informar um e-mail válido no campo “E-mail”

3. Informar uma senha válida no campo “Senha”

4. Clicar no botão “Entrar”

Resultado Esperado:

O sistema deve autenticar o usuário
O usuário deve ser redirecionado para a página inicial
O nome do usuário deve ser exibido no topo da página



ID: CT-LOGIN-002
Titulo: Realizar login com senha inválida 

Pré-condições: 
Usuário já cadastrado no sistema 
Usuário não está logado
Usuário digitou senha inválida
Navegador Google Chrome aberto

Passos: 

1. Acessar página de login do sistema 

2. Digitar um email no campo "E-mail"

3. Digitar uma senha no campo "Senha" 

4. Clicar no botão de login 

Resultado esperado: 
O sistema deve exibir mensagem informando o erro no topo da página
O usuário deve ser redirecionado para página de login novamente 



ID: CT-LOGIN-003
Titulo: Realizar login com e-mail inválida 

Pré-condições: 
Usuário já cadastrado no sistema 
Usuário não está logado
Usuário digitou e-mail inválida
Navegador Google Chrome aberto

Passos: 

1. Acessar página de login do sistema 

2. Digitar um email no campo "E-mail"

3. Digitar uma senha no campo "Senha" 

4. Clicar no botão de login 

Resultado esperado: 
O sistema deve exibir mensagem informando o erro no topo da página
O usuário deve ser redirecionado para página de login novamente 




ID: CT-LOGIN-004 
Titulo: Login com campos vázios 

Pré-condições: 
Usuário precisa está cadastrado no sistema 
Usuário não está logado
Usuário não digitou nenhum caractere nos campos de login 
Navegador Google Chrome aberto

Passos: 
1. Acessar página de login do sistema

2. Não digitar nenhum carectere no campo "Email"

3. Não digitar nenhum carectere no campo "Senha"

4. Clicar no botão de login 

Resultados esperados: 
Usuário recebe mensagem de erro no canto superior da tela
Usuário não tem acesso a homepage
Será solicitado que o usuário faça login novamente
Navegador Google Chrome aberto


ID: CT-LOGIN-005
Titulo: Login com senha em braco 

Pré-condições: 
Usuário precisa está cadastrado no sistema 
Usuário não está logado
Usuário não digitou nenhum caractere nos campo de senha
Navegador Google Chrome aberto

Passos: 
1. Acessar página de login do sistema

2. digitar um e-mail no campo "Email"

3. Não digitar nenhum carectere no campo "Senha"

4. Clicar no botão de login 

Resultados esperados: 
Usuário recebe mensagem de erro no canto superior da tela
Usuário não tem acesso a homepage
Será solicitado que o usuário faça login novamente


 

ID: CT-LOGIN-006
Titulo: Login com E-mail em braco 

Pré-condições: 
Usuário precisa está cadastrado no sistema 
Usuário não está logado
Usuário não digitou nenhum caractere nos campo de E-mail
Navegador Google Chrome aberto

Passos: 
1. Acessar página de login do sistema

2. Não digitar nenhum caractere no campo "Email"

3. Digitar uma senha no campo "Senha"

4. Clicar no botão de login 

Resultados esperados: 
Usuário recebe mensagem de erro no canto superior da tela
Usuário não tem acesso a homepage
Será solicitado que o usuário faça login novamente




ID: CT-LOGIN-007
Titulo: Login com caracteres especiais no campo E-mail

Pré-Condições:
Usuário já cadastrado no sistema
Usuário não está logado no sistema 
Usuário digitou carecteres especiais no campo E-mail
Navegador Google Chrome aberto

Passos: 
1. Acessar página de login do sistema

2. Digitar caractere especial no campo "Email"

3. Digitar uma senha no campo "Senha"

4. Clicar no botão de login 

Resultado esperado: 
O sistema devara informar por meio de um indicador que só aceita determinado grupo de caracteres 
O login não será feito no sistema
Usuário será solicitado para digitar o login novamente 



ID: CT-LOGIN-008
Titulo: Login com caracteres especiais no campo senha

Pré-Condições:
Usuário já cadastrado no sistema
Usuário não está logado no sistema 
Usuário digitou carecteres especiais no campo senha
Navegador Google Chrome aberto

Passos: 
1. Acessar página de login do sistema

2. Digitar E-mail no campo "Email"

3. Digitar caracter especial no campo "Senha"

4. Clicar no botão de login 

Resultado esperado: 
O sistema devara informar por meio de um indicador que só aceita determinado grupo de caracteres 
O login não será feito no sistema
Usuário será solicitado para digitar o login novamente 



ID: CT-LOGIN-009
Titulo: Login com caracteres especiais em ambos campos

Pré-Condições:
Usuário já cadastrado no sistema
Usuário não está logado no sistema 
Usuário digitou carecteres especiais no campo email
Usuário digitou carecteres especiais no campo senha
Navegador Google Chrome aberto

Passos: 
1. Acessar página de login do sistema

2. Digitar caracter especial no campo "Email"

3. Digitar caracter especial no campo "Senha"

4. Clicar no botão de login 

Resultado esperado: 
O sistema devara informar por meio de um indicador que só aceita determinado grupo de caracteres nos campos referentes
O login não será feito no sistema
Usuário será solicitado para digitar o login novamente 


ID:CT-LOGIN-010
Titulo: Tentativa falha de login 

Pré-Condições: 
Usuário não esta cadrastado no sistema 
Ter acessado pagina de login 
Navegador chrome aberto

Passos: 
1. Acessar página de login do sistema

2. Digitar email no campo "Email"

3. Digitar senha no campo "Senha"

4. Clicar no botão de login 

Resultados esperados: 
O login será negado 
Ira aparecer um indicador na parte superior da tela indicando o motivo da falha 
Usuário será sugerido que crie sua conta no sistema 


------CASOS NEGATIVOS------

ID: CTN-LOGIN-001
titulo: Falha na requisição ao back-end

Pré-Condições: 
Usuário pode esta cadatrado na plataforma ou não 
Usuário deve digitar seus dados de login quando solicitado
Acessar pagina de login 
Navegadir Google Chrome aberto

Passos: 
1. Acessar página de acesso a plataforma 
2. Usuário deve digitar seus dados de cadastro como "Email" e "senha" em seus respectivos campos
3. clicar no botão de "Login"

Resultados esperados: 
O botão de "Login" ao ser pressioando e verificado que ouve um erro de comunicação com o backend, irá dispara um popup na tela indicando instabilidades na plataforma 
A página de login sera recarregada manualmente, solcitando reinicio no processo de cadastro


ID: CTN-LOGIN-002
Titulo: Usuário cadatrado tem email ou senha incorretos

Pré-condições: 
Acesso a página de login
Usuário já deve ter conta criada na plataforma
Usuário adicionou dados de login incorretos
Google chrome navegador aberto 

Passos: 
1. Acessar página de login da plataforma 
2. Digitar e inserir dados de login na plataforma
3. Clicar no botão de login 

Resultado esperados: 
Será indicado ao usuário que os seus dados de acesso não estão corretos por meio de um popup
logo após vamos sugerir que ele faça alteração da sua senha e nova tentativar de login será iniciada




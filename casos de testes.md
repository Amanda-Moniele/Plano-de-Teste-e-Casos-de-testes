# Casos de testes

## ID: CT-001

Título: Login com credenciais válidas

Prioridade: Alta

Passos:
1 - Acessar a tela de login.
2- Informar username válido.
3 - Informar senha válida.
4 - Clicar no botão Entrar.

Resultado esperado:
O usuário deve ser autenticado e redirecionado para a página inicial.

Resultado obtido: O usuário é autenticado e redirecionado para a página inicial

## ID: CT-002

Título: Login com senha incorreta

Prioridade: Alta

Passos:
1 - Acessar a tela de login.
2 - Informar um username válido.
3 - Informar uma senha incorreta.
4 - Clicar em Entrar.

Resultado esperado:
O sistema deve exibir a mensagem "Usuário ou senha inválidos" e impedir o login.

Resultado obtido: o sistema retorna uma mensagem de erro "username e password required"

## ID: CT-003

Título: Login com campos vazios

Prioridade: Média

Passos:
1 - Abrir a tela de login.
2 - Não preencher nenhum campo.
3 - Clicar em Entrar.

Resultado esperado:
O sistema deve informar que os campos são obrigatórios.

Resultado obtido: O ssitema retorna uma mensagem de erro "email e password required"

## ID: CT-004

Título: Validar funcionalidade do botão de excluir

Passos:

1 - Criar uma tarefa ou escolher uma tarefa já existente.
2 - Clicar no botão de excluir.

Resultado esperado:
O sistema deve excluir a tarefa selecionada

Resultado obtido: a tarefa foi excluída

## ID: CT-005

Título: Campo "todo" gerando erro 400 ao tentar salvar uma nova tarefa

Prioridade: Alta

Passos: 
1 - Clicar no campo "todo" para adicionar tarefa
2 - Digitar uma tarefa
3 - Clicar em salvar

Resultado esperado: salvar o texto que foi digitado ou uma mensagem avisando  para o usuário que ocorreu um erro

Resultado obtido: ao clicar em salvar o sistema retorna um erro 400 somente, sem detalhes do erro

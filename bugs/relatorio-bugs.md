# Registro de Bugs

## Bug 002

Título:
Sistema permite cadastro de curso com campo obrigatório vazio

Passos para reproduzir:

1 Acessar tela de cadastro
2 Deixar campo "Nome do curso" vazio
3 Clicar em salvar

Resultado atual:

Sistema salva curso sem nome.

Resultado esperado:

Sistema deveria impedir cadastro.

Severidade:

Alta




## Bug 003

Título do Bug:

Sistema permite cadastrar curso duplicado.

Passos para Reproduzir

1 Acessar a tela de Cadastro de Cursos.

2 Cadastrar um curso com o nome "Inglês Básico" e salvar.

3 Retornar à tela de cadastro.

4 Tentar cadastrar novamente um curso com o nome "Inglês Básico".

5 Clicar no botão Salvar.


Resultado Atual:

O sistema permite salvar o cadastro mesmo quando já existe um curso com o mesmo nome, criando um registro duplicado.


Resultado Esperado:

O sistema deve validar se já existe um curso com o mesmo nome antes de salvar.

Caso exista, o sistema deve:

* Bloquear o cadastro duplicado, ou
* Exibir uma mensagem de alerta ao usuário, informando que o curso já está cadastrado.


Severidade:
Média


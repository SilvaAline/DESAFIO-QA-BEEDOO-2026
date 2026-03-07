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


## Bug 004

Título do Bug:
Sistema permite cadastrar nome de curso com excesso de caracteres.

Passos para Reproduzir

1 Acessar a tela de cadastro de cursos.

2 Inserir um nome de curso com mais de 255 caracteres.

3 Clicar em Salvar.

Resultado Atual:
O sistema aceita e salva o nome do curso com excesso de caracteres.

Resultado Esperado:
O sistema deve limitar o campo a 255 caracteres ou impedir o cadastro exibindo uma mensagem de validação.

Severidade
Média

https://docs.google.com/spreadsheets/d/1qrIuY_N_eLovk1iHIOJpGtp2wPPI6oaP3MBoKMNdaKo/edit?usp=sharing

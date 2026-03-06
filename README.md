# DESAFIO-QA-BEEDOO-2026

Este repositório contém a análise, cenários de teste, execução de testes e registro de bugs do módulo de cadastro e listagem de cursos da aplicação:

https://creative-sherbet-a51eac.netlify.app/

---

# 1. Objetivo da Aplicação

A aplicação parece ser um sistema de gerenciamento de cursos, permitindo que usuários realizem o cadastro e visualização de cursos disponíveis.

Esse tipo de sistema é comum em plataformas LMS (Learning Management System), utilizadas para organização de conteúdos educacionais e treinamentos corporativos. Plataformas como a :contentReference[oaicite:0]{index=0} utilizam esse tipo de funcionalidade para estruturar trilhas de aprendizagem e gestão de conteúdos educacionais. :contentReference[oaicite:1]{index=1}

---

# 2. Principais Fluxos da Aplicação

Os fluxos principais identificados na aplicação são:

### Cadastro de cursos
Permite que o usuário registre um novo curso no sistema.

Possíveis campos:

- Nome do curso
- Descrição
- Categoria
- Carga horária
- Instrutor

Fluxo:

1. Acessar página de cadastro
2. Preencher campos obrigatórios
3. Salvar curso
4. Validar sucesso da operação

---

### Listagem de cursos

Permite visualizar os cursos cadastrados.

Possíveis comportamentos:

- Exibir lista de cursos
- Atualizar lista após cadastro
- Exibir informações resumidas do curso

---

# 3. Pontos Críticos para Teste

Os pontos mais críticos identificados são:

### Cadastro de cursos
- Validação de campos obrigatórios
- Prevenção de cadastro duplicado
- Limite de caracteres
- Tratamento de dados inválidos

### Listagem de cursos
- Atualização da lista após cadastro
- Integridade das informações exibidas
- Performance da listagem

### Persistência de dados
- Verificar se cursos cadastrados permanecem após atualização da página

### Tratamento de erros
- Mensagens claras ao usuário
- Prevenção de falhas silenciosas

---

# 4. Casos de Teste

Os casos de teste estão documentados na planilha abaixo:

LINK DA PLANILHA GOOGLE SHEETS

---

# 5. Execução dos Testes

Os testes foram executados manualmente conforme os cenários definidos.

Evidências disponíveis em:

LINK DA PASTA GOOGLE DRIVE

---

# 6. Registro de Bugs

Os bugs encontrados estão documentados no arquivo:

bugs/relatorio-bugs.md



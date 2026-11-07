# Projeto 01 – Testes Manuais de Login

## 1. Objetivo

Verificar se a funcionalidade de login permite o acesso do usuário com dados válidos e impede o acesso quando os dados estão incorretos ou não foram preenchidos.

## 2. Cenários de teste

### CT001 – Login com dados válidos
- **Pré-condição:** Usuário cadastrado no sistema.
- **Dados de entrada:** E-mail e senha corretos.
- **Passos:**
  1. Acessar a tela de login.
  2. Informar o e-mail cadastrado.
  3. Informar a senha correta.
  4. Clicar em Entrar.
- **Resultado esperado:** O sistema deve permitir o acesso à conta.

### CT002 – Login com senha incorreta
- **Pré-condição:** Usuário cadastrado no sistema.
- **Dados de entrada:** E-mail correto e senha incorreta.
- **Passos:**
  1. Acessar a tela de login.
  2. Informar o e-mail cadastrado.
  3. Informar uma senha incorreta.
  4. Clicar em Entrar.
- **Resultado esperado:** O sistema deve impedir o acesso e apresentar uma mensagem de erro.

### CT003 – Login sem preencher o e-mail
- **Dados de entrada:** Campo de e-mail vazio e senha preenchida.
- **Passos:**
  1. Acessar a tela de login.
  2. Deixar o campo de e-mail vazio.
  3. Preencher a senha.
  4. Clicar em Entrar.
- **Resultado esperado:** O sistema deve solicitar o preenchimento do e-mail.

### CT004 – Login sem preencher a senha
- **Dados de entrada:** E-mail preenchido e campo de senha vazio.
- **Passos:**
  1. Acessar a tela de login.
  2. Informar o e-mail.
  3. Deixar a senha vazia.
  4. Clicar em Entrar.
- **Resultado esperado:** O sistema deve solicitar o preenchimento da senha.

## 3. Resultados dos testes

Os testes ainda não foram executados em um sistema real. Os resultados serão registrados após a execução prática.

## 4. Conclusão

Os cenários foram elaborados para verificar o comportamento básico da funcionalidade de login, considerando situações válidas e inválidas.

# testes-suitecrm

## 1. Teste Login:

### Descrição: Realizar login com usuario valido;

### Objetivo:Verificar se o sistema permite o login com credenciais válidas;

### O que será testado: Será testado o login de usuario de forma validade;

### Pré requisitos:
* Usuario existente no sistema do SuiteCRM
* Sistema especificação:Windows 10
* Entrar com o usuario: "admin" e senha:"admin123"
* clicar no botão de login
  
### Procedimento para execução do teste: Preenchimento da espaço de login e senha com as credencias de "admin" para login e "admin123" para senha;

### Resultado esperado: Acesso com sucesso ao site;

### Resultado real: Login realizado com sucesso;

### Analise do resultado: Perfeito, login sem problema;

### Evidencias:

![Captura de tela 2025-04-15 203032](https://github.com/user-attachments/assets/3188dcf8-5cf1-4676-809e-64bac6b19ce0)

![Captura de tela 2025-04-15 203059](https://github.com/user-attachments/assets/44559b79-11e5-4ec3-b807-284f8e229302)

## 2. Teste Login Invalido:

### Descrição: Tentar realizar login com usuario invaldio;

### Objetivo: Avaliar a resposta do sistema quando são inseridas credenciais inválidas, confirmando a exibição de mensagens de erro apropriadas;

### O que será testado: Será testado o login de usuario de forma invalida;

### Pré requisitos:
* Usuario existente no sistema do SuiteCRM
* Sistema especificação:Windows 10
* Entrar com o usuario: "admininvalido" e senha:"admin345"
* clicar no botão de login
  
### Procedimento para execução do teste: Preenchimento da espaço de login e senha com as credencias de "admininvalido" para login e "admin345" para senha;

### Resultado esperado: Não acessar o site;

### Resultado real: Site não acessado;

### Analise do resultado:Teste realizado com sucesso, no qual não foi possivel acessar o site;

### Evidencias:
![Captura de tela 2025-04-19 184732](https://github.com/user-attachments/assets/0d1e68da-806f-43cf-9275-e054e7ede751)

![Captura de tela 2025-04-19 184717](https://github.com/user-attachments/assets/9c6c42ee-b4f2-4664-a20a-7e33f25d376b)


## 3. Criação de novo contato:

### Descrição: Realizar a criação de um novo contato no site com as credenciais;

### Objetivo: Garantir que o módulo de contatos permita a criação de um novo registro com todas as informações necessárias.

### O que será testado: A  criação de um contato no site;

### Pré requisitos:
* Usuario existente no sistema do SuiteCRM
* Sistema especificação:Windows 10
* Entrar com o usuario: "admin" e senha:"admin123"
* clicar no botão de login
* Localizr na barra de tarefas a função Account
* Clicar no botão Create Account
  
### Procedimento para execução do teste: Preenchimento das credencias necessarias para a criação de contato;

### Resultado esperado: Criação de um contato de forma simples;

### Resultado real: Contato criado com sucesso;

### Analise do resultado:Teste realizado com sucesso, no qual não foi apresentado erros;

### Evidencias:
![Captura de tela 2025-04-19 185633](https://github.com/user-attachments/assets/55958e5f-6ced-44fb-a7c3-c3b07acb892b)

![Captura de tela 2025-04-19 190441](https://github.com/user-attachments/assets/cad47d82-7315-4abd-8544-cd977d7652a7)

![Captura de tela 2025-04-19 190502](https://github.com/user-attachments/assets/5a461efc-6312-4491-b717-6075db3da3ee)

## 4. Edição de contato existente:

### Descrição: Realizar a edição de credenciais de um contato existentes;

### Objetivo: Testar a funcionalidade de edição de registros, verificando se as alterações são salvas e refletidas corretamente;

### O que será testado: Editar o contato;

### Pré requisitos:
* Usuario existente no sistema do SuiteCRM
* Sistema especificação:Windows 10
* Entrar com o usuario: "admin" e senha:"admin123"
* Clicar no botão de login
* Localizr na barra de tarefas a função Account
* Clicar no botão View Contact
* Selecionar o contato desejado para a edição
* Clicar no Botão de Edit
  
### Procedimento para execução do teste: Preenchimento das novas credencias para a edição do contato existente;

### Resultado esperado: Edição de um contato de forma simples;

### Resultado real: Edição de contato com sucesso;

### Analise do resultado:Teste realizado com sucesso, no qual não foi apresentado erros;

### Evidencias:
![Captura de tela 2025-04-20 200352](https://github.com/user-attachments/assets/9f1778be-cd57-4c96-9d90-f4d76b000a6c)
![Captura de tela 2025-04-20 200422](https://github.com/user-attachments/assets/7ee43d8f-cf72-4e52-921d-d87a6daf71f9)
![Captura de tela 2025-04-20 200523](https://github.com/user-attachments/assets/72aa08e8-db57-441c-8db0-1f651bb11af8)
![Captura de tela 2025-04-20 200440](https://github.com/user-attachments/assets/42101282-201e-476a-97e6-6d5541d6b8cd)
![Captura de tela 2025-04-20 200553](https://github.com/user-attachments/assets/da6cf301-ff82-4b2e-bf66-e0e92d5d7658)

## 5. Exclusão de contato existente:

### Descrição: Realizar a exclusão de um contato existentes;

### Objetivo: Confirmar que a exclusão de um contato remove o registro de forma eficaz do sistema;

### O que será testado: Exclusão de um contato;

### Pré requisitos:
* Usuario existente no sistema do SuiteCRM
* Sistema especificação:Windows 10
* Entrar com o usuario: "admin" e senha:"admin123"
* Clicar no botão de login
* Localizr na barra de tarefas a função Account
* Clicar no botão View Contact
* Selecionar o contato desejado para a exclusão
* Clicar no Botão de Actions
* Clicar no botão delete
  
### Procedimento para execução do teste: Exclusão de um contato existente;

### Resultado esperado: Exclusão  de um contato de forma simples;

### Resultado real: Exclusão de contato com sucesso;

### Analise do resultado:Teste realizado com sucesso, no qual não foi apresentado erros;

![Captura de tela 2025-04-20 200422](https://github.com/user-attachments/assets/8e215665-58f6-438d-a0de-72117a576891)
![Captura de tela 2025-04-20 200352](https://github.com/user-attachments/assets/050bf21d-a27f-48b7-8d94-860980b77132)
![Captura de tela 2025-04-20 200440](https://github.com/user-attachments/assets/f5560177-8121-46ff-b2b7-3a8657b312d1)
![Captura de tela 2025-04-20 200553](https://github.com/user-attachments/assets/ee6ea620-39c7-4f92-9281-ed60bc4685cd)
![Captura de tela 2025-04-20 203240](https://github.com/user-attachments/assets/ebeb9607-dcab-4dce-a07f-f3cc51969068)



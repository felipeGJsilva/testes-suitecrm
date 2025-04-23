### RELATÓRIOS DE TESTE – SuiteCRM

---

#### **1. Teste de Login com Credenciais Válidas**

**Descrição:**
Verificação do processo de autenticação de usuário com credenciais válidas.

**Objetivo:**
Confirmar que o sistema permite o acesso quando credenciais corretas são fornecidas.

**O que será testado:**
Funcionalidade de login.

**Pré-requisitos:**
- Acesso à instância SuiteCRM;
- Usuário: admin;
- Senha: admin123;
- Navegador Google Chrome em ambiente Windows 10;
- Conexão com a internet.

**Procedimento para Execução do Teste:**
1. Acessar a tela de login do sistema;
2. Informar usuário "admin" e senha "admin123";
3. Clicar no botão "Login".

**Resultado Esperado:**
Usuário autenticado com sucesso e redirecionado para a tela principal do sistema.

**Resultado Real:**
Acesso realizado com sucesso.

**Análise do Resultado:**
Teste aprovado. O login foi efetuado corretamente.

**Evidências:**
[Imagem 1](https://github.com/user-attachments/assets/3188dcf8-5cf1-4676-809e-64bac6b19ce0)
[Imagem 2](https://github.com/user-attachments/assets/44559b79-11e5-4ec3-b807-284f8e229302)

---

#### **2. Teste de Login com Credenciais Inválidas**

**Descrição:**
Verificação do comportamento do sistema ao inserir credenciais inválidas.

**Objetivo:**
Avaliar se o sistema impede o login e apresenta mensagem de erro adequada.

**O que será testado:**
Validação de login com dados incorretos.

**Pré-requisitos:**
- Acesso à instância SuiteCRM;
- Usuário: admininvalido;
- Senha: admin345;
- Navegador Google Chrome em ambiente Windows 10;

**Procedimento para Execução do Teste:**
1. Acessar a tela de login do sistema;
2. Informar usuário "admininvalido" e senha "admin345";
3. Clicar no botão "Login".

**Resultado Esperado:**
Sistema não permite acesso e apresenta mensagem de erro.

**Resultado Real:**
Acesso negado, conforme esperado.

**Análise do Resultado:**
Teste aprovado. O sistema se comportou corretamente diante de dados inválidos.

**Evidências:**
[Imagem 1](https://github.com/user-attachments/assets/0d1e68da-806f-43cf-9275-e054e7ede751)
[Imagem 2](https://github.com/user-attachments/assets/9c6c42ee-b4f2-4664-a20a-7e33f25d376b)

---

#### **3. Teste de Criação de Contato**

**Descrição:**
Verificar se é possível adicionar um novo contato no módulo "Accounts".

**Objetivo:**
Garantir o funcionamento correto da funcionalidade de criação de contato.

**O que será testado:**
Criação de um novo registro de contato.

**Pré-requisitos:**
- Acesso com usuário "admin";
- Sistema operacional Windows 10;
- Navegador compatível;

**Procedimento para Execução do Teste:**
1. Acessar o sistema com credenciais válidas;
2. Navegar até o menu "Accounts";
3. Clicar em "Create Account";
4. Preencher os campos obrigatórios e salvar.

**Resultado Esperado:**
Contato adicionado com sucesso e visível na lista de contatos.

**Resultado Real:**
Contato criado corretamente.

**Análise do Resultado:**
Teste aprovado. Processo de criação executado sem falhas.

**Evidências:**
[Imagem 1](https://github.com/user-attachments/assets/55958e5f-6ced-44fb-a7c3-c3b07acb892b)
[Imagem 2](https://github.com/user-attachments/assets/cad47d82-7315-4abd-8544-cd977d7652a7)
[Imagem 3](https://github.com/user-attachments/assets/5a461efc-6312-4491-b717-6075db3da3ee)

---

#### **4. Teste de Edição de Contato**

**Descrição:**
Verificar a edição de um contato previamente criado.

**Objetivo:**
Testar se as alterações nos registros são salvas corretamente.

**O que será testado:**
Funcionalidade de edição de contato.

**Pré-requisitos:**
- Acesso com usuário "admin";
- Contato previamente criado;
- Navegador em ambiente Windows 10;

**Procedimento para Execução do Teste:**
1. Acessar o módulo "Accounts";
2. Clicar em "View Contact";
3. Selecionar o contato desejado;
4. Clicar em "Edit", realizar alterações e salvar.

**Resultado Esperado:**
Contato atualizado com as novas informações.

**Resultado Real:**
Alterações salvas com sucesso.

**Análise do Resultado:**
Teste aprovado. Sistema refletiu corretamente as modificações.

**Evidências:**
[Imagem 1](https://github.com/user-attachments/assets/9f1778be-cd57-4c96-9d90-f4d76b000a6c)
[Imagem 2](https://github.com/user-attachments/assets/7ee43d8f-cf72-4e52-921d-d87a6daf71f9)
[Imagem 3](https://github.com/user-attachments/assets/72aa08e8-db57-441c-8db0-1f651bb11af8)
[Imagem 4](https://github.com/user-attachments/assets/42101282-201e-476a-97e6-6d5541d6b8cd)
[Imagem 5](https://github.com/user-attachments/assets/da6cf301-ff82-4b2e-bf66-e0e92d5d7658)

---

#### **5. Teste de Exclusão de Contato**

**Descrição:**
Testar a funcionalidade de exclusão de contatos.

**Objetivo:**
Confirmar que contatos podem ser removidos do sistema sem erros.

**O que será testado:**
Exclusão de registros do módulo "Contacts".

**Pré-requisitos:**
- Contato previamente criado;
- Acesso como "admin";

**Procedimento para Execução do Teste:**
1. Acessar "Accounts" > "View Contact";
2. Selecionar contato desejado;
3. Clicar em "Actions" > "Delete".

**Resultado Esperado:**
Contato removido com sucesso da base.

**Resultado Real:**
Registro deletado com êxito.

**Análise do Resultado:**
Teste aprovado. O contato foi excluído do sistema corretamente.

**Evidências:**
[Imagem 1](https://github.com/user-attachments/assets/8e215665-58f6-438d-a0de-72117a576891)
[Imagem 2](https://github.com/user-attachments/assets/050bf21d-a27f-48b7-8d94-860980b77132)
[Imagem 3](https://github.com/user-attachments/assets/f5560177-8121-46ff-b2b7-3a8657b312d1)
[Imagem 4](https://github.com/user-attachments/assets/ee6ea620-39c7-4f92-9281-ed60bc4685cd)
[Imagem 5](https://github.com/user-attachments/assets/ebeb9607-dcab-4dce-a07f-f3cc51969068)

---

#### **6. Teste de Pesquisa de Registros**

**Descrição:**
Testar o mecanismo de busca de contatos existentes utilizando critérios como nome e e-mail.

**Objetivo:**
Validar a precisão e funcionalidade da busca.

**O que será testado:**
Barra de busca do módulo "Contacts".

**Pré-requisitos:**
- Acesso com usuário válido;
- Contatos previamente cadastrados.

**Procedimento para Execução do Teste:**
1. Realizar login;
2. Acessar módulo "Contacts";
3. Inserir critérios de busca (nome, e-mail) e acionar pesquisa.

**Resultado Esperado:**
Retorno preciso dos registros correspondentes aos critérios informados.

**Resultado Real:**
Sistema retornou corretamente os resultados esperados.

**Análise do Resultado:**
Teste bem-sucedido. A busca está funcionando corretamente.

**Evidências:**
[Imagem 1](https://github.com/user-attachments/assets/eb05ca29-4870-4200-bf19-2de9e5de340f)
[Imagem 2](https://github.com/user-attachments/assets/a067840a-97b7-4caa-ac3c-5734e305e247)

---

#### **7. Teste de Importação de Dados**

**Descrição:**
Validar o processo de importação de contatos via arquivo CSV.

**Objetivo:**
Confirmar a correta leitura e cadastro dos dados contidos no arquivo importado.

**O que será testado:**
Funcionalidade de importação do módulo "Contacts".

**Pré-requisitos:**
- Arquivo CSV formatado corretamente;
- Acesso como "admin";

**Procedimento para Execução do Teste:**
1. Acessar "Contacts";
2. Clicar em "Import Contacts";
3. Fazer upload do arquivo CSV;
4. Confirmar importação.

**Resultado Esperado:**
Contatos inseridos corretamente no sistema.

**Resultado Real:**
Importação executada com sucesso.

**Análise do Resultado:**
Teste aprovado. Dados foram importados sem erros.

**Evidências:**
[Imagem 1](https://github.com/user-attachments/assets/2c8de863-85b5-43f7-8005-22c82d842014)
[Imagem 2](https://github.com/user-attachments/assets/2dabdbca-2019-49ed-9205-6f69c83559c2)

---



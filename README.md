<<<<<<< HEAD
## 🛠 Atividade de DevOps com *GitHub Actions*
* Realizar o fork da aplicação
* Criar um nova branch *(Opcional)*
* Realizar o clone da aplicação na sua máquina
* Tirar os comentários do método de teste **DELETE**
* Criar o banco de dados:
  ```
  create database funcionarioDB;
  
  use funcionarioDB;
  
  create table funcionario (
  	cod int primary key auto_increment,
      nome varchar(100),
      salario decimal(15,2)
  );
  ```  
* Configure o git, se caso haja a necessidade:  
  `git config --global user.name "Seu nome de usuário"`  
  `git config --global user.email "Seu email"`
  Realize o login quando der o push
* Realizar um commit e subir para o repositório  
  `git add .`
  `git commit -m "Nome do commit"`
  `git push`
* Verificar o *workflow*
* Corrigir o método **DELETE**, tirar o comentário e remover a última linha
  - Utilizar o comando `npx tsc` para converter o código *Typescript* em *Javascript*
* Fazer o commit e verificar novamente o *workflow*
* Realizar um novo commit e verificar novamente o *workflow*
* Fazer os testes para **PUT (Atualizar)** e **GET (Encontrar código)**  
=======
# 🧩 Projeto Funcionários

Este repositório faz parte do sistema **Projeto Funcionários**, desenvolvido em **Node.js**.  
O objetivo deste documento é descrever, de forma clara e organizada, os **passos necessários** para configurar o workflow de integração contínua (CI) do backend e desenvolver os testes automatizados para as principais rotas da aplicação.

---

## 🍴 Fazer o Fork do Repositório

Antes de iniciar qualquer modificação, é necessário criar uma cópia (fork) do repositório original na sua conta do GitHub.

### Passos

1. Acesse o repositório original:  
   👉 [https://github.com/Jean-silvaDev/Projeto-Funcionarios](https://github.com/Jean-silvaDev/Projeto-Funcionarios)

2. No canto superior direito da página, clique em **Fork**.

3. Escolha sua conta e confirme a criação do fork.

4. Clone o repositório forkado para sua máquina:
   ```bash
   git clone https://github.com/<seu-usuario>/Projeto-Funcionarios.git

## 🛠 Próximos passos:

5. Acessar o projeto e criar o **backendWorkflow.yaml** em **.github/workflows/**.

6. Realizar um commit e testar se o workflow executou com sucesso.

7. Criar os testes **GET(Para buscar código existente)**, **PUT** e **DELETE** com base nos já criados no backend.

8. Realizar o commit e o push.

9. Verificar se os testes executaram com sucesso.
>>>>>>> 09e9b73 (Add README with project setup instructions)

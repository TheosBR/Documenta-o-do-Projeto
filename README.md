# ⚽ Gerador de Torneios de Futebol

Sistema web desenvolvido em **PHP** e **MySQL** para gerenciamento de torneios de futebol.

O projeto permite que usuários criem, editem, salvem e gerenciem campeonatos de forma simples e organizada, calculando automaticamente a classificação das equipes.

---

## 📖 Sobre o Projeto

O **Gerador de Torneios de Futebol** foi desenvolvido como projeto da disciplina de **Gestão de Projetos**, com o objetivo de aplicar conceitos de:

- Engenharia de Software
- Banco de Dados
- Desenvolvimento Web
- Testes de Software
- Programação em PHP

O sistema gera automaticamente a classificação dos times com base nas estatísticas informadas pelo usuário.

---

## 🚀 Funcionalidades

- ✅ Cadastro de usuários
- ✅ Login e Logout
- ✅ Autenticação por sessão
- ✅ Geração automática da classificação
- ✅ Cálculo de pontos
- ✅ Cálculo do saldo de gols
- ✅ Classificação por critérios de desempate
- ✅ Modo Pontos Corridos
- ✅ Modo Playoff
- ✅ Escolha da quantidade de classificados
- ✅ Salvar torneios
- ✅ Carregar torneios
- ✅ Editar torneios
- ✅ Excluir torneios
- ✅ Cada usuário visualiza apenas seus próprios torneios

---

## 🛠 Tecnologias Utilizadas

- PHP 8
- HTML5
- CSS3
- MySQL
- XAMPP
- Visual Studio Code

---

## 📁 Estrutura do Projeto

```
Projeto/

│── index.php
│── login.php
│── cadastro.php
│── logout.php
│── conexao.php
│── salvar_torneio.php
│── editar_torneio.php
│── atualizar_torneio.php
│── abrir_torneio.php
│── meus_torneios.php
│── deletar_torneio.php
│── dashboard.php
│── style.css
│── style_botoes.css
│── banco.sql
│── README.md
│── Documentação do Projeto.docx
```

---

## 🗄 Banco de Dados

O projeto utiliza **MySQL**.

Para configurar:

1. Abra o **phpMyAdmin**.
2. Crie um banco chamado:

```
campeonato
```

3. Importe o arquivo:

```
banco.sql
```

---

## ▶ Como Executar

1. Instale o **XAMPP**.

2. Inicie:

- Apache
- MySQL

3. Copie o projeto para:

```
C:\xampp\htdocs\
```

4. Abra o navegador:

```
http://localhost/Projeto
```

---

## 📸 Telas do Sistema

### Página Inicial

- Geração da classificação
- Cadastro dos resultados
- Seleção do modo da competição

### Login

- Autenticação do usuário

### Cadastro

- Criação de novas contas

### Meus Torneios

- Visualização dos torneios salvos
- Carregar torneio
- Editar torneio
- Excluir torneio

---

## 📋 Requisitos Funcionais

- Cadastro de usuários
- Login
- Logout
- Criar torneio
- Gerar classificação
- Salvar torneio
- Editar torneio
- Carregar torneio
- Excluir torneio

---

## 🔒 Requisitos Não Funcionais

- Interface simples
- Autenticação por sessão
- Banco MySQL
- PHP 8
- Navegadores modernos
- Senhas criptografadas utilizando `password_hash()`

---

## 🧪 Casos de Teste

- Cadastro de usuário
- Login
- Geração da classificação
- Salvar torneio
- Editar torneio
- Excluir torneio
- Carregar torneio
- Validação de acesso
- Funcionamento do Playoff

---

## 📚 Documentação

A documentação completa está disponível no arquivo:

```
Documentação do Projeto.docx
```

Ela contém:

- Introdução
- Requisitos Funcionais
- Requisitos Não Funcionais
- Diagrama de Classes
- Diagrama de Caso de Uso
- Tecnologias utilizadas
- Cenários de Testes

---

## 👨‍💻 Autor

**Matheus Silva de Lima**

Curso: Técnico em Informática

Instituição: Grau Técnico

Disciplina: Gestão de Projetos 3

Professor: Cefras

---

## 🔮 Melhorias Futuras

- Cadastro de partidas
- Geração automática dos confrontos
- Estatísticas dos jogadores
- Ranking de artilheiros
- Escudos dos clubes
- Exportação em PDF
- Responsividade para dispositivos móveis
- Publicação em hospedagem web

---

## 📄 Licença

Este projeto foi desenvolvido para fins acadêmicos.

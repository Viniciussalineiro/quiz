# Projeto Quiz - Documentação Inicial

---

## Visão Geral do Projeto

O projeto "Quiz" é uma aplicação desenvolvida em Java 21 com o framework Spring Boot, com o propósito de fornecer uma plataforma interativa para aulas de alunos pela MJV. A aplicação permite a criação, gerenciamento e execução de questionários (quizzes) em ambientes educacionais.

---

## Requisitos do Sistema

1. **Java 21:** O projeto é baseado na versão 21 da linguagem Java.
2. **Spring Boot:** Utiliza o framework Spring Boot para simplificar o desenvolvimento e facilitar a configuração.
3. **Banco de Dados:** A aplicação requer um banco de dados para armazenar informações sobre usuários, perguntas e respostas.
4. **Frontend:** Será necessário um frontend para interação com os usuários, permitindo a criação e execução de quizzes.

---

## Componentes Principais

1. **Controle de Usuários:**
   - Registro e autenticação de usuários.
   - Atribuição de funções (aluno, professor, administrador).
   - Gerenciamento de perfis e senhas.

2. **Quizzes:**
   - Criação e edição de quizzes por professores/administradores.
   - Execução de quizzes por alunos.
   - Armazenamento de perguntas, respostas e estatísticas associadas.

3. **Banco de Dados:**
   - Integração com um banco de dados para persistência de dados.
   - Entidades: Usuário, Quiz, Pergunta, Resposta.
   - Relacionamentos entre entidades para garantir consistência.

4. **Frontend:**
   - Interface para criação e edição de quizzes.
   - Página de execução de quizzes para alunos.
   - Visualização de estatísticas e resultados.

---

## Tecnologias Utilizadas

- **Linguagem:** Java 21
- **Framework:** Spring Boot
- **Banco de Dados:** (Exemplo: MySQL, PostgreSQL, H2)
- **Frontend:** (Exemplo: React, Angular, Vue.js)
- **Controle de Versão:** Git

---

## Configuração do Ambiente de Desenvolvimento

1. **Clonar Repositório:**
   ```bash
   git clone https://github.com/seu-usuario/quiz.git

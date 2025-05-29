<h3 style="display: flex; justify-content: center;">
  <img alt="Digital One" src="https://www.digitalone.com.br/images/agencia-de-marketing-digital-one.png" />
</h3>

# Documentação para Tester — Sistema de Postagens com Laravel + Vuetify

---

A [Digital One](https://www.digitalone.com.br/) está sempre em busca de profissionais com boa capacidade de aprendizado e adaptação, mas principalmente motivação.

Este teste tem como objetivo avaliar seus conhecimentos. Fique tranquilo, caso não consiga concluir o desafio no prazo estipulado, você deve envia-lo da maneira que estiver, pois iremos avaliar a qualidade do que foi desenvolvido. 

## 1. Objetivo do Sistema

Construir uma aplicação com as seguintes funcionalidades:

- Registro de conta
- Login
- Recuperação de senha (validação do e-mail e alteração da senha)
- Usuário pode criar postagens
- Exibição pública de todas as postagens
- Usuário dono da postagem pode editar ou excluir sua postagem

### Tecnologias usadas

- Backend: Laravel
- Frontend: Vue.js + Vuetify
- Banco: phpMyAdmin/MySQL

---

## 2. Requisitos Funcionais

### Autenticação

- Usuário pode registrar conta com nome, e-mail e senha (validação básica)
- Usuário pode logar com e-mail e senha
- Usuário pode solicitar recuperação de senha — o sistema valida se o e-mail existe e permite alterar a senha
- Só é possível ver as publicações se estiver logado

### Postagens

- Usuário logado pode criar uma postagem com título e conteúdo
- Todos os usuários  podem ver todas as postagens
- Usuário pode editar ou excluir apenas as suas postagens
- Postagens devem exibir título, conteúdo, autor e data de criação

---

## 3. Testes Automatizados

O tester deve executar os testes automatizados já implementados, além de validar manualmente os principais fluxos. São eles:

### Backend (Laravel)

- Testar registro de usuário (cenários de sucesso e falha)
- Testar login (cenários de sucesso e falha)
- Testar recuperação de senha (validação do e-mail e alteração da senha)
- Testar criação, edição e exclusão de postagens, garantindo que somente o dono da postagem possa editar/excluir
- Testar a listagem pública de postagens

### Frontend (Vue + Vuetify)

- Executar testes unitários e E2E já criados (Jest, Cypress ou Playwright), cobrindo o fluxo principal:  
  Registro → Login → Criar postagem → Editar → Excluir → Logout
- Testar restrições para edição e exclusão de postagens de outros usuários
- Testar fluxo de recuperação de senha

---

## Regras

- Você também deve utilizar algum padrão de desenvolvimento (ex: MVC, MVVM, MVP, etc...).
- No layout, Você poderá utilizar algum framework CSS (ex: Bootstrap, MaterializeCSS, etc...).
- Faça commits pequenos para que possamos acompanhar a sua linha de raciocínio.
- Após o recebimento do e-mail com esse desafio, você terá 7 dias para desenvolve-lo.

## Por onde começar?

Primeiramente, você pode fazer um fork desse repositório aqui, para sua conta do Github, depois disso crie uma branch nova com o seu nome (ex: nome_sobrenome), para podermos indentificá-lo.

Após terminar o desafio, você pode solicitar um pull request para a branch master do nosso repositório. Vamos receber e fazer a avaliação de todos.
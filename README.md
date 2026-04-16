# 🛒 E-Commerce de Hardware em Kotlin

## 📌 Descrição do Projeto

Este projeto consiste no desenvolvimento de um sistema de **e-commerce de equipamentos de hardware**, implementado em **Kotlin**, com **interface gráfica baseada em XML**, como parte da disciplina de **Programação de Aplicativos**.

A aplicação simula o funcionamento de uma loja virtual completa, permitindo que usuários realizem login, naveguem por produtos, gerenciem um carrinho de compras e finalizem pedidos por meio de uma interface intuitiva.

O projeto integra conceitos de **desenvolvimento mobile (Android)** com **Programação Orientada a Objetos (POO)**.

> Autor(a): Emanuele Kmiecik  |  Linguagem: Kotlin

---

## 🎯 Objetivos

* Aplicar conceitos de **POO com Kotlin** em um contexto real
* Desenvolver interfaces gráficas utilizando **XML (Android)**
* Implementar a lógica de um sistema de e-commerce
* Integrar backend lógico com frontend visual

---

## 🧱 Estrutura do Projeto

O sistema é composto pelas seguintes classes principais:

### 📦 Produto

Responsável por representar os itens disponíveis no catálogo.

**Funcionalidades:**

* Armazenar nome, preço e quantidade em estoque
* Controle de disponibilidade
* Integração com o carrinho

---

### 👤 Cliente

Representa o usuário da aplicação.

**Funcionalidades:**

* Login no sistema
* Criação de pedidos
* Interação com o carrinho

---

### 🛒 Carrinho

Gerencia os produtos selecionados.

**Funcionalidades:**

* Adicionar e remover produtos
* Atualizar quantidades
* Calcular valor total da compra

---

### 📄 Pedido

Responsável pela finalização da compra.

**Funcionalidades:**

* Gerar resumo do pedido
* Selecionar método de pagamento
* Confirmar compra

---

### ⚙️ Sistema

Controla o fluxo da aplicação.

**Funcionalidades:**

* Navegação entre telas
* Controle de estados
* Gerenciamento das interações do usuário

---

## 🎨 Interface Gráfica (UI)

A interface foi desenvolvida utilizando **XML no Android**, garantindo separação entre lógica e apresentação.

**Principais telas:**

* 🔐 Tela de Login
* 🏠 Tela Inicial / Menu
* 🛍️ Catálogo de Produtos
* 🛒 Carrinho de Compras
* 💳 Finalização de Pedido

---

## 🔄 Fluxo de Funcionamento

1. Usuário acessa a **tela de login**
2. Após autenticação:

   * Visualiza o **menu principal**
3. Pode:

   * Navegar pelo catálogo
   * Adicionar produtos ao carrinho
4. No carrinho:

   * Ajusta quantidades
   * Visualiza total
5. Finaliza o pedido:

   * Escolhe método de pagamento
   * Visualiza resumo e confirmação

---

## 🛠️ Tecnologias Utilizadas

* **Kotlin**
* **Android Studio**
* **XML (Layouts Android)**
* Programação Orientada a Objetos (POO)

---

## 📚 Conceitos Aplicados

* Arquitetura básica de apps Android
* Separação entre **UI (XML)** e **lógica (Kotlin)**
* Manipulação de listas com `RecyclerView`
* Navegação entre telas
* Gerenciamento de estado da aplicação

---

## 🚀 Possíveis Melhorias Futuras

* Integração com banco de dados (SQLite / Firebase / MySQL)
* Implementação de API REST
* Sistema de autenticação com segurança avançada
* Persistência de carrinho
* Sistema de avaliações e comentários
* Interface mais moderna com **Material Design 3**


---

## 📄 Licença

Este projeto possui finalidade acadêmica e pode ser utilizado como base para estudos e evolução de aplicações mobile.

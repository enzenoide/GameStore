

# 🎮 Game Store – Aplicação Python com MVC

Este projeto é uma **loja de jogos eletrônicos** desenvolvida inteiramente em **Python**, utilizando a biblioteca **Streamlit** como interface gráfica.

O sistema foi construído seguindo a arquitetura **MVC (Model–View–Controller)** e aplica conceitos fundamentais de **Programação Orientada a Objetos (POO)**. A persistência de dados é feita por meio de **arquivos JSON**, simulando um banco de dados simples.

---

## 🚀 Funcionalidades

- Sistema de autenticação com login
- Controle de acesso por perfis:
  - **Administrador**
    - Gerenciamento de produtos (jogos)
    - Gerenciamento de categorias, plataformas e desenvolvedoras
    - Gerenciamento de cupons de desconto
    - Visualização de vendas e avaliações dos clientes
  - **Cliente**
    - Navegação pelos jogos disponíveis
    - Adição de produtos ao carrinho
    - Aplicação de cupons de desconto
    - Finalização de compras
    - Visualização do histórico de compras
    - Avaliação de compras realizadas
- Sistema de carrinho de compras
- Sistema de cupons de desconto (baseado em porcentagem)
- Avaliações de produtos vinculadas às vendas
- Persistência de dados em JSON para todas as entidades

---

## 🧠 Arquitetura

O projeto segue o padrão **MVC (Model–View–Controller)**:

- **Model**
  - Lógica de negócio e entidades (Produto, Usuário, Venda, Carrinho, Cupom, Avaliação, etc.)
  - Camada DAO (Data Access Object) para persistência
- **View**
  - Interface gráfica construída com **Streamlit**
- **Controller (camada View atuando como Controller)**
  - Coordena as ações do usuário e a lógica de negócio por meio da classe `View`

Essa separação melhora a manutenção, legibilidade e escalabilidade do sistema.

---

## 🛠 Tecnologias Utilizadas

- **Python 3**
- **Streamlit** (Interface Gráfica)
- **JSON** (Persistência de Dados)

---

## 📁 Persistência de Dados

Todos os dados da aplicação são armazenados localmente em arquivos JSON, incluindo:
- Usuários
- Produtos
- Vendas
- Itens do carrinho
- Cupons de desconto
- Avaliações

Essa abordagem foi escolhida pela simplicidade e com foco educacional.

---

## 👤 Perfis de Usuário

### Administrador
- Controle total do sistema
- Gerenciamento de produtos e entidades
- Visualização de todas as vendas e avaliações

### Cliente
- Pode navegar e comprar jogos
- Aplicar cupons de desconto
- Visualizar histórico de compras
- Enviar avaliações após compras concluídas

---

## 📌 Observações

Este projeto foi desenvolvido com **fins educacionais**, com foco em:
- Arquitetura de software
- Design orientado a objetos
- Separação de responsabilidades
- Operações CRUD
- Implementação prática do padrão MVC em Python

---

## 📷 Interface

A interface gráfica foi construída inteiramente com **Streamlit**, oferecendo uma experiência interativa e amigável ao usuário.

---

## 📄 Licença

Este projeto foi desenvolvido para fins acadêmicos e de aprendizado.

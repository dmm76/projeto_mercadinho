# 🛒 Sistema de Vendas - Mercadinho Borba Gato

Bem-vindo ao repositório do **Sistema de Vendas para o Mercadinho Borba Gato**, um projeto web desenvolvido com foco em organização, clareza e fácil expansão. Este sistema simula uma aplicação de vendas com cadastros de clientes, vendedores, produtos e registros de vendas com múltiplos itens.

---

## 📸 Visão Geral

> ✅ Acesse o sistema em funcionamento aqui: [🔗 GitHub Pages](https://seu-usuario.github.io/seu-repo/)

---

## 📁 Estrutura do Sistema

O sistema foi desenvolvido com base em uma modelagem relacional robusta. Abaixo estão os principais módulos e suas responsabilidades:

### 🧱 Entidades principais:

| Tabela            | Descrição                                                             |
| ----------------- | --------------------------------------------------------------------- |
| `Clientes`        | Armazena os dados dos clientes, como nome e endereço.                 |
| `Vendedores`      | Contém os dados dos vendedores e a unidade em que trabalham.          |
| `Unidades`        | Representa as unidades físicas do mercadinho (filiais, lojas, etc).   |
| `Produtos`        | Catálogo de produtos, com descrição, preço e categoria.               |
| `Vendas`          | Registra cada venda feita, associando cliente, vendedor e data.       |
| `Vendas_Produtos` | Tabela intermediária que detalha os produtos incluídos em cada venda. |

---

## 🧩 Modelo Relacional

A estrutura segue uma lógica de **relacionamentos bem definidos**:

- 🔗 **Cliente 1:N Venda**: Cada cliente pode realizar várias compras.
- 🔗 **Vendedor 1:N Venda**: Cada vendedor pode realizar várias vendas.
- 🔗 **Venda N:M Produto**: Uma venda pode ter vários produtos e um produto pode estar em várias vendas.
- 🔗 **Vendedor N:1 Unidade**: Cada vendedor pertence a uma unidade.

---

## 🧰 Tecnologias Utilizadas

- HTML5 e CSS3 (caso tenha parte visual)
- SQL para modelagem relacional - Próxima etapa
- [Opcional] Bootstrap ou JS para a interface
- Diagrama criado com ferramentas como draw.io ou dbdiagram.io

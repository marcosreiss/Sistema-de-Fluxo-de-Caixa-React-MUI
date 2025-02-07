# Sistema de Fluxo de Caixa - React + MUI

## Descrição

Este sistema de fluxo de caixa foi desenvolvido utilizando **React** e **Material UI (MUI)** para fornecer uma interface intuitiva e eficiente. Ele oferece controle financeiro completo, incluindo **CRUD** para clientes, fornecedores, produtos, compras e vendas, além de lançamentos avulsos. 

## Funcionalidades Principais

- **Gerenciamento de Clientes e Fornecedores**: Criação, edição, exclusão e listagem de registros.
- **Controle de Produtos**: Cadastro e manutenção de produtos.
- **Registro de Compras e Vendas**: CRUD completo para transações comerciais.
- **Lançamentos Avulsos**: Inclusão manual de entradas e saídas financeiras.
- **Geração de Contas a Pagar e a Receber**: Com status de **Cancelado, Pendente e Pago**.
- **Buscas e Filtros Personalizados**: Disponíveis para todas as entidades, garantindo uma navegação eficiente.
- **Emissão de Relatórios e Recibos**: Geração de documentos padronizados e personalizados.
- **Página de Balanço Financeiro**: Com indicadores-chave de desempenho (**KPIs**) para análise da saúde financeira da empresa.

## Tecnologias Utilizadas

- **React**: Biblioteca principal para a construção da interface.
- **Material UI (MUI)**: Framework de componentes para estilização e design responsivo.
- **React Hook Form**: Gerenciamento de formulários com validações eficientes.
- **React Query**: Implementação de **hooks personalizados** para otimizar requisições e gerenciamento de cache.
- **useContext**: Utilizado para autenticação e sistema de notificações (**toast notifications**).

## Estrutura do Projeto

O projeto segue uma arquitetura modular, garantindo fácil manutenção e escalabilidade:

```
/src
│── components        # Componentes reutilizáveis
│── contexts          # Contextos globais (autenticação, notificações)
│── hooks             # Hooks personalizados com React Query
│── pages             # Páginas principais do sistema
│── services          # Comunicação com a API
│── utils             # Funções auxiliares
│── App.js            # Componente raiz
│── index.js          # Ponto de entrada da aplicação
```

## Fluxo do Sistema

1. **Cadastro de clientes, fornecedores e produtos**.
2. **Registro de compras e vendas**.
3. **Geração automática de contas a pagar e a receber**.
4. **Monitoramento do status de cada transação (Cancelado, Pendente, Pago)**.
5. **Análises e emissão de relatórios financeiros**.
6. **Consulta rápida através de filtros e buscas personalizadas**.
7. **Visualização de KPIs financeiros no painel de balanço**.

---

Este sistema foi desenvolvido com o objetivo de oferecer um controle financeiro prático e eficiente para empresas de diferentes segmentos.

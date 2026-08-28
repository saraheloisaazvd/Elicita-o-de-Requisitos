# Atividade Aula 4 - Elicitação de Requisitos

**Contexto:** Sistema de vendas por telefone e encontros presenciais com 3 perfis de usuário: Vendedor, Administrador e Estoque.

### PROCESSO 1: Registro de Pedidos (Perfil: Vendedor)

**Requisito 1.1:** O sistema deve permitir que o vendedor registre um novo pedido com cliente, produtos, quantidade e forma de pagamento.
*   **Fonte 1:** Entrevista com vendedores. Fonte humana, nível operacional, classe de usuário vendedor.
*   **Fonte 2:** Análise de blocos de pedido / caderno de pedidos atuais. Fonte não humana, categoria documentação.

**Requisito 1.2:** O sistema deve validar se há estoque disponível do produto no momento do registro do pedido.
*   **Fonte 1:** Reunião com o time de estoque. Fonte humana, nível operacional, classe de usuário estoque.
*   **Fonte 2:** Entrevista com gerente de vendas. Fonte humana, nível tático, classe de usuário vendedor.

**Requisito 1.3:** O sistema deve gerar um comprovante do pedido em PDF para envio ao cliente por WhatsApp ou e-mail.
*   **Fonte 1:** Entrevista com vendedores sobre como enviam comprovante hoje. Fonte humana, nível operacional, classe de usuário vendedor.
*   **Fonte 2:** Análise de sistemas concorrentes (ex: Tiny, Bling). Fonte não humana, categoria concorrência.

### PROCESSO 2: Cadastro e Remoção de Produtos (Perfil: Administrador)

**Requisito 2.1:** O sistema deve permitir que o administrador cadastre, edite e remova produtos com nome, descrição, preço e foto.
*   **Fonte 1:** Entrevista com o administrador / dono da empresa. Fonte humana, nível estratégico, classe de usuário administrador.
*   **Fonte 2:** Catálogo atual de produtos em Excel. Fonte não humana, categoria documentação.

**Requisito 2.2:** O sistema deve manter um histórico de alterações de preço dos produtos com data e usuário que alterou.
*   **Fonte 1:** Entrevista com o administrador sobre controle de preços. Fonte humana, nível estratégico, classe de usuário administrador.
*   **Fonte 2:** Política de auditoria e compliance da empresa. Fonte não humana, categoria norma.

**Requisito 2.3:** O sistema não deve permitir remover um produto que possua pedidos em aberto ou em processamento.
*   **Fonte 1:** Entrevista com o administrador. Fonte humana, nível tático, classe de usuário administrador.
*   **Fonte 2:** Entrevista com o time de estoque para entender impacto. Fonte humana, nível operacional, classe de usuário estoque.

### PROCESSO 3: Controle de Quantidade Disponível (Perfil: Estoque)

**Requisito 3.1:** O sistema deve dar baixa automática no estoque ao confirmar um pedido e permitir registrar entradas de mercadoria manualmente.
*   **Fonte 1:** Entrevista com o time de estoque. Fonte humana, nível operacional, classe de usuário estoque.
*   **Fonte 2:** Sistema legado de controle de estoque (planilha atual). Fonte não humana, categoria sistema legado.

**Requisito 3.2:** O sistema deve emitir alerta quando a quantidade de um produto atingir o estoque mínimo.
*   **Fonte 1:** Entrevista com o responsável pelo estoque. Fonte humana, nível operacional, classe de usuário estoque.
*   **Fonte 2:** Reunião com o dono sobre prejuízos por falta de produto. Fonte humana, nível estratégico, classe de usuário administrador.

**Requisito 3.3:** O sistema deve gerar relatório diário de movimentação de estoque (entradas e saídas).
*   **Fonte 1:** Entrevista com gerente de operações. Fonte humana, nível tático, classe de usuário estoque.
*   **Fonte 2:** Modelo de relatório exigido pela contabilidade. Fonte não humana, categoria documentação.

# Domain Mapper Activity

## Entities
- Product (id, size, color)
- Stock (id, prodcutId, min)
- Supplier (id, name)
- Transactions (id, productId, createdAt)
- Order (id)

## Usecases
- Deve ser possível rastrear cada produto individualmente.
- Deve ser possível definir quantidades mínimas de estoque.
- Deve ser possível receber alertas quando o estoque estiver baixo.
- Deve ser possível gerar histórico de vendas.
- Deve ser possível gerar histórico de estoque.
- Deve ser possível criar ordens de compra.
- Deve ser possível gerenciar ordens de compra.
- Deve ser possível integrar API com fornecedores.

## Business
- Criar ordens de compra de forma automática baseadas no estoque e tendências.
- Receber alertas por email e notificações pelo sistema.
- No histórico de vendas exibir quantos produtos foram vendidos em um período.
- No histórico de vendas exibir o lucro gerado por produto.
- No histórico de vendas classificar produtos com mais vendas em um período.
- Exibir tendências de estoque para tomada de decisão.
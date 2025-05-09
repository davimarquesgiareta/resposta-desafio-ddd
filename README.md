Entidades de Domínio:

Produto: Representa cada item individual no estoque. Possui atributos como:
Número de identificação único
Nome/Descrição
Quantidade em estoque
Quantidade mínima de estoque
Preço de venda
(Opcional) Tamanho
(Opcional) Cor
Estoque: Representa o conjunto de produtos disponíveis.
Venda: Representa uma transação de venda de um ou mais produtos. Possui informações como:
Data da venda
Produtos vendidos
Quantidade vendida de cada produto
Preço unitário de venda
Lucro da venda
Alerta de Estoque: Notificação gerada quando o estoque de um produto atinge ou fica abaixo da quantidade mínima definida.
Ordem de Compra: Representa um pedido de novos produtos aos fornecedores. Possui informações como:
Data do pedido
Produtos a serem comprados
Quantidade a ser comprada de cada produto
Status do pedido
Fornecedor: Entidade externa que fornece os produtos.
Histórico de Vendas: Registro de todas as vendas realizadas em um determinado período.
Histórico de Estoque: Registro das movimentações de estoque ao longo do tempo (entradas e saídas).
Ações (Casos de Uso):

Rastrear Produto Individualmente:
Atribuir número de identificação único a um produto.
Registrar informações adicionais do produto (tamanho, cor, etc.).
Visualizar a localização/movimentação de um produto específico no estoque.
Gerenciar Estoque:
Registrar a entrada de novos produtos no estoque.
Registrar a saída de produtos do estoque (venda, perda, etc.).
Atualizar a quantidade em estoque de um produto.
Definir Quantidade Mínima de Estoque:
Definir um limite mínimo de estoque para cada produto.
Gerar Alertas de Estoque:
Verificar periodicamente o nível de estoque de cada produto.
Gerar um alerta quando o estoque de um produto atingir ou ficar abaixo do limite mínimo.
Enviar alertas por e-mail e/ou notificação no sistema.
Visualizar Histórico de Vendas:
Consultar o número de produtos vendidos em um período específico.
Consultar o lucro gerado por produto em um período específico.
Identificar os produtos mais vendidos em diferentes períodos.
Visualizar Histórico de Estoque:
Consultar as tendências de estoque ao longo do tempo.
Analisar as entradas e saídas de estoque.
Criar Ordem de Compra:
Gerar automaticamente ordens de compra com base nas quantidades mínimas e tendências de vendas.
Criar ordens de compra manualmente.
Gerenciar o status das ordens de compra.
Gerenciar Ordem de Compra:
Visualizar ordens de compra pendentes, em andamento e concluídas.
Editar informações de uma ordem de compra.
Confirmar o recebimento de uma ordem de compra.
Integrar com Fornecedores:
Receber atualizações automáticas sobre prazos de entrega de novas remessas.
(Possivelmente) Enviar ordens de compra diretamente aos fornecedores (dependendo da complexidade desejada).

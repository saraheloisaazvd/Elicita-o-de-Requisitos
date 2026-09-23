Requisitos Não Funcionais — ISO/IEC 25010
1. Consultar histórico de pedidos

História de usuário:
Como cliente, quero visualizar meus pedidos anteriores, para conseguir consultar compras que já realizei.

RNF 1.1 — Eficiência de desempenho

O histórico de pedidos deve ser carregado em até 3 segundos para usuários com até 100 pedidos registrados.

Característica ISO/IEC 25010: Eficiência de desempenho.

RNF 1.2 — Confiabilidade

Caso ocorra uma falha temporária no servidor, o sistema deve informar o usuário e permitir uma nova tentativa de carregamento sem perder os dados já disponíveis.

Característica ISO/IEC 25010: Confiabilidade.

RNF 1.3 — Usabilidade

O usuário deve conseguir acessar o histórico de pedidos a partir da tela principal em até 3 interações.

Característica ISO/IEC 25010: Usabilidade.

2. Atualizar informações do produto

História de usuário:
Como administrador do restaurante, quero alterar as informações de um produto, para manter o cardápio atualizado para os clientes.

RNF 2.1 — Eficiência de desempenho

Após salvar uma alteração, as novas informações do produto devem aparecer no cardápio em até 4 segundos.

Característica ISO/IEC 25010: Eficiência de desempenho.

RNF 2.2 — Confiabilidade

O sistema deve impedir que uma alteração seja salva parcialmente caso ocorra uma falha durante o processo, mantendo os dados anteriores até que a atualização seja concluída corretamente.

Característica ISO/IEC 25010: Confiabilidade.

RNF 2.3 — Usabilidade

O administrador deve conseguir editar e salvar as informações de um produto sem precisar acessar mais de duas telas diferentes.

Característica ISO/IEC 25010: Usabilidade.

3. Cancelar um pedido

História de usuário:
Como cliente, quero cancelar meu pedido dentro do prazo permitido, para evitar que ele seja preparado quando não precisar mais da compra.

RNF 3.1 — Segurança

Somente o cliente responsável pelo pedido poderá solicitar seu cancelamento.

Característica ISO/IEC 25010: Segurança.

RNF 3.2 — Confiabilidade

Após o cancelamento ser confirmado, o pedido não poderá voltar automaticamente para o status de preparo.

Característica ISO/IEC 25010: Confiabilidade.

RNF 3.3 — Usabilidade

A opção de cancelamento deve estar disponível na tela de acompanhamento do pedido e exigir no máximo 3 interações para ser concluída.

Característica ISO/IEC 25010: Usabilidade.

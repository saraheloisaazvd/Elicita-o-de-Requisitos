**MUST - Acompanhar pedido**

*Como usuário:*
Quero ver onde está meu pedido
Para que eu saiba quando minha comida vai chegar

**1.** Dado que fiz um pedido
**Quando** eu abrir o app
**Então** vejo o status Em preparo/Saiu para entrega/Entregue

**2.** Dado que o pedido saiu pra entrega
**Quando** eu entrar na tela do pedido
**Então** vejo a localização do entregador no mapa

**3.** Dado que o status mudou
**Quando** o restaurante/entregador atualizar
**Então** recebo notificação do app

**SHOULD - Item indisponível**

*Como restaurante:*
Quero desativar itens do cardápio
Para que o cliente não peça algo que acabou

**1.** Dado que estou no painel do restaurante
**Quando** marco um item como "Indisponível"
**Então** ele some do cardápio do cliente

**2.** Dado que um item ficou indisponível
**Quando** o cliente já havia adicionado ao carrinho
**Então** ele recebe um aviso e o item é removido

**3.** Dado que reativei o item
**Quando** marco como "Disponível"
**Então** ele volta aparecer no cardápio

**COULD - Problema na entrega**

*Como entregador:*
Quero avisar se a entrega teve problemas
Para que o suporte e o cliente saibam

**1.** Dado que estou fazendo uma entrega
**Quando** clico em "Reportar Problema"
**Então** posso escolher o motivo Não atendeu/Endereço errado/Outro

**2.** Dado que reportei um problema
**Quando** envio
**Então** cliente e suporte são notificados

**3.** Dado que o problema foi reportado
**Quando** o suporte visualizar
**Então** o pedido muda para "Com Problemas"

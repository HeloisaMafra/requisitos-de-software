# 🛵 Exemplo Prático — Sistema de Delivery

Este estudo de caso apresenta requisitos funcionais e não funcionais para um sistema fictício de delivery.

## Cenário

Uma pequena lanchonete deseja disponibilizar um sistema no qual clientes possam consultar o cardápio e fazer pedidos pela internet. A equipe da lanchonete precisa acompanhar os pedidos recebidos.

## Requisitos funcionais

| ID | Requisito |
|---|---|
| RF01 | O sistema deve permitir que o cliente consulte o cardápio. |
| RF02 | O sistema deve exibir o nome, a descrição e o preço de cada produto. |
| RF03 | O sistema deve permitir que o cliente adicione produtos ao carrinho. |
| RF04 | O sistema deve calcular o subtotal e o valor total do pedido. |
| RF05 | O sistema deve permitir que o cliente informe o endereço de entrega. |
| RF06 | O sistema deve permitir que o cliente confirme o pedido. |
| RF07 | O sistema deve permitir que a equipe consulte os pedidos recebidos. |
| RF08 | O sistema deve permitir que a equipe atualize o status do pedido. |

## Requisitos não funcionais

| ID | Categoria | Requisito |
|---|---|---|
| RNF01 | Desempenho | Nas condições de teste definidas, 95% das consultas ao cardápio devem responder em até 2 segundos. |
| RNF02 | Segurança | O acesso às funções administrativas deve exigir autenticação. |
| RNF03 | Compatibilidade | As páginas devem ser utilizáveis nos navegadores e dispositivos definidos para o projeto. |
| RNF04 | Usabilidade | O sistema deve apresentar mensagens claras quando houver erro no preenchimento do pedido. |
| RNF05 | Privacidade | Os dados pessoais devem ser acessados apenas por pessoas e processos autorizados. |

## Como diferenciar?

Pergunte:

- **É uma ação ou função que o sistema oferece?** Provavelmente é um requisito funcional.
- **É uma condição de qualidade, segurança, desempenho ou restrição?** Provavelmente é um requisito não funcional.

### Exemplo de comparação

**“O sistema deve permitir que o cliente acompanhe o pedido.”**  
É funcional: descreve uma função.

**“A atualização do status deve aparecer para o cliente em até 5 segundos após ser registrada.”**  
É não funcional: define uma condição de desempenho para essa atualização.

## Observação

Os requisitos deste arquivo são exemplos didáticos, não uma especificação validada para um produto real. Em um projeto, é necessário conversar com clientes, usuários e equipe para confirmar as necessidades e definir critérios realistas.

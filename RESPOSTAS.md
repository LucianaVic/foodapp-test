# RESPOSTAS

## Bugs corrigidos

### Bug 1
O carrinho duplicava produtos ao adicionar o mesmo item, corrigi verificando se o item já existia e incrementando a quantidade.

### Bug 2
O total ignorava a quantidade do item, corrigi multiplicando preço por quantidade.

### Bug 3
O carrinho não era limpo após finalizar pedido, corrigi usando clearCart() após sucesso do checkout.

##Adicionei sistema de cupons:
- BEMVINDO10: 10% de desconto no total
- FRETE20: R$ 20,00 de desconto fixo

# RESPOSTAS

## Melhorias possível

- A API aceita o total vindo do frontend sem recalcular no backend.
- Não há persistência dos pedidos, eles somem ao reiniciar o servidor.
- O checkout não mostra uma tela de revisão antes de enviar.
- Não há testes automatizados.
- O campo de cupom poderia ter botão para remover cupom aplicado.
- Não tem um botão para remover o cupom de desconto.
- Melhorar acessibilidade dos botões, inputs e mensagens de erro.
- Impedir finalização de pedido com carrinho vazio.
- Validar melhor os campos do checkout, como nome e endereço obrigatórios.


## Melhoria aplicada

- Escolhi implementar a opção de remover o cupom aplicado porque, depois que o usuário aplica um desconto, ele pode querer trocar por outro cupom ou desistir de usar aquele. Sem essa opção, ele teria que recarregar a página ou alterar manualmente o campo, o que prejudica a experiência. Além disso, é uma melhoria pequena, mas importante para o fluxo de checkout, porque dá mais controle ao usuário antes de finalizar o pedido.

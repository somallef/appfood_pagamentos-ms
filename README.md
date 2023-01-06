# appfood [Microsserviço de pagamento]

Projeto criado como acompanhamento do treinamento [Microsserviços na prática: implementando com Java e Spring](https://www.alura.com.br/curso-online-microsservicos-implementando-java-spring)

Para criar um pagamento, basta enviar uma requisição POST com o seguinte corpo:

``` json
{
    "valor": 500,
    "nome": "Jacqueline",
    "numero": "12345678",
    "expiracao": "10/29",
    "codigo": "123",
    "pedidoId": 1,
    "formaDePagamentoId": 1
}
```


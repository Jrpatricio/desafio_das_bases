# Desafio das Bases

Link para apresentação da solução
https://docs.google.com/presentation/d/1nwIFp9_Pk7SlGjXZlUw_pyemeeEybsvgJaNMdRqdv0s/edit?usp=sharing


## Serviço que consume Base A

Este serviço deve retornar o seguinte payload:

```
{
   "cpf":"46693389978",
   "nome":"Alessandro Roberto",
   "endereco":{
      "logradouro":"Rua da felicidade",
      "numero":788,
      "complemento":null,
      "cidade": "City of Dores",
      "bairro":"Vila das dores",
      "uf":"SP"
   },
   "dividas":[
      {
         "id": 1,
         "nome":"Divida com banco X",
         "situacao":"PROSTESTADA",
         "valor":5800.90
      }
   ]
}
```


## Serviço que consume Base B

Este serviço deve retornar o seguinte payload:

```
{
   "cpf":"46693389978",
   "nome":"Alessandro Roberto",
   "idade":38,
   "endereco":{
      "logradouro":"Rua da felicidade",
      "numero":788,
      "complemento":null,
      "cidade":"City of Dores",
      "bairro":"Vila das dores",
      "uf":"SP"
   },
   "fonteRenda":{
      "ocupacao":"assalariado",
      "rendaMensal":2500,
      "rendaAnual":30000
   },
   "bens":[
      {
         "id":1,
         "tipo":"Automovel",
         "descricao":"Celta prata - ano 2020/2019",
         "valorAvaliado":25800
      },
      {
         "id":2,
         "tipo":"Imovel",
         "descricao":"Celta prata - ano 2020/2019",
         "endereco":{
            "logradouro":"Rua da tristeza",
            "numero":788,
            "complemento":null,
            "cidade":"City of Sorrisos",
            "bairro":"Vila das risadas",
            "uf":"SP"
         },
         "valorAvaliado":205800
      }
   ]
}
```

## Serviço que consume Base C

Este serviço deve retornar o seguinte payload:

```
{
   "cpf":"46693389978",
   "nome":"Alessandro Roberto",
   "idade":38,
   "endereco":{
      "logradouro":"Rua da felicidade",
      "numero":788,
      "complemento":null,
      "cidade":"City of Dores",
      "bairro":"Vila das dores",
      "uf":"SP"
   },
   "fonteRenda":{
      "ocupacao":"assalariado",
      "rendaMensal":2500,
      "rendaAnual":30000
   },
   "transaçõesFinaceiras":[
      {
         "id":1,
         "tipo":"Investimento CDB",
         "valorInvestido":25800
      }
   ],
   "ComprasComCartão":[
      {
         "id":1,
         "cartao":"4558XXXXXXX",
         "limite":5000,
         "valorDaCompra":25,
         "vendedor":"Amazon",
         "cnpjDoVendedor":"45.456.456/0001-85"
      },
      {
         "id":2,
         "cartao":"4563XXXXXXX",
         "limite":500,
         "valorDaCompra":100,
         "vendedor":"Mercado Livre",
         "cnpjDoVendedor":"46.457.465/0001-73"
      }
   ],
   "dataUltimaConsulta":"23/03/2021- 16:30:45"
}
```

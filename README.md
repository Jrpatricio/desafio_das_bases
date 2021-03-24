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
   "fonte_renda":{
      "ocupacao":"assalariado",
      "renda_mensal":2500,
      "renda_anual":30000
   },
   "bens":[
      {
         "id":1,
         "tipo":"Automovel",
         "descricao":"Celta prata - ano 2020/2019",
         "valor_avaliado":25800
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
         "valor_avaliado":205800
      }
   ]
}
```

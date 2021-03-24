# Desafio das Bases

Link para apresentação da solução
https://docs.google.com/presentation/d/1nwIFp9_Pk7SlGjXZlUw_pyemeeEybsvgJaNMdRqdv0s/edit?usp=sharing


# Serviço que consume Base A

Este serviço deve retornar o seguinte payload:

```
{
   "cpf":"46693389978",
   "nome":"Alessandro Roberto",
   "endereco":{
      "logradouro":"Rua da felicidade",
      "numero":788,
      "complemento":null,
      "bairro":"Vila das dores",
      "uf":"SP"
   },
   "dividas":[
      {
         "id": 1,
         "nome":"Divida com banco X",
         "situacao":"PROSTESTADA",
         "valor":5,
         800.90
      }
   ]
}
```

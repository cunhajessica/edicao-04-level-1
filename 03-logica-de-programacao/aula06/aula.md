# Aula 06 - Condicionais

Assista ao vídeo:

  1. [Condicionais](https://www.youtube.com/watch?v=Uw7X_JwGbis) ✅

> É **#fundamental** que você assista ao vídeo. É **#opcional** _(embora muito importante)_ que você faça o exercício.

---

#### _Exercício:_ ✅

O IMC significa `Índice de Massa Corpórea` e é um indicador utilizado pela OMS _(Organização Mundial da Saúde)_ como referência para saber a saúde de uma pessoa com base no seu peso e altura.

O cálculo do IMC é feito pela divisão do `peso` de alguém pela sua `altura` ao quadrado. Os valores de referência do índice são:

| IMC | Classificação | Grau de Obesidade |
| - | - | - |
| Menor do que 18,50 | Magreza | 0 |
| Entre 18,50 e 24,99 | Normal | 0 |
| Entre 25,00 e 29,99 | Sobrepeso | 1 |
| Entre 30,00 e 39,99 | Obesidade | 2 |
| Maior ou igual a 40,00 | Obesidade grave | 3 |

Faça um algoritmo que efetue o cálculo do IMC, com base nas variáveis `peso` e `altura`.

Exiba o valor do IMC e a classificação obtida. Se houver algum grau de obesidade, exiba também a mensagem: `Cuidado! Você está acima do peso recomendado pela OMS.`

Se o grau de obesidade for `3`, adicione também a seguinte mensagem: `É importante procurar um médico para avaliar sua saúde.`

_**Após** ter feito o exercício, dá uma olhada na [nossa implementação](resolucao.md)._

---

_Minha Resposta:_

```
peso = 50
altura = 1.58

imc = (peso / altura **2)

console.log("O seu IMC é:", imc.toFixed(2))

grau = ""

if (imc <=18.50){
  grau = "Grau 0 | Classificação: Magreza"
}
else if (imc <=21.99){
  grau = "Grau 1 | Classificação: Normal"
}
else if (imc <=29.99){
  grau = "Grau 2 | Classificação: Sobrepeso"
}
else if (imc <=39.99){
  grau = "Grau 3 | Classificação: Obesidade"
}
else {
  grau = "Grau 4 | Classificação: Obesidade grave"
}

console.log("O seu grau de IMC é:", grau)

if (imc > 29.99){
  console.log("Cuidado! Você está acima do peso recomendado pela OMS.")
}
```


---

👈 [Voltar para aula anterior](../aula05/aula.md) ..... [Avançar para próxima aula](../aula07/aula.md) 👉

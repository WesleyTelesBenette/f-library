# 🤔 Condição
## ✨ Introdução
Não existe como você dizer que sabe programar, se não souber o que são condições e como usar.
> Ah 😐. Pelo jeito não sei programar... e nem fazer um bolo de abacate 🥲

Em contrapartida, é um conceito muito fácil, e se você entendeu o que é uma variável, provavelmente não vai ter muitas dificuldades.
> Veremos 😑! Tenho habilidades assustadoras em ter dificuldades extremas na menor coisa que seja 💪😎

## 🪄 Explicação
### O que é uma Condição?
Uma condição é uma **estrutura condicional**, onde caso uma condição seja verdadeira, um código específico é executado, e se a condição for falsa, pode não ser executado nada ou outro código de sua escolha.
> Tudo bem... não entendi nadinha 😐👍, preciso disso na prática 😒

Então vamos para um exemplo prático.

### Exemplo
Se a `idade` do usuário for menor que `18`, então exibir `"Você é menor de idade!"`, se não exibir `"Acesso permitido."`.

```c
//C
if (idade < 18) {
    printf("Você é menor de idade!");
} else {
    printf("Acesso permitido.");
}
```
```csharp
//C#
if (idade < 18) {
    Console.WriteLine("Você é menor de idade!");
} else {
    Console.WriteLine("Acesso permitido.");
}
```
```java
//Java
if (idade < 18) {
    System.out.println("Você é menor de idade!");
} else {
    System.out.println("Acesso permitido.");
}
```
```js
//JavaScript
if (idade < 18) {
   console.log("Você é menor de idade!")
} else {
    console.log("Acesso permitido.")
}
```
```python
#Python
if (idade < 18):
   print("Você é menor de idade!")
else:
    print("Acesso permitido.")
```
```php
//PHP
if ($idade < 18) {
   echo "Você é menor de idade!";
} else {
    echo "Acesso permitido.";
}
```
Obs. Analisando esses trechos de código, você pode perceber que:
- A palavra-chave `if` significa "se", onde caso a condição (na mesma linha dele) for verdadeira, tudo que estiver entre suas chaves `{ }` é executado.
- A palavra-chave `else` significa "se não", onde caso a condição do `if` anterior a ele não for verdadeira, tudo que estiver entre suas chaves `{ }` é executado.
- Não no caso desse exemplo, mas em outros contextos o `else` é opcional.
> ...

### Operadores Lógicos
Os operadores lógicos são as formas com que você pode montar suas condições, seja para realizar uma verificação de condição específica ou combinar várias condições.
| Operador | Descrição | Exemplo |
| - | - | - |
| == | Igual | valor1 == valor2 |
| != | Diferente | valor1 != valor2 |
| > | Maior | valor1 > valor2 |
| >= | Maior ou igual | valor1 >= valor2 |
| < | Menor | valor1 < valor2 |
| <= | Menor ou igual | valor1 <= valor2 |
| && | E. As duas condições precisam ser verdadeiras | (condição) && (condição) |
| \|\| | Ou. Umas das duas condições precisam ser verdadeiras | (condição) \|\| (condição) |
> ...

### Exemplo
Um programa que:
- Cheque se o e-mail do usuário está correto, juntamente se ele é maior de idade.
- Caso o e-mail esteja correto, cheque se a senha do usuário está correta.
- Apresente mensagens para caso as condições sejam verdadeiras, e também caso sejam falsas.


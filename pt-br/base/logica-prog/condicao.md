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
> Deixa eu ver se eu entendi 🤔 <br/><br/>
> double meuSaldoNoBanco = -3458.63;
> 
> if (meuSaldoNoBanco < 0) { <br/>
> <span>&nbsp;&nbsp;&nbsp;&nbsp;Console.WriteLine("Estou pobre e terei que vender a minha casa para pagar minhas dívidas."); </span> <br/>
> } <br/><br/>
> É isso? Acho que programação está me traumatizando 🥲

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
> Hmmm 🤔 blz 👍, acho que dá até para entender, mas vou precisar testar 38h por dia até eu entender de verdade 😳

Vamos a um exemplo, só que dessa vez um programa completo, para você ter uma noção um pouco maior de um exemplo real.

### Exemplo
Um programa que:
- Cheque se o e-mail do usuário está correto, juntamente se ele é maior de idade.
- Caso o e-mail esteja correto, cheque se a senha do usuário está correta.
- Apresente mensagens para caso as condições sejam verdadeiras, e também caso sejam falsas.

```c
//C
#include <stdio.h>

int main() {
    int idade = 21;
    char email[] = "seu.tio@gmail.com";
    char senha[] = "12345678";
    
    int idadeMinima = 18;
    char emailCerto[] = "seu.tio@gmail.com";
    char senhaCerta[] = "uva12345";
    
    if ((strcmp(email, emailCerto) == 0) && (idade >= idadeMinima)) {
        if (strcmp(senha, senhaCerta) == 0) {
            printf("Login realizado com sucesso.");
        } else {
            printf("Senha incorreta...");
        }
    } else {
        printf("Usuário inválido!");
    }

    return 0;
}
```
```csharp
//C#
using System;

public class App
{
    public static void Main(string[] args)
    {
        int idade = 21;
        string email = "seu.tio@gmail.com";
        string senha = "12345678";
        
        int idadeMinima = 18;
        string emailCerto = "seu.tio@gmail.com";
        string senhaCerta = "uva12345";
        
        if ((email == emailCerto) && (idade >= idadeMinima)) {
            if (senha == senhaCerta) {
                Console.WriteLine("Login realizado com sucesso.");
            } else {
                Console.WriteLine("Senha incorreta...");
            }
        } else {
            Console.WriteLine("Usuário inválido!");
        }
    }
}
```
```java
//Java
class App {
    public static void main(String[] args) {
        int idade = 21;
        String email = "seu.tio@gmail.com";
        String senha = "12345678";
        
        int idadeMinima = 18;
        String emailCerto = "seu.tio@gmail.com";
        String senhaCerta = "uva12345";
        
        if ((email.equals(emailCerto)) && (idade >= idadeMinima)) {
            if (senha.equals(senhaCerta)) {
                System.out.println("Login realizado com sucesso.");
            } else {
                System.out.println("Senha incorreta...");
            }
        } else {
            System.out.println("Usuário inválido!");
        }
    }
}
```
```js
//JavaScript
let idade = 21;
let email = "seu.tio@gmail.com";
let senha = "12345678";

let idadeMinima = 18;
let emailCerto = "seu.tio@gmail.com";
let senhaCerta = "uva12345";

if ((email == emailCerto) && (idade >= idadeMinima)) {
    if (senha == senhaCerta) {
        console.log("Login realizado com sucesso.");
    } else {
        console.log("Senha incorreta...");
    }
} else {
    console.log("Usuário inválido!");
}
```
```python
#Python
idade = 21;
email = "seu.tio@gmail.com";
senha = "12345678";

idadeMinima = 18;
emailCerto = "seu.tio@gmail.com";
senhaCerta = "uva12345";

if ((email == emailCerto) and (idade >= idadeMinima)):
    if (senha == senhaCerta):
        print("Login realizado com sucesso.");
    else:
        print("Senha incorreta...");
else:
    print("Usuário inválido!");

```
```php
//PHP
<?php

$idade = 21;
$email = "seu.tio@gmail.com";
$senha = "12345678";

$idadeMinima = 18;
$emailCerto = "seu.tio@gmail.com";
$senhaCerta = "uva12345";

if (($email == $emailCerto) && ($idade >= $idadeMinima)) {
    if ($senha == $senhaCerta) {
        echo "Login realizado com sucesso.";
    } else {
        echo "Senha incorreta...";
    }
} else {
    echo "Usuário inválido!";
}
```






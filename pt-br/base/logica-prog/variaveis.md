# 📦 Variáveis
## ✨ Introdução
Esse é um dos conceitos mais importantes de toda programação, você vai trabalhar com isso o tempo inteiro, independente da área da programação que você escolher trabalhar.
> Acredite, variáveis vão te perseguir aonde quer que você vá... 🥲

## 🪄 Explicação
### O que seria uma variável?
Num resumo rápido, é uma estrutura nomeada, que faz referência a um espaço na memória RAM, onde se pode armazenar dados, acessado e manipulando em diferentes pontos do seu programa.
> Ok, nem eu mais entendo o que eu falo 😒

Você pode enxergar variáveis como "caixas", que precisam de:
- Um **nome**: para conseguirmos indentificar que caixa é essa.
- Um **tipo**: para sabermos que tipo de coisa podemos encontrar dentro dessa caixa.
- Um **conteúdo**: essa caixa é um local que pode ser guardado coisas, e ela sempre tem um conteúdo, mesmo que ele seja "nada".

### Regras para criar uma variável
Antes de efetivamente criar uma variável, precisamos entender duas coisas principais: **nomenclatura** e **tipos**.
> Não aguento mais, a teoria não acabaaaaaa 😭

Regras básicas sobre nomes de variáveis:
- Só podem conter letras, números e sublinahado ( _ ).
- Não pode começar por números.
- Normalmente não pode ter acentos, embora algumas linguagens aceitem (mesmo assim evite usar).
> Pelo menos eu não preciso decorar isso, a maioria das linguagens esfrega na minha cara um erro, indicando que eu na vida não sei nem ao menos nomear uma variável 😁

Tipos mais comuns 🗒️:
| Tipo | Descrição | Exemplos |
| - | - | - |
| `boolean` | Verdadeiro ou falso | `true` e `false` |
| `char` | Caractere único. | `'f'` e `'W'` |
| `string` | Texto | `"Fernanda"` e `"20 de Abril de 2004"` |
| `int` | Número inteiro | `8888` e `16` |
| `float` | Número racional | `89187918791.2f` e `3.1415f` |
| `double` |  Número racional extendido | `516516516515615665.519581651` e `2.5` |
> Tá... não vou lembrar disso com minha memória de esquilo 🐿️, vou precisar olhar essa tabela a cada mês, semana, dia, hora, minuto e segundo da minha vida, em que eu estiver programando... 💀

Pode aparentar ser meio confuso e difícil, mas na prática é mais simples do que parece.

### Exemplo
Uma variável do tipo **texto**, com nome `minhaVariavelF`, onde seu conteúdo é `"F Library é a melhor!"`:
```c
//C
char minhaVariavelF[] = "F Library é a melhor!";
```
```csharp
//C#
string minhaVariavelF = "F Library é a melhor!";
```
```java
//Java
String minhaVariavelF = "F Library é a melhor!";
```
```js
//Javascript
let minhaVariavelF = "F Library é a melhor!"
```
```python
#Python
minhaVariavelF = "F Library é a melhor!"
```
```php
//PHP
$minhaVariavelF = "F Library é a melhor!";
```

Obs. Se você prestou atenção nos exemplos, pode ter percebido alguns detalhes:
- A linguagem `C` não tem o tipo `string` (porém uma gambiarra da linguagem resolve).
- As linguagem `C`, `C#` e `Java` são **estaticamente tipadas** (para declarar uma variáveis precisa definir o tipo).
- As linguagem `Javascript`, `Python` e `PHP` são **dinamicamente tipadas** (a linguagem reconhece sozinha qual o tipo da variável).
- E que algumas linguagens como `Javascript` e `Python`, você precisa usar ponto e vírgula no final da linha.
> 😝 - Ksksksk sou preguiçoso, só vou usar linguagem dinâmica apartir de agora. <br/>
> `JS` - Aé? E esse seu `int` aí? To achando que é uma `string`, vou trocar o tipo ksksksks <br/>
> 😢 - Calma aí, amigão. Também não é assim...

### Operações Aritméticas
Com variáveis numéricas como: `int`, `float` e `double`, é possível realizar cálculos, coisa que é muito comum dentro de um programa.
> 😢 - Vish, não sei fazer conta nenhuma... me lasquei. <br/>
> 🖥️ - Relaxa, a Mãe aqui faz as conta pra você, só me mandar as fórmulas que eu preciso calcular, beleza? 👍. <br/>
> 🤩 - Obrigado, Sra. linguagem de programação rodando no meu computador!

As principais operações mais comuns:
| Símbolo | Descrição | Exemplo |
| - | - | - |
| `+` | Adição | `varNum = 4 + 7` |
| `-` | Subtração | `varNum = 4 - 7` |
| `*` | Multiplicação | `varNum = 4 * 7` |
| `/` | Divisão | `varNum = 4 / 7` |
| `%` | Resto de Divisão | `varNum = 4 % 7` |
> Ok, acho que isso eu já consigo 😎👍, porque não é possível que eu seja tão burro também 🥲.

Vamos para um exemplo mais prático.

### Exemplo
Uma variável chamada `num` que tem o valor de `8`, somada com `36` e **depois** dividida por `11`. Onde todo esse cálculo é armazenado na variável `somaDeNum`.

```c
//C
int num = 8;
int somaDeNum = (8 + 36) / 11;
```
```csharp
//C#
int num = 8;
int somaDeNum = (8 + 36) / 11;
```
```java
//Java
int num = 8;
int somaDeNum = (8 + 36) / 11;
```
```js
//Javascript
let num = 8
let somaDeNum = (8 + 36) / 11
```
```python
#Python
num = 8
somaDeNum = (8 + 36) / 11
```
```php
//PHP
$num = 8;
$somaDeNum = (8 + 36) / 11;
```
Obs. Ok, vamos para mais uma análise:
- Você pode criar expressões matemáticas (basicamente fórmulas) misturando várias operações e difinindo prioridade com parênteses.
- Em todas as linguagens, realizar um cálculo é uma ação práticamente idêntica.
- Você não "rodou" esses código, porém se você executasse eles, veria que linguagens estáticas como `C`, `C#` e `Java` deram o resultado `4`, enquanto nas demais linguagens dinâmicas o resultado é próximo de `4.3636`, e se você quiser um resultado inteiro vai ter que usar métodos ou lógicas específicas da linguagem.
> Droga! Não sei se as linguagens dinâmicas me ajudam ou me atrapalham 😥

### Variáveis no Console
Voltando para o tema ***console***, você também pode usar variáveis nas suas "escritas na tela". Dessa forma:
```c
//C
printf(variavelNome); //Variável sozinha

printf("Meu nome é: " + variavelNome); //Variável com texto
```
```csharp
//C#
Console.WriteLine(variavelNome);  //Variável sozinha

Console.WriteLine($"Meu nome é: {variavelNome}"); //Variável com texto

Console.WriteLine("Meu nome é: " + variavelNome); //Variável com texto
```
```java
//Java
System.out.println(variavelNome);  //Variável sozinha

System.out.println("Meu nome é: " + variavelNome); //Variável com texto
```
```js
//Javascript
console.log(variavelNome)  //Variável sozinha

console.log(`Meu nome é: ${variavelNome}`) //Variável com texto

console.log("Meu nome é: " + variavelNome) //Variável com texto
```
```python
#Python
print(variavelNome)  #Variável sozinha

print(f"Meu nome é: {variavelNome}") #Variável com texto

print("Meu nome é: " + variavelNome) #Variável com texto
```
```php
//PHP
echo $variavelNome;  //Variável sozinha

$outraVariavel = "Meu nome é: {$variavelNome}"; //Variável com texto
echo outraVariavel; //Sim, teve que ser armazenado numa outra variável antes...

$outraVariavel = "Meu nome é: " . $variavelNome; //Variável com texto
echo outraVariavel; //Sim, teve que ser armazenado numa outra variável antes...
```


<!--

Ok, mas para que serve uma variável? 🤨
- **Guardar informações em seu conteúdo** (como: nome, e-mail, senha, algum número para uma conta, idade, cpf etc.).
- **Elas economizam tempo** (quando você usa o nome de uma variável, na hora que o programa é executado esse nome é substituido pelo valor da variável, assim te evita de escrever esse conteúdo em várias partes do código).
- **Ajudam na manutenção do código** (se você precisar mudar esse conteúdo, mudar na variável muda automaticamente em todos os pontos que tiverem o nome dela).
- **Poder tratar dados** (guardando informações num variável, você pode modificar essas informações de diversas formas).

-->

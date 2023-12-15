# F Library - Lógica de Programação

A Lógica de Programação é o conceito primordial 🧐 e, sem dúvidas, o mais importante da programação no geral, pois ela pode ser observada 🔍 em qualquer linguagem de programação desde [1950](https://www.programador.com.br/historia-da-programacao.html).

Embora pareça algo antigo ou simplesmente um conceito que pode ser uma perca de tempo, vale ressaltar que ao aprender Lógica de Programação, você consegue entender o básico de qualquer linguagem com extrema facilidade 😎, além de te evitar de cometer erros absurdos de lógica básica 😳.
(traduzindo: aprenda ou sofra constantemente 🥰)

Mas claro, nada te impede de aprender programação sem saber ela...

## 📑 Informações Técnicas
- 📖 Tempo de leitura estimado: **?** min.
- 📜 Será utilizado como exemplo as linguagens: `C`, `C#`, `Java`, `PHP` e `Python`, porém **não se apegue a linguagem utilizada**, e sim ao conceito explicado com ela.

## Variáveis
Esse é um dos conceitos mais importantes de toda programação, você vai trabalhar com isso o tempo inteiro.

Variáveis são como "caixas" 📦, que precisam de:
- Um **nome** (para conseguirmos indentificar que caixa é essa).
- Um **tipo** (para sabermos que tipo de coisa podemos encontrar dentro dessa caixa).
- Um **conteúdo** (a caixa é um local que pode ser guardado coisas, enão ela sempre tem um centeúdo, mesmo que ele seja "nada").

Ok, mas para que serve uma variável? 🤨
- **Guardar informações em seu conteúdo** (como: nome, e-mail, senha, algum número para uma conta, idade, cpf etc.).
- **Elas economizam tempo** (quando você usa o nome de uma variável, na hora que o programa é executado esse nome é substituido pelo valor da variável, assim te evita de escrever esse conteúdo em várias partes do código).
- **Ajudam na manutenção do código** (se você precisar mudar esse conteúdo, mudar na variável muda automaticamente em todos os pontos que tiverem o nome dela).
- **Poder tratar dados** (guardando informações num variável, você pode modificar essas informações de diversas formas).

Regras básicas sobre nomes de variáveis ✍️:
- Só podem conter letras, números e sublinahado ( _ ).
- Não pode começar por números.
- Normalmente não pode ter acentos, embora algumas linguagens aceitem (mesmo assim evite usar).

Tipos mais comuns 🗒️:
- `boolean` : Verdadeiro ou falso (basicamente um binário de 0 ou 1).
- `char` : Caractere único (tipo uma única letra).
- `string` : Texto.
- `int` : Número inteiro.
- `double` ou `float` : Número racional (quebrado, com vírgula).

Pode aparentar ser meio confuso e difícil 😵‍💫, mas na prática é mais simples do que parece.

### Exemplo
Uma variável do tipo **texto**, com nome `minhaVariavelF`, onde seu conteúdo é "F Library é a melhor!":
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
```python
#Python
minhaVariavelF = "F Library é a melhor!";
```
```php
//PHP
$minhaVariavelF = "F Library é a melhor!";
```

Obs. Se você prestou atenção nos exemplos percebeu que:
- A linguagem `C` não tem o tipo `string` 💀 (mas uma gambiarra resolve).
- A linguagem `C`, `C#` e `Java` são **estaticamente tipadas** 🗿 (para declarar uma variáveis precisa definir o tipo).
- A linguagem `Python` e `PHP` são **dinamicamente tipadas** 🪄 (a linguagem reconhece sozinha qual o tipo da variável).

E por último, caso ainda esteja utiizando o console, você também pode escrever variáveis na tela.
```c
//C
printf(variavelNome); //Variável sozinha

printf("Meu nome é: " + variavelNome); //Variável com texto
```
```csharp
//C#
Console.WriteLine(variavelNome);  //Variável sozinha

Console.WriteLine($"Meu nome é: {variavelNome}"); //Variável com texto

Console.WriteLine($"Meu nome é: " + variavelNome); //Variável com texto
```
```java
//Java
System.out.println(variavelNome);  //Variável sozinha

System.out.println("Meu nome é: " + variavelNome); //Variável com texto
```
```python
#Python
print(variavelNome)  #Variável sozinha

print(f"Meu nome é: {variavelNome}") #Variável com texto

print(f"Meu nome é: " + variavelNome) #Variável com texto
```
```php
//PHP
echo $variavelNome;  //Variável sozinha

$outraVariavel = "Meu nome é: {$variavelNome}"; //Variável com texto
echo outraVariavel; //Sim, teve que ser armazenado numa outra variável antes...

$outraVariavel = "Meu nome é: " . $variavelNome; //Variável com texto
echo outraVariavel; //Sim, teve que ser armazenado numa outra variável antes...
```

## Inputs


## Condição


## Loop


## Arrays


## Função e Método


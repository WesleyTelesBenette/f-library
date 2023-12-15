# F Library - Lógica de Programação

A Lógica de Programação é o conceito primordial 🧐 e, sem dúvidas, o mais importante da programação no geral, pois ela pode ser observada 🔍 em qualquer linguagem de programação desde [1950](https://www.programador.com.br/historia-da-programacao.html).

Embora pareça algo antigo ou simplesmente um conceito que pode ser uma perca de tempo, vale ressaltar que ao aprender Lógica de Programação, você consegue entender o básico de qualquer linguagem com extrema facilidade 😎, além de te evitar de cometer erros absurdos de lógica básica 😳.
(traduzindo: aprenda ou sofra constantemente 🥰)

Mas claro, nada te impede de aprender programação sem saber ela...

## 📑 Informações Técnicas
- 📖 Tempo de leitura estimado: **?** min.
- 📜 Será utilizado como exemplo as linguagens: `C`, `C#`, `Java`, `PHP` e `Python`, porém **não se apegue a linguagem utilizada**, e sim ao conceito explicado com ela.

## ✒️ Escrever na tela (console)
Quando se trata de um programa, normalmente não é interessante criar um amontado de código se você não consegue ver 👀 o que está acontecendo e nem iteragir com nada. Óbvio que não é o que você quer 🫵😠.

Muitas linguagens são direcionadas a vários fins, como: apps de celular 📱, sites 🌐, aplicativos de computador 🖥️ etc.

O que lógicamente indica que você poderia sim "escrever na tela" usando a tecnologia específica da sua linguagem de escolha, porém todas as linguagens possuem a capacidade de serem executadas num console (telinha preta cheia dos código 👩‍💻), o que vai deixar nosso exemplo mais genérico e mais simples (ou seja, vai ser mais fácil para qualquer Neandertal 🦖 ~~igual você~~ entender).

Tudo bem, vamo logo para o código, já devo ter te entediado. 😴

Para exibir algo na tela (do console), normalmente os comandos são simples e diretos.

### Exemplos
Exemplos exibindo a frase "Bem-vindo ao F-Library!":
```c
//C
printf("Bem-vindo ao F-Library!");
```
```csharp
//C#
Console.WriteLine("Bem-vindo ao F-Library!");
```
```java
//Java
System.out.println("Bem-vindo ao F-Library!");
```
```python
#Python
print("Bem-vindo ao F-Library!")
```
```php
//PHP
echo "Bem-vindo ao F-Library!";
```

Como você pode notar é só um texto entre aspas duplas dentro de uma "função" específica da linguagem, super simples, não? 🙂

Claro que existem algumas particularidades 🧐 como:
- Caracteres especiais 😨 (que podem não aparecer na tela, mas caso isso aconteça, normalmente colocar \ antes dele pode ser uma solução).
- Pular linha 😯 (você pode pular linhas nos seus textos, normalmente se usa \n, porém pode variar entre linguagens).

Mas no fim, escrever na tela é a ação mais básica que você pode realizar na programação. 😌

## Variáveis
Esse é um dos conceitos mais importantes de toda programação, você vai trabalhar com isso o tempo inteiro.

Variáveis são como "caixas" 📦, que precisam de:
- Um **nome** (para conseguirmos indentificar que caixa é essa).
- Um **tipo** (para sabermos que tipo de coisa podemos encontrar dentro dessa caixa).
- Um **conteúdo** (a caixa é um local que pode ser guardado coisas, enão ela sempre tem um centeúdo, mesmo que ele seja "nada").

Ok, mas para que serve uma variável? 🤨
- Guardar informações em seu conteúdo (como: nome, e-mail, senha, algum número para uma conta, idade, cpf etc.).
- Elas economizam tempo (quando você usa o nome de uma variável, na hora que o programa é executado esse nome é substituido pelo valor da variável, assim te evita de escrever esse conteúdo em várias partes do código, e se você precisar mudar esse conteúdo, mudar na variáveil muda automaticamente em todos os pontos que tiverem o nome dela).
- Poder tratar dados (guardando informações num variável, você pode modificar essas informações de diversas formas).

Regras básicas sobre nomes de variáveis ✍️:
- Só podem conter letras, números e sublinahado ( _ ).
- Não pode começar por números.
- Normalmente não pode ter acentos, embora algumas linguagens aceitem (mesmo assim evite usar).

Tipos mais comuns 🗒️:
- `boolean`: Verdadeiro ou falso (basicamente um binário de 0 ou 1).
- `char`: Caractere único (tipo uma única letra).
- `string`: Texto.
- `int`: Número inteiro.
- `double` ou `float`: Número racional (quebrado, com vírgula).

Pode aparentar ser meio confuso e difícil 😵‍💫, mas na prática é mais simples do que parece.

### Exemplos
Veja alguns exemplos de uma variável do tipo texto, com nome `minhaVariavelF`, onde seu conteúdo é "F Library é a melhor!":
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

Obs. se você prestou atenção nos exemplos percebeu que:
- A linguagem `C` não tem o tipo `string` 💀 (mas uma gambiarra resolve).
- A linguagem `C`, `C#` e `Java` são **estaticamente tipadas** 🗿 (para declarar uma variáveis precisa definir o tipo).
- A linguagem `Python` e `PHP` são **dinamicamente tipadas** 🪄 (a linguagem reconhece sozinha qual o tipo da variável).
  
## Inputs


## Condição


## Loop


## Arrays


## Função e Método


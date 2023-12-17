# ⌨️ Console (ler)
## ✨ Introdução
É essencialmente uma continuação da página "[✒️ Console (escrever)](escrever-console.md)".
> Se ainda não viu, vai ver, vacilãum! ☹️.

## 🪄 Explicação
### Ler entradas no Console
No contexto de um ***console***, "ler uma entrada" é basicamente **captar uma entrada de dados**, comumente pelo teclado.

A forma mais comum de leitura de entrada, é a "leitura de linha", onde o console te deixa digitar tudo que você quiser, até que a tecla ***enter*** seja pressionada.
> Só escrever abobrinhas e depois clicar no ENTER? 🤔 <br/>
> Hmmm... acho que entendi 😎👍... espero 😥

Talvez com um exemplo fique mais claro, mas dessa vez num formato de exercício.

### Exemplo
Um programa que:
- Peça o nome do usuário;
- Leia a entrada do nome;
- Diga "Bem-vindo(a), ", só que usando o nome lido.

```c
//C
char nome[100] = "\0"; //Em C, você tem que definir a variável antes, e com um tamanho
printf("Digite seu nome: ");
scanf("%[^\n]", &nome); //Leitura de entrada
printf("Bem-vindo(a), %s!", nome);
```
```csharp
//C#
Console.WriteLine ("Digite seu nome: ");
string nome = Console.ReadLine(); //Leitura de entrada
Console.WriteLine($"Bem-vindo(a), {nome}!");
```
```java
//Java
Scanner scan = new Scanner(System.in); //Scanner de leitura do Java
System.out.println("Digite seu nome: ");
String nome = scan.nextLine(); //Leitura de entrada
System.out.println("Bem-vindo(a), " + nome + "!");
```
```js
//JavaScript
let nome = prompt("Digite seu nome: "); //Leitura de entrada
console.log(`Bem-vindo(a), ${nome}!`);
```
```python
#Python
nome = input("Digite seu nome: ") #Leitura de entrada
print(f"Bem-vindo(a), {nome}!")
```
```php
//PHP
echo "Digite seu nome: ";
$nome = fgets(STDIN); //Leitura de entrada
$nome = rtrim($nome, "\r\n"); //Remove uma quebra no final
echo "Bem-vindo(a), {$nome}!";
```
Obs. Dessa vez você deve ter percebido que
- Cada linguagem tem **sua própria maneira de ler uma entrada de texto**, precisando até mesmo de coisas mais específicas da linguagem.
- Mesmo com toda essa diferença, elas ainda conseguem ser parecidas, tendo:
  - Uma **função específica para ler** uma linha de texto.
  - Precisam armazenar o resultado numa **variável de texto**.
> Vish... não tem jeito... 😶 <br/>
> Vou precisar virar Uber 🥲

Enquanto estiver estudando lógica de programação ou até mesmo POO, te recomendaria decorar a forma que a sua linguagem lê uma linha de texto, mas não se preocupe, quando começar a programar profissionalmente, praticamente nunca vai precisar usar esse tipo de recurso (o console no geral), no máximo raramente escrever na tela.
> Pelo menos alguma notícia boa na minha vida sofrida, completamente desprovida de sorte e sossego 🤕

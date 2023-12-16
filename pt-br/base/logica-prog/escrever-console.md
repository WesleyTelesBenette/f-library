# ✒️ Escrever na tela (console)
## Introdução
Quando se trata de programação, normalmente não é interessante criar um amontado de código se você **não consegue ver** o que está acontecendo e nem **iteragir com nada**.
> Óbvio que não é o que você quer 🫵😠... p-pelo menos é o que eu acho 😥.

Muitas linguagens são direcionadas a vários fins, como:
- 📱 Apps de celular.
- 🌐 Sites.
- 🖥️ Aplicativos de computador  etc.

Logicamente indica que você poderia sim "escrever na tela" usando a tecnologia específica da sua linguagem de escolha, porém todas as linguagens possuem a capacidade de serem executadas num ***console***.
> Uma telinha preta cheia dos código 👩‍💻, parecida com aquelas de filme de Hacker mesmo 💀.

O que vai deixar todas as páginas de documetação e exemplos, **bem mais genéricas** e simples de serem entendidas.
> Ou seja, vai ser fácil a ponto de qualquer Neandertal 🦖 ~~igual você~~ entender.

## Explicação
Tudo bem, vamo logo para o código, já devo ter te entediado com tantos contextos e justificativas.

Para exibir algo na tela (do console), normalmente **os comandos são simples e diretos**.

### Exemplo
Escrevendo a frase "Bem-vindo ao F-Library!":
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
```js
//Javascript
console.log("Bem-vindo ao F-Library!");
```
```python
#Python
print("Bem-vindo ao F-Library!")
```
```php
//PHP
echo "Bem-vindo ao F-Library!";
```

Como você pode notar é só um texto entre aspas duplas dentro de uma "função" específica da linguagem, se olhar com bastante atenção vai perceber que todas as linguagens escrevem no console de uma forma bem parecida.

Simples, não?

### Particularidades

Claro que existem alguns detalhes a mais para se preocupar, como:
- **Caracteres especiais**: que podem não aparecer na tela, mas caso isso aconteça, normalmente colocar **\\** antes dele pode ser uma solução.
- **Pular linha**: você pode pular linhas nos seus textos, normalmente se usa **\n**, porém pode variar entre linguagens.
- Dentre outras...

Mas no fim, escrever na tela é a **ação mais básica que você pode realizar na programação**, e que definitivamente você **DEVE** saber fazer isso pelo menos em todas as linguagens que você mais utiliza.
> Ou você simplesmente tem um "Celta, 2008, 4 portas, vermelho 🚗" ao invés de um cérebro digno de um ser humano.

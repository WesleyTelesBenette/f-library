# Lógica de Programação - C#

## ✨ Visão Geral

### Console
```csharp
//Escrever na tela
Console.WhiteLine("Hello, F Library!");

//Ler input (teclado)
string inputTec = Console.ReadLine();
```

### Variáveis
```csharp
//Boolean | true ou false | 1 byte
bool varBool = true;

//Char | caracteres | 2 bytes
char varChar = 'F';

//String | texto | (2 bytes * lenght) < RAM
string varString = "Fernanda";

//Byte | 0 a 255 | 1 byte
byte varByte = 8;

//SByte | -128 a 127 | 1 byte
sbyte varSByte = -8;

//Short | -32768 a 32767 | 2 bytes
short varShrot = -513;

//UShort | 0 a 65535  | 2 bytes
ushort varUShort = 513;

//Int | -2*(10^9) a 2*(10^9) | 4 bytes
int varInt = -50000;

//UInt | 0 a 4*(10^9) | 4 bytes
uint varUInt = 50000;

//Long | -9*(10^18) a 9*(10^18) | 8 bytes
long varLong = -516515618798L;

//ULong | 0 a 1*(10^19) | 8 bytes
ulong varULong = 516515618798;

//Float | 10^38 | 4 bytes
float varFloat = 14564.25f;

//Double | 10^308  | 8 bytes
double varDouble = 55616516.5587;

//Decimal | 1/(10^28) | 16 bytes
decimal varDecimal = 2.214516516516516516556;
```

### Condição
```csharp
//if-else
if (varQualquer == 8) //Se
{ 
    //Código...
}
else //Se não
{ 
    //Código...
}
```

### Operadores Lógicos
| Operador | Descrição |
| - | - |
| == | Igual |
| != | Diferente |
| > | Maior |
| < | Menor |
| >= | Maior ou igual |
| <= | Menor ou igual |
| && | E |
| \|\| | OU |

### Múltiplas Condições de Igualdade
```csharp
//switch-case
switch (var)
{
    case(valor1): //Case -> var == valor1
        //Código...
        break;

    case(valor2): //Case -> var == valor1
        //Código...
        break;

    default: //var != todos os cases
        //Código...
}
```

### Laços de Repetição
```csharp
//Loop simples
while (condição)
{
    //Código...
}


//Loop com primeira execução garantida
do
{
    //Código...
}
while (condição);


//Loop composto
for (declaração; condição; incremento)
{
    //Código...
}
```

### Array
```csharp
//Array
string[] listaDeNomes = new string[3];
listaDeNomes[0] = "Fernanda";
listaDeNomes[1] = "Wesley";
listaDeNomes[2] = "Tiago";

//Array atribuição na declaração
string[] diasSemana = new string[7] {
    "Domingo", "Segunda", "Terça", "Quarta", "Quinta", "Sexta", "Sábado"
};
```

### Matriz
```csharp
//Matriz
string[,] listaPessoas = new string[2,2];

listaPessoas[0,0] = "Fernanda";
listaPessoas[0,1] = "Design";

listaPessoas[1,0] = "Wesley";
listaPessoas[1,1] = "Dev Backend";

listaPessoas[2,0] = "Tiago";
listaPessoas[2,1] = "Dev Fullstack";
```

### Método e Função
```csharp
//Método
void nomeMetodo(parâmetros)
{
    //Código...
}

//Função
string nomeFuncao(parâmetros)
{
    //Código...
    return "Retorno";
}
```

## 🪄 Exemplo Prático
 
## 🗃️ Material Adicional
- Links...

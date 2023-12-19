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
if (varQualquer == 8)
{
    //Código...
}
else
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
switch (var)
{
    case(valor1):
        //Código...
        break;

    case(valor2):
        //Código...
        break;

    default:
        //Código...
}
```

### Laços de Repetição
```csharp
while (condição)
{
    //Código...
}


do
{
    //Código...
}
while (condição);


for (declaração; condição; incremento)
{
    //Código...
}

```


## 🪄 Exemplo Prático
 
## 🗃️ Material Adicional
- Links...

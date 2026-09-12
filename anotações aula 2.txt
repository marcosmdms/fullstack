aula 2

1. Tipagem Dinâmica vs Tipagem Estática
JS -> Dinâmica
Exemplo:
let valor = 10;
valor = "Olá";
valor = true;

TS -> Estática

Exemplo:
let valor: number = 10;

valor = 20;      // ✅
valor = "Olá";   // ❌ erro


2. união (uso do | para adicionais mais tipos)
3. Inferencia: implicita ou explicita
    **tranformar o que vem do prompt em number
    ** typeof (mostra qual  o tipo da informação armazenada ou recebida)
4. Concatenação de texto (string + variavel)
5. Operadores:
 - aritimeticos (+,-,*, /, %)
_________
 % - modulo ou rest ( divide o numero da esquerda pelo da direita e mostra o resto da divisão)
é utilizado para saber se é par ou importante
se restar 0 é par
se diferente de 0 é impar
________
    
    ** coerção implicita -> alert('30'-5) -> 25
    ** coerção explicita -> (number, string, boolean)
        number ('30')
        String (false)
        boolean('true')
________
 - comparação ( >, <, >=, <=, ==, ===)
    ** == (comparação) -> compara somente valores
    ** === (comparação extricta) -> compara valor e tipo
    ** Dica do professor: usar sempre o (===) para fazer as comparações
____________
 - atribuição ()
    Exemplo:
    let x = 10;
    x += 5;  // 15
    x -= 3;  // 12
    x *= 2;  // 24
    x /= 4;  // 6
    x %= 4;  // 2 (nao foi abordado pelo professor)
    x **= 3; // 8 (nao foi abordado pelo professor)
-----------Existem também operadores de atribuição bit a bit (nao foi abordado pelo professor)
    &=
    |=
    ^=
    <<=
    >>=
    >>>=
-------- operadores de atribuição lógica: (nao foi abordado pelo professor)
    &&= 
    ||=
    ??=
____________
 - lógicos (&& (and), || (or), ! (not))

Expressão booleana
 const expression = true ? 'é verdade' : 'é mentira'; (equivale ao elseIf)
    -> ? - equivale ao SE (if)
    -> : - equivale ao SENÂO (else)

________

Estruturas condicionais
 - Estrutura de controle de fluxo (decisão)
    ** se sim / se não
if (){}

_______________
** O que o JS considera verdade ou mentira **

thuthy (tudo que for diferente de mentira, é verdade)
falsy (" " (string vazia), null, false,0, undefined)

_____________________________________


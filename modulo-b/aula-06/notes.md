### Tratamento de dados

(number + number) + para adição
(string + string) + para concatenação

Number.parseInt(n) -> Números inteiros
Number.parseFloat(n) -> Números reais
Number(n) -> Decide sozinho

String(n) -> String
n.toString() -> String

Formas de concatenação:
window.alert("A soma dos dois números é: " + String(soma));
window.alert(`A soma dos dois números é: ${String(soma)}.`);

Formatação de string
s.length -> quantos caracteres a string tem
s.toUpperCase() -> tudo para 'MAIÚSCULAS'
s.toLowerCase() -> tudo para 'minúsculas'

Formatação de number
n.toFixed(2) -> com duas casas decimais
n.toFixed(2).replace('.', ',') -> com duas casas decimais, substituindo "." por ","
n.toLocaleString('pt-br', {style:'currency', currency: 'BRL'})
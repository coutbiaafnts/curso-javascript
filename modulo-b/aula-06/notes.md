### Tratamento de dados

(number + number) + para adição<br>
(string + string) + para concatenação<br>

Number.parseInt(n) -> Números inteiros<br>
Number.parseFloat(n) -> Números reais<br>
Number(n) -> Decide sozinho<br>

String(n) -> String<br>
n.toString() -> String<br>

Formas de concatenação:<br>
window.alert("A soma dos dois números é: " + String(soma));<br>
window.alert(`A soma dos dois números é: ${String(soma)}.`);<br>

Formatação de string<br>
s.length -> quantos caracteres a string tem<br>
s.toUpperCase() -> tudo para 'MAIÚSCULAS'<br>
s.toLowerCase() -> tudo para 'minúsculas'<br>

Formatação de number<br>
n.toFixed(2) -> com duas casas decimais<br>
n.toFixed(2).replace('.', ',') -> com duas casas decimais, substituindo "." por ","<br>
n.toLocaleString('pt-br', {style:'currency', currency: 'BRL'})<br>
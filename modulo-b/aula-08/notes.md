# Operadores (parte 02)

> Precedência:  Aritméticos -> Relacionais -> Lógicos -> Ternário

## Relacionais

- 5 `>` 2 -> true
- 7 `<` 4 -> false
- 8 `>=` 8 -> true
- 9 `<=` 7 -> false
- 5 `==` 5 -> true
- 4 `!=` 4 -> false
- 5 `===` "5" -> false (valores idênticos) 

> O resultado de expressões relacionais sempre devolve um valor booliano (boolean)

## Lógicos

- `!` -> negação
- `&&` -> conjunção
- `||` -> disjunção

> Precedência: Negação -> Conjunção -> Disjunção

### Negação "!"

- Operador unário -> Possui somente `um` operando

> ! true -> false<br>
> ! false -> true<br>

### Conjunção "&&"

- Operador binário -> Possui `dois` operadores lógicos, um de cada lado

> true && true -> true<br>
> true && false -> false<br>
> false && true -> false<br>
> false && false -> false<br>

### Disjunção "||"

- Operador binário -> Possui `dois` operadores lógicos, um de cada lado

> true || true -> true<br>
> true || false -> true<br>
> false || true -> true<br>
> false || false -> false<br>

## Ternário

> teste `?` true `:` false<br>
> média >= 7.0 `?` 'Aprovado' `:`  'Reprovado'<br>

 

## Exemplos

> `idade >= 15 && idade <= 7` -> (A idade está entre 15 e 17?)<br>
> `estado == 'RJ' || estado == 'SP'` -> (O estado é RJ ou SP?)<br>
> `salário > 1500 && sexo != 'M'` -> (É uma mulher que recebe mais que 1500?)
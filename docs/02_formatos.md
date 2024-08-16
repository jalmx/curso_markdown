# Formatos

Tenemos diferentes símbolos para dar los formatos de manera nativa:

- Negrita
- Cursiva o itálica
- Cita

## Negritas

Para negritas se debe colocar "doble asterisco al inicio y al final del la palabra o frase", `**TEXTO**`, ==*sin espacios*==.
Otra opción para especificar negritas es con "doble guion bajo al inicio y al final", `__TEXTO__`, ==*sin espacios*==.

**Ejemplo**:

```markdown
**PALABRA**

**Estoy aprendiendo la sintaxis de Markdown**

__PALABRA__

__Estoy aprendiendo la sintaxis de Markdown__
```
## Cursiva o Itálica

Para cursivas se debe colocar "un asterisco al inicio y al final del la palabra o frase", `*TEXTO*`, ==*sin espacios*==.
Otra opción para especificar cursivas es con "un guión bajo al inicio y al final", `_TEXTO_`, ==*sin espacios*==.

**Ejemplo**:

```markdown
*PALABRA*

*Estoy aprendiendo la sintaxis de Markdown*

_PALABRA_

_Estoy aprendiendo la sintaxis de Markdown_
```

## Cita

La cita me sirve para resaltar alguna frase o mención. 
Se utiliza el símbolo de mayor que `>`.

**Ejemplo**:

```markdown
> Esto es una cita
```

Se pueden colocar citas dentro de citas.

**Ejemplo**:

```markdown
>> Esto es una cita

>>> Esto es una cita
```

## Tachado (`~`)

Para tachar se debe colocar "doble `virgulilla` al inicio y al final del la palabra o frase", `~~TEXTO~~`, ==*sin espacios*==.

**Ejemplo**:

```markdown
~~PALABRA~~

~~Esto es una frase~~
```

**Resultado:**

~~PALABRA~~

~~Esto es una frase~~

## Resaltado (Highlight)

Esto es equivalente a aplicar **marcatexto**.
La sintaxis es colocando doble *signo de igual, sin espacio, al inicio al final* de la palabra o frase.

```markdown
==WORD==

==THIS IS A PARAGRAPH==
```

**Resultado:**

==WORD==

==THIS IS A PARAGRAPH==


> 📝 ***Nota:** Esta sintaxis es extendido de `markdown`. No siempre funciona.*

Si no funciona, se usa `HTML`. Ejemplo:

```html
<mark>WORD</mark>
<mark>THIS IS A PARAGRAPH</mark>
```

<mark>WORD</mark>
<mark>THIS IS A PARAGRAPH</mark>

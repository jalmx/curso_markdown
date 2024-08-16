# Otros

## Separador

Un separador es una linea horizontal que abarca todo el ancho.
La sintaxis son con 3 símbolos, estos pueden ser:

- guion medio: `---`
- asterisco: `***`
- guion bajo: `___`

**Ejemplo:**

```
Texto

---

Texto
```

**Resultado:**

Texto

---

Texto


## Código

Markdown soporta tener bloques o secciones con código de programación, al estilo de un editor de código.

### Bloque de código

La sintaxis es colocar al inicio del bloque 3 backticks (\```), seguido del lenguaje de programación del código escrito, y cierra con otros 3 backticks (\```). 

**Ejemplo:**


```c
int main(){
    return 0;
}
```

```markdown
# Título

Sint deserunt ex occaecat aute est proident officia labore occaecat nostrud eu sunt...
```

> 📝 ***Nota:** En caso de **NO** indicar un lenguaje no hará el resaltado del código.*

> *:warning: El editor no sabe si esta bien escrito el lenguaje que estas especificando.*

### Código en línea

La sintaxis es colocar al inicio del un backtick (\`), seguido del código, y cierra con otro backtick (\`). 

**Ejemplo:**

```markdown

`int value = 3`

```

**Resultado:**

`int value = 3`

## Sub y Sup

### Super índice

Para se colocan al inicio un acento circunflejo `^` y al final cierra con otro cento circunflejo, sin dejar espacio.

Ejemplo:

```markdown
x^2^
```

**Resultado:**

x^2^

### Sub índice

Para se colocan al inicio un virgulilla `~` y al final cierra con otro virgulilla, sin dejar espacio.

Ejemplo:

```markdown
x~2~
```

**Resultado:**

x~2~

## Romper una línea

Dolor consequat voluptate magna officia deserunt velit enim veniam occaecat cillum adipisicing. <br> Ad eu Lorem quis aute aliqua ex magna in est amet. Ipsum Lorem ea magna ex adipisicing consequat dolore officia nulla aute velit.
Mollit occaecat ullamco esse Lorem magna in anim adipisicing aliqua incididunt irure elit.

- cosa 1
- cosa 2 <br>cosa 2.1
- cosa 3
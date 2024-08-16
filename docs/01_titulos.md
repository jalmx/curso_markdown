---
title: Títulos y subtítulos en markdown
description: Se dan especificaciones, formato y sintaxis del uso de títulos y subtítulos
author: Yo merengues!
date: '2024-08-14'
---

# Títulos y subtítulos en markdown 🤡

Para colocar títulos y subtítulos en `markdown` se ocupa en *hash* `#`, al **INICIO DE LA LÍNEA**.

- Titulo -> `#`
- Subtitulo -> `##`
- Sub-subtitulo -> `###`
- Tenemos hasta 6 niveles de subtítulos -> `######` 

> *Después, del hash va un espacio*

## Recomendaciones de los titulo y subtítulos

- Solo debe haber un titulo por archivo
- Después del titulo, debe ir un subtitulo, es decir; no puede haber sub-subtitulo entre titulo y subtitulo.
    ```markdown
    # titulo

    texto .....

    ### esto no debe ir aquí

    ## Subtitulo
    ```

```mermaid
mindmap
  root((mindmap))
    Origins
      Long history
      ::icon(fa fa-book)
      Popularisation
        British popular psychology author Tony Buzan
    Research
      On effectiveness<br/>and features
      On Automatic creation
        Uses
            Creative techniques
            Strategic planning
            Argument mapping
    Tools
      Pen and paper
      Mermaid
```

```mermaid
%%{init: {"pie": {"textPosition": 0.5}, "themeVariables": {"pieOuterStrokeWidth": "5px"}} }%%
pie showData
    title Key elements in Product X
    "Calcium" : 42.96
    "Potassium" : 50.05
    "Magnesium" : 10.01
    "Iron" :  5

```
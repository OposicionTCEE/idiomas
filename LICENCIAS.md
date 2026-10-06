# Licencias y atribuciones

Este paquete reúne material propio y material abierto de terceros, que se cita en cada ficha (campo `fuente` y, en cada ejercicio
tomado de Tatoeba, campo `origen`).

| Material | Autoría | Licencia | Dónde |
|---|---|---|---|
| Explicaciones y ejemplos adaptados de *Tex's French Grammar* | Center for Open Educational Resources and Language Learning (COERLL), Universidad de Texas en Austin — https://laits.utexas.edu/tex/ | CC BY 3.0 (https://creativecommons.org/licenses/by/3.0/) | fichas de gramática francesa con `fuente.nombre` = «Tex's French Grammar». Se han traducido al español, resumido y ampliado. |
| Frases de ejemplo y de ejercicios | Colaboradores de Tatoeba — https://tatoeba.org | CC BY 2.0 FR (https://creativecommons.org/licenses/by/2.0/fr/) | ejercicios con `origen` = `tatoeba:<id>` (la frase original está en https://tatoeba.org/es/sentences/show/<id>). Algunas se han adaptado ligeramente. |
| Índice de materias | Inspirado en el *Core Inventory for General English* (British Council–EAQUALS) y el *Inventaire linguistique des contenus clés des niveaux du CECRL* (Eaquals–CIEP) | Solo se ha usado como guía de qué tratar en cada nivel; los textos son propios | `materias.json` |
| Resto de fichas, explicaciones y ejercicios | Elaboración propia para el Panel TCEE | CC BY-SA 4.0 | fichas con `fuente.nombre` = «propia» |

Uso no comercial, para preparar la oposición.

## Títulos en la lengua estudiada (`*/titulos.json`)

Redacción propia (CC BY-SA 4.0). En inglés, el campo `oficial` cita el rótulo de la materia en el *Core Inventory for General English*
(British Council–EAQUALS, 2010/2015) y, en francés, el del *Inventaire linguistique des contenus clés des niveaux du CECRL*
(Eaquals–CIEP, 2015), solo como referencia de índice; no se copia ningún otro texto de esas obras.

## Diccionarios bilingües (`fr/diccionario.json`, `en/diccionario.json`)

Datos de **Wiktionary** (Wikcionario en español y Wiktionnaire en francés), extraídos con *wiktextract* y publicados por
[kaikki.org](https://kaikki.org/) (Tatu Ylonen). Licencia: **CC BY-SA 4.0** y GFDL, autores de Wiktionary.
Se generan con `main/scripts/idiomas/diccionario.py`; solo se conservan la palabra, su categoría, la pronunciación (AFI),
las traducciones al español y hasta cinco definiciones en español.

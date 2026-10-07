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
las traducciones al español y hasta cinco definiciones en español; en francés, para unas 2.900 palabras frecuentes (vocabulario de FLELex) sin traducción en Wiktionary, hasta tres definiciones en francés, marcadas «(fr)».

## Verbos franceses (`fr/verbos.json`) y fichas de conjugación (`fr/conjugacion/`)

- `fr/verbos.json`: lista de 7.015 verbos y sus 149 modelos de conjugación de **Verbiste** (© 2003-2016 Pierre Sarrazin,
  <http://sarrazip.com/dev/verbiste.html>), licencia **GNU GPL versión 2 o posterior**, tal como la distribuye mlconjug3.
  Se ha cambiado el formato (JSON) y se ha corregido el participio de pouvoir («pu», invariable). La frecuencia de cada verbo se ha contado
  en las frases francesas de Tatoeba (CC BY 2.0 FR). Generado con `main/scripts/idiomas/verbos.py`.
- `fr/conjugacion/*.json`: fichas de consulta de redacción propia (CC BY-SA 4.0); sus tablas se generaron y comprobaron con Verbiste.

## Biblioteca de textos (`*/textos/`, `*/textos.json`)

Cada texto lleva su fuente, URL, autoría y licencia en el campo `fuente`. Los textos se han recortado por párrafos sin cambiar las frases.

| Fuente | Licencia |
|---|---|
| Wikipedia (inglés y francés), Simple English Wikipedia — colaboradores de cada artículo (ver `fuente.url`, historial del artículo) | CC BY-SA 4.0 |
| Vikidia — colaboradores de Vikidia | CC BY-SA 3.0 |
| Wikinews (inglés y francés) — colaboradores de Wikinews | CC BY 2.5 |
| VOA Learning English (Voice of America, gobierno de EE. UU.); el audio se enlaza, no se copia | Dominio público |
| Artículos `prensa-*`: escritos para el panel por Claude (Anthropic); datos aproximados, no citables | CC0 |

El material de cada texto (ideas clave, resumen modelo, preguntas, preguntas de tribunal y glosario) es de elaboración propia (CC BY-SA 4.0).

## Escritura, tribunal y expresiones (`*/escritura.json`, `*/tribunal.json`, `*/expresiones.json`)

Elaboración propia para el Panel TCEE (CC BY-SA 4.0).

# Idiomas · paquete de contenido del Panel TCEE

Contenido de la pestaña **Idiomas** del Panel Oposición (inglés y francés, de A1 a C2). Lo descarga y actualiza la tarea *Sincronizar*.
Los datos de cada usuario (progreso, errores, escritos, grabaciones) **no** están aquí: se guardan solo en su Mac, en `TCEE/idiomas-<nombre>/`.

Diseño, formato y reglas: `main/IDIOMAS.md`. Programas que fabrican este paquete: `main/scripts/idiomas/`.

```
<lengua>/materias.json      índice de materias A1→C2 (gramática, léxico, fonética, destrezas); los id no cambian nunca
<lengua>/fichas/<id>.json   ficha: explicación en español, ejemplos, errores típicos de hispanohablantes y ejercicios de respuesta fija
```

Atribuciones y licencias: `LICENCIAS.md`.

## Fases 2–3 (7/10/2026)

- `<l>/textos.json` y `<l>/textos/`: biblioteca para leer y resumir, escuchar y resumir, preguntas, dictado, exposición y tribunal
  (generada con `main/scripts/idiomas/textos.py`; reglas en `main/IDIOMAS.md`, «Fases 2–3»).
- `<l>/escritura.json`: tareas de expresión escrita. `<l>/tribunal.json`: preguntas generales del tribunal. `<l>/expresiones.json`: banco de expresiones por función.

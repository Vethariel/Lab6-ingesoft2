# Laboratorio 6: Testing

Pruebas unitarias e integración, TDD, cobertura y calidad. Ingeniería de Software II (2016702), Universidad Nacional de Colombia, 2026-II.

## Qué hay en el repositorio

| Ruta | Qué es |
| --- | --- |
| [docs/informe.pdf](docs/informe.pdf) | El informe, con las evidencias E1 a E20 |
| [Prestamos-00/](Prestamos-00/) | El proyecto Maven del préstamo de equipos, con sus pruebas. Su [README](Prestamos-00/README.md) tiene el stack y los comandos para ejecutar las pruebas y la cobertura |

## Informe

La fuente está en [latex/main.tex](latex/main.tex) y se compila con LuaLaTeX. El PDF queda en [docs/informe.pdf](docs/informe.pdf):

```bash
cd latex
latexmk
```

Las capturas van en `latex/capturas/`. Mientras falta una, el PDF muestra un recuadro con su nombre. latexmk no detecta que llegó una captura nueva, así que en ese caso hay que forzar la compilación con `latexmk -g`.

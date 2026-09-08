# Segundo Overleaf de la tesis (v2)

Copia de la tesis en plantilla UCM con la introducción reescrita para
incorporar la contribución de la distribución latido a latido y su exponente
de escalamiento.

## Qué cambió respecto del repositorio original

- `05-intro.tex` — nueva subsección «La dimensión que falta: el tiempo entre
  latidos», con el estado del arte de las dos familias de generadores, los
  valores de referencia del exponente y la precisión de nomenclatura entre
  $\alpha$ y $H$. Hipótesis ampliada con una segunda proposición verificable.
  Nuevo objetivo específico 6 sobre el módulo de ritmo. Alcance actualizado:
  la secuencia R-R entra al alcance y la ventana pasa a ser asimétrica.
- `04-1resumen.tex` y `04-2abstract.tex` — párrafo nuevo con la contribución
  del ritmo y su criterio de validación.
- `biblio.bib` — ocho entradas nuevas, todas verificadas contra la fuente:
  Peng 1995, Hardstone 2012, Costa 2017, McSharry 2002, Moody 2002,
  Clifford 2002, Davey 1999 y la base nsr2db de PhysioNet.
- `fig/` — se agregan `validacion_visual_v2.png` y `validacion_hurst.png`.

## Cómo subirlo a Overleaf

Opción simple: en Overleaf, **New Project → Upload Project**, y subir esta
carpeta comprimida en zip.

Opción con sincronización: crear un repositorio nuevo en GitHub, subir esta
carpeta, y en Overleaf usar **New Project → Import from GitHub**. Así queda con
el mismo flujo que el repositorio actual.

## Estado por sección

Escrito y compilando (64 páginas, sin errores ni citas indefinidas):

- `05-intro.tex` — subsección nueva «La dimensión que falta: el tiempo entre
  latidos», hipótesis ampliada, objetivo específico 6, alcance actualizado.
- `06-marco_teorico.tex` — subsección nueva «Dinámica latido a latido y
  correlaciones de largo alcance»: del ideal homeostático a la dinámica
  fractal, el DFA, la distinción entre alfa y H, y los valores de referencia.
- `07-estado_del_arte.tex` — reescrito. Pasa de dos paradigmas a tres,
  incorporando la línea de generación de tacogramas y el desafío de 2002, y
  cierra con la síntesis de la brecha.
- `08-metodos.tex` — sección nueva del módulo de ritmo: síntesis espectral,
  medición por DFA, acoplamiento selectivo en el tiempo y criterio de
  validación.
- `09-resultados.tex` — métricas actualizadas a la ventana asimétrica, cuadro
  de tres iteraciones, efecto de la redefinición de la ventana, las tres
  hipótesis rechazadas sobre la onda T, y la sección del módulo de ritmo con
  su cuadro de sesgo y la cohorte. Las dos figuras insertadas.
- `10-conclusion.tex` — objetivos actualizados, conclusión nueva sobre el
  control verificable de la dinámica, y trabajos futuros reemplazados.

## Lo que falta

- **Marco referencial empírico.** Hay una indicación del profesor, conservada
  como comentario al final de `07-estado_del_arte.tex`, que pide describir los
  resultados en escala internacional, latinoamericana y nacional, tensionar la
  evidencia e integrarla en una conclusión. Las tres líneas mapeadas son todas
  de escala internacional: falta la búsqueda regional y nacional.
- **Portada y comisión** siguen con los marcadores de la plantilla: nombre del
  director, título definitivo y miembros de la comisión.
- **Calibración externa del módulo de ritmo** contra la base nsr2db de
  PhysioNet, que requiere descargarla.

# MVP y user flow

Versión mínima de Mi_Recetario y recorrido de una persona por ella. Parte de lo que contaron P1 y P2 en las entrevistas y de los nombres de pantalla del sitemap.

## MVP

### Entra en el MVP

- **Almacén:** ver qué alimentos hay en casa.
  - Por qué: P1 depende de la memoria o de mirar el frigorífico y ha comprado cosas que ya tenía. P2 recorre los muebles con una hoja y un boli.
- **Caducidad (avisa):** aviso de lo que caduca pronto.
  - Por qué: tanto a P1 como a P2 se le han puesto algún alimento malo.
- **Apuntar recetas con sus modificaciones.**
  - Por qué: P1 las apunta en un cuaderno con flechas entre versiones. P2 las tiene de memoria y no apunta los cambios, así que apuntarlas tiene que ser rápido para que P2 quiera utilizarlo.

### Se queda fuera

- **Foto del ticket:** es difícil de implementar, por lo que mientras tanto, se añade a mano.
- **Planificador semanal:** P1 y P2 deciden sobre la marcha, así que no necesitan nada para planificar.
- **Lista de la compra automática:** no es algo primordial, con el almacén ya ves lo que tienes.
- **Cuenta y compartir por QR:** no es algo que ninguna halla mencionado.
- **Narración y temporizador:** no sale de ninguna entrevista.


## User flow del MVP: almacén, caducidad y recetas

Una persona al abrir Mi_Recetario en el móvil, en casa, añade alimentos, ve lo que caduca pronto y guarda recetas con sus cambios.

**Leyenda:** óvalo = inicio o fin · rectángulo = pantalla · rombo = decisión.

**Punto de entrada:** Despensa.

### Notas del flujo

- **Añadir alimento:** si falta algún dato, se vuelve a la pantalla antes de guardar. Así no se guardan alimentos a medias.
- **CADUCAN PRONTO:** ordena lo que caduca antes. Responde a lo que repiten P1 y P2: no saben cuándo se les echa a perder la comida.
- **Añadir receta, ¿es una modificación de otra?:** si lo es, se elige la receta base y se guarda solo lo que cambia. P1 usa flechas entre versiones y P2 cambia recetas sin apuntarlas.
- **Error al guardar:** se puede reintentar o volver a la pantalla anterior sin perder lo escrito. Pensado para P2, que no apunta nada si apuntar es pesado.
- **Alimento añadido:** confirma que se ha guardado y lleva de vuelta al ALMACÉN.

### Recorrido desde cada persona

- **P1:** encuentra lo que caduca sin poner los productos abiertos delante del frigorífico y conserva las versiones de sus recetas.
- **P2:** apunta lo que tiene sin hoja y boli y guarda una receta en pocos pasos.

### Decisiones pendientes

- ¿Dónde se añade la modificación de una receta?
- ¿Con cuántos días de antelación se avisa por defecto de lo que caduca?
- ¿Qué pasa con un alimento sin fecha de caducidad?

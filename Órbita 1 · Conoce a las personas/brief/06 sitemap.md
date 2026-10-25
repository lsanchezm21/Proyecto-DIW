# Sitemap

Estructura de Mi_Recetario: qué pantallas hay, cómo se agrupan y cómo se llaman. Parte del MVP y del user flow.

## Mapa

```
Despensa (inicio)
├── Añadir alimento
├── Recetas
│   ├── Detalle de receta
│   └── Añadir receta
└── Caducan pronto
```

## Pantallas de sistema

No forman parte del menú. Aparecen como respuesta a una acción:

- **Alimento añadido:** al guardar un alimento.
- **Error al guardar:** cuando falla el guardado.

## Inventario

De dónde sale cada pantalla:

- **Del MVP, despensa:** Despensa, Añadir alimento, Alimento añadido.
- **Del MVP, caducidad:** Caducan pronto.
- **Del MVP, recetas:** Recetas, Añadir receta, Detalle de receta.
- **Del user flow, casos límite:** Error al guardar.

## Tipos de pantalla

- **Principales (menú):** Despensa, Recetas, Caducan pronto.
- **Secundarias:** Añadir alimento, Añadir receta, Detalle de receta.
- **De sistema:** Alimento añadido, Error al guardar.

## Decisiones

- El flujo empieza en la Despensa, porque lo primero que necesitan P1 y P2 es saber qué tienen en casa.
- Tiene 2 niveles de navegación. Todo el MVP se alcanza desde la Despensa en uno o dos toques.
- Caducan pronto tiene su propia pantalla en el primer nivel porque es el problema que tienen tanto P1 y P2.
- Las pantallas de sistema van aparte del árbol porque no se llega a ellas desde el menú.

# modulo-ligier-experience — Contexto de trabajo

## Qué es Ligier Experience
Evento anual de vinos premium de Vinoteca Ligier. Se desarrolla en el Salón Central
del Predio de La Rural. Nunca llamarlo "feria" — siempre "evento de vinos".

## Edición 8 — datos fijos
- Fecha: 20 de agosto de 2026
- Horario: 18:30 a 23:30
- Lugar: La Rural · Salón Central · Av. Sarmiento 2704, CABA
- Formato: cóctel · libre recorrido
- Capacidad: 600 invitados
- Bodegas: 30 seleccionadas — cosechas actuales, añadas anteriores y botellones
- Copa de cristal: obsequio de ingreso
- Novedad edición 8: sell out — los asistentes pueden comprar vinos durante el evento con envío postdatado a confirmar

## Tiers de bodegas

| Tier | Vinos | Staff | Observaciones |
|---|---|---|---|
| Black | hasta 10 (1 de 2014 o anterior) | 4 | Ubicación preferencial, stand de mayor dimensión |
| Gold | 5 (1 de 2014 o anterior) | 2–3 | Stand propio en recorrido general |
| Silver | hasta 3 | — | Stand compartido, servidos por sommeliers de Ligier. Opción de enviar sommelier propio |

La organización provee: copas, fajines, hielo, fraperas, agua y demás insumos operativos.

## Precios de entradas (valores actualizados junio 2026)

| Tipo | Precio por entrada | Incluye |
|---|---|---|
| Entrada general | $190.000 | Gift Card $40.000 |
| Pack 25 · 10% off | $135.000 | sin Gift Card |
| Pack 50 · 15% off | $127.500 | sin Gift Card |
| Pack 100 · 20% off | $120.000 | sin Gift Card |

Todos los valores incluyen IVA.
La Gift Card no es para consumir en el evento — el evento es all inclusive una vez adentro.
La Gift Card es para tienda online, futuras compras o eventos. Es opcional en packs corporativos y se puede agregar al momento del pago.

## Tu entrada incluye
- Copa de cristal (de regalo, para llevarse)
- Degustación sin límite de los 30 bodegas participantes
- Gastronomía completa en formato cóctel
- Agua y bebidas sin alcohol
- Descuentos especiales en compras de vino durante el evento
- Ligier Gift Card $40.000 (entrada general) / opcional (packs)

## Packs corporativos
Pensados para empresas que quieren agasajar clientes, cerrar vínculos con aliados
o hacer team building. Precio base desde $120.000 sin Gift Card.
Tres opciones: Pack 25 / Pack 50 / Pack 100.

## Páginas de producto producidas (Magento 2)
- Entrada general — short description en HTML ✓
- Pack corporativo 25 entradas — HTML ✓
- Pack corporativo 50 entradas — HTML ✓
- Pack corporativo 100 entradas — HTML ✓

## Design system aplicado (V2)
- Fuente: Helvetica Neue, max-width 680px
- Labels: 11px uppercase letter-spacing 2px color #b08850
- Valores/precios: color #b08850
- Bloques de precio: fondo #f5f0e8, flex justify-content space-between
- Separadores: 1px solid #e8e0d4
- Bloque informativo: fondo #faf7f2 padding 20px 24px
- Output HTML: siempre dentro de bloque ```html — nunca suelto en chat

## Estructura de product page (aprobada)
1. Párrafo introductorio
2. Cuadro 1 — fecha, horario, lugar, formato, capacidad
3. Cuadro 2 — precios (entrada general + 3 packs) con fondo cream
4. Nota sobre IVA y Gift Card
5. Cuadro 3 — "Tu entrada incluye" (labels dorados uppercase)
6. Bloque Gift Card (solo en entrada individual)

## Pendiente / próximos pasos
- Definir beneficios completos por tier de bodega (Black/Gold/Silver) para el paper de bodegas
- Paper de bodegas: texto de "¿Por qué participar?" aprobado, niveles definidos, requerimientos aprobados — falta cierre con tabla de beneficios diferenciados por tier

## Última actualización
Junio 2026

## Cómo usar este módulo en Claude
Pegá este README al inicio del chat y escribí:
"Continuamos con el módulo Ligier Experience. [tu consulta]"

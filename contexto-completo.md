# CONTEXTO COMPLETO — Vinoteca Ligier / Vinos Guardados
> Archivo generado automáticamente. Pegá esto al inicio de un chat en Claude para retomar el trabajo.
> Última generación: junio 2026

---


---
## ARCHIVO: README.md
---

# alan — Sistema de Módulos de Conocimiento

Repositorio de contexto, código y documentación para Vinoteca Ligier / Casa VG.
Cada módulo representa un área de trabajo. Para retomar una conversación en Claude,
pegá el README del módulo correspondiente al inicio del chat.

## Módulos

| Módulo | Descripción |
|---|---|
| [modulo-wine-club](./modulo-wine-club/) | VG Wine Club — tiers, curaduría, comunicación |
| [modulo-ligier-experience](./modulo-ligier-experience/) | Evento Ligier Experience — ediciones, bodegas, logística |
| [modulo-magento](./modulo-magento/) | Páginas de producto Magento 2 — HTML, design system V2 |
| [modulo-cenas-casavg](./modulo-cenas-casavg/) | Cenas Casa VG — estructura, copy, product pages |
| [modulo-coleccion-legado](./modulo-coleccion-legado/) | Colección Legado / Patrimonio — copy aspiracional |
| [modulo-general](./modulo-general/) | Comunicación, marca, misceláneos |

## Cómo usar
1. Abrí un chat nuevo en Claude.ai
2. Pegá el contenido del README del módulo que necesitás
3. Continuá desde donde quedaste

---
Última actualización: junio 2026


---
## ARCHIVO: modulo-wine-club/README.md
---

# VG Wine Club — Contexto de Trabajo
## Qué es
VG Wine Club es la vertical de suscripción de **Vinoteca Ligier / Vinos Guardados** (`vinotecaligier.com`, Magento 2). Cada mes el socio recibe 4 botellas seleccionadas por Alan Dayan directo desde su cava — vinos de distintas añadas, bodegas y estilos que ya no existen en el mercado.
- **Mes actual de operación:** Mes 24
- **Socios totales actuales:** ~142
- **Meta:** 1.000 socios
- **Curación y publicación:** manual, a cargo de Alan
- **Pago:** mensual (débito automático o pago mes a mes)
---
## Estructura de tiers
| Tier | Slogan | Precio/mes | Socios actuales |
|------|--------|-----------|-----------------|
| Silver | El primer paso dentro de la cava. | $160.000 | 70 |
| Gold | Ya sabés lo que buscás. | $330.000 | 40 |
| Platinum | Entendés lo que otros solo ven. | $470.000 | 18 |
| Black | No necesitás que te lo expliquen. | $750.000 | 14 |
| **X** *(sin nombre aún)* | *(pendiente)* | $1.500.000 | 0 |
Cada tier recibe **solo sus 4 botellas** — no acumula las de los tiers inferiores. El código interno incluye el número de mes (ej. `S24` = Silver mes 24).
---
## Perfiles de cada tier
**Silver** — El curioso que da su primer paso. Amante del vino en formación, más curioso que conocedor. Descubre cada mes que el tiempo hace al vino lo que ninguna etiqueta nueva puede tener.

**Gold** — Un curioso más atrevido. Ya probó suficiente como para querer ir más adentro. Empieza a entender que hay otro nivel.

**Platinum** — El conocedor. Ya cruzó la línea entre consumir y coleccionar. Entiende que una botella de 2002 no es solo vino — es un momento detenido en el tiempo.

**Black** — El que llegó. Conoce, colecciona, ya no necesita que le expliquen nada. Elige las etiquetas más raras de la cava con criterio propio.

**X** — No busca cantidad, busca acceso único. El vino es parte de su mundo cultural. Discreción total. Incluye un encuentro mensual en la cava con grupos de 6, con Alan. Las 4 botellas mensuales son la extensión física de esa noche.

> **Nota sobre edades:** El universo VG abarca principalmente personas de 25 a 50 años. El precio más alto no correlaciona con edad mayor.
---
## Tier X — Estado y definición
- **Precio:** $1.500.000/mes
- **Socios actuales:** 0 (en lanzamiento)
- **Diferencial exclusivo:** encuentro mensual presencial en la cava, en grupos de 6, con Alan Dayan
- **Nombre:** pendiente — debe ser aspiracional, orientado al coleccionismo, moderno, con referencias al universo Audemars Piguet (austero, seguro, no necesita explicarse)
- **Color:** pendiente
---
## Comunicación actual
- **Captación:** videos en Instagram
- **Socios activos:** no reciben ninguna comunicación mensual (punto de mejora)
- **Landing de suscripción:** `vinotecaligier.com/contenido-wineclub`
---
## Diseño aprobado — páginas de producto (short description)
Sistema visual heredado de las Cenas Casa VG:
- Fuente: Helvetica Neue
- Títulos: `13px`, `letter-spacing: 3px`, `uppercase`, color `#b08850`, `font-weight: 500`
- Párrafos: `16px`, `color: #3a3a3a`, `line-height: 1.8`
- Título principal (slogan): `17px`, `letter-spacing: 3px`, `uppercase`, `color: #1e1e1e`, `font-weight: 500`
- Divisores: `<hr>` full-width, `border-top: 1px solid #b08850`
- Tabla técnica al final: columna izquierda en dorado uppercase 10px, columna derecha en #3a3a3a 14px, separadores `#e8e2d9`
- Max-width: 640px
### Estructura de cada bloque de producto
1. **Slogan del tier** — título grande negro uppercase
2. `<hr>` dorado
3. **BIENVENIDO A VINOS GUARDADOS WINE CLUB** — subtítulo dorado + párrafo común (igual en todos los tiers)
4. `<hr>` dorado
5. **MEMBRESÍA [NOMBRE]** — subtítulo dorado + párrafo específico del tier
6. `<hr>` dorado
7. **Tabla técnica:** Membresía / Entrega / Valor / Ciclo
### Párrafo común (igual en todos los tiers)
> Cada mes, Alan Dayan hace una selección de 4 botellas de su cava para que lleguen a tu casa. Cada entrega combina distintas añadas, productores y estilos, para que cada mes sea un descubrimiento distinto.
---
## HTML aprobado — Silver
```html
<div style="font-family:'Helvetica Neue',Helvetica,Arial,sans-serif;color:#1e1e1e;max-width:640px;">
  <p style="font-size:17px;letter-spacing:3px;text-transform:uppercase;color:#1e1e1e;margin:0 0 16px;font-weight:500;">Tu primer paso dentro de la cava.</p>
  <hr style="border:none;border-top:1px solid #b08850;margin:0 0 28px;">
  <p style="font-size:13px;letter-spacing:3px;text-transform:uppercase;color:#b08850;margin:0 0 12px;font-weight:500;">Bienvenido a Vinos Guardados Wine Club</p>
  <p style="font-size:16px;color:#3a3a3a;line-height:1.8;margin:0 0 28px;">Cada mes, Alan Dayan hace una selección de 4 botellas de su cava para que lleguen a tu casa. Cada entrega combina distintas añadas, productores y estilos, para que cada mes sea un descubrimiento distinto.</p>
  <hr style="border:none;border-top:1px solid #b08850;margin:0 0 28px;">
  <p style="font-size:13px;letter-spacing:3px;text-transform:uppercase;color:#b08850;margin:0 0 12px;font-weight:500;">Membresía Silver</p>
  <p style="font-size:16px;color:#3a3a3a;line-height:1.8;margin:0 0 28px;">Es tu entrada a este mundo. Cada botella tiene una historia que ninguna etiqueta nueva puede tener. Empezás a entender que el mejor vino no es el más caro — es el que esperó el momento justo.</p>
  <hr style="border:none;border-top:1px solid #b08850;margin:0 0 28px;">
  <table style="width:100%;border-collapse:collapse;">
    <tr>
      <td style="font-size:10px;letter-spacing:2px;text-transform:uppercase;color:#b08850;padding:10px 0;border-bottom:1px solid #e8e2d9;width:40%;">Membresía</td>
      <td style="font-size:14px;color:#3a3a3a;padding:10px 0;border-bottom:1px solid #e8e2d9;">Silver</td>
    </tr>
    <tr>
      <td style="font-size:10px;letter-spacing:2px;text-transform:uppercase;color:#b08850;padding:10px 0;border-bottom:1px solid #e8e2d9;">Entrega</td>
      <td style="font-size:14px;color:#3a3a3a;padding:10px 0;border-bottom:1px solid #e8e2d9;">4 botellas</td>
    </tr>
    <tr>
      <td style="font-size:10px;letter-spacing:2px;text-transform:uppercase;color:#b08850;padding:10px 0;border-bottom:1px solid #e8e2d9;">Valor</td>
      <td style="font-size:14px;color:#3a3a3a;padding:10px 0;border-bottom:1px solid #e8e2d9;">$160.000</td>
    </tr>
    <tr>
      <td style="font-size:10px;letter-spacing:2px;text-transform:uppercase;color:#b08850;padding:10px 0;">Ciclo</td>
      <td style="font-size:14px;color:#3a3a3a;padding:10px 0;">Mensual</td>
    </tr>
  </table>
</div>
```
---
## HTML aprobado — Gold
```html
<div style="font-family:'Helvetica Neue',Helvetica,Arial,sans-serif;color:#1e1e1e;max-width:640px;">
  <p style="font-size:17px;letter-spacing:3px;text-transform:uppercase;color:#1e1e1e;margin:0 0 16px;font-weight:500;">Ya sabés lo que buscás.</p>
  <hr style="border:none;border-top:1px solid #b08850;margin:0 0 28px;">
  <p style="font-size:13px;letter-spacing:3px;text-transform:uppercase;color:#b08850;margin:0 0 12px;font-weight:500;">Bienvenido a Vinos Guardados Wine Club</p>
  <p style="font-size:16px;color:#3a3a3a;line-height:1.8;margin:0 0 28px;">Cada mes, Alan Dayan hace una selección de 4 botellas de su cava para que lleguen a tu casa. Cada entrega combina distintas añadas, productores y estilos, para que cada mes sea un descubrimiento distinto.</p>
  <hr style="border:none;border-top:1px solid #b08850;margin:0 0 28px;">
  <p style="font-size:13px;letter-spacing:3px;text-transform:uppercase;color:#b08850;margin:0 0 12px;font-weight:500;">Membresía Gold</p>
  <p style="font-size:16px;color:#3a3a3a;line-height:1.8;margin:0 0 28px;">Ya probaste suficiente como para saber que hay otro nivel. Gold es para quien quiere ir más adentro — etiquetas con más historia, añadas con más tiempo, selecciones que empiezan a mostrar lo que esta cava realmente guarda.</p>
  <hr style="border:none;border-top:1px solid #b08850;margin:0 0 28px;">
  <table style="width:100%;border-collapse:collapse;">
    <tr>
      <td style="font-size:10px;letter-spacing:2px;text-transform:uppercase;color:#b08850;padding:10px 0;border-bottom:1px solid #e8e2d9;width:40%;">Membresía</td>
      <td style="font-size:14px;color:#3a3a3a;padding:10px 0;border-bottom:1px solid #e8e2d9;">Gold</td>
    </tr>
    <tr>
      <td style="font-size:10px;letter-spacing:2px;text-transform:uppercase;color:#b08850;padding:10px 0;border-bottom:1px solid #e8e2d9;">Entrega</td>
      <td style="font-size:14px;color:#3a3a3a;padding:10px 0;border-bottom:1px solid #e8e2d9;">4 botellas</td>
    </tr>
    <tr>
      <td style="font-size:10px;letter-spacing:2px;text-transform:uppercase;color:#b08850;padding:10px 0;border-bottom:1px solid #e8e2d9;">Valor</td>
      <td style="font-size:14px;color:#3a3a3a;padding:10px 0;border-bottom:1px solid #e8e2d9;">$330.000</td>
    </tr>
    <tr>
      <td style="font-size:10px;letter-spacing:2px;text-transform:uppercase;color:#b08850;padding:10px 0;">Ciclo</td>
      <td style="font-size:14px;color:#3a3a3a;padding:10px 0;">Mensual</td>
    </tr>
  </table>
</div>
```
---
## HTML aprobado — Platinum
```html
<div style="font-family:'Helvetica Neue',Helvetica,Arial,sans-serif;color:#1e1e1e;max-width:640px;">
  <p style="font-size:17px;letter-spacing:3px;text-transform:uppercase;color:#1e1e1e;margin:0 0 16px;font-weight:500;">Entendés lo que otros solo ven.</p>
  <hr style="border:none;border-top:1px solid #b08850;margin:0 0 28px;">
  <p style="font-size:13px;letter-spacing:3px;text-transform:uppercase;color:#b08850;margin:0 0 12px;font-weight:500;">Bienvenido a Vinos Guardados Wine Club</p>
  <p style="font-size:16px;color:#3a3a3a;line-height:1.8;margin:0 0 28px;">Cada mes, Alan Dayan hace una selección de 4 botellas de su cava para que lleguen a tu casa. Cada entrega combina distintas añadas, productores y estilos, para que cada mes sea un descubrimiento distinto.</p>
  <hr style="border:none;border-top:1px solid #b08850;margin:0 0 28px;">
  <p style="font-size:13px;letter-spacing:3px;text-transform:uppercase;color:#b08850;margin:0 0 12px;font-weight:500;">Membresía Platinum</p>
  <p style="font-size:16px;color:#3a3a3a;line-height:1.8;margin:0 0 28px;">Para quien ya cruzó la línea entre consumir y coleccionar. Las selecciones Platinum incluyen algunas de las etiquetas más buscadas de la cava — vinos que definen épocas, de bodegas que marcaron la historia del vino argentino.</p>
  <hr style="border:none;border-top:1px solid #b08850;margin:0 0 28px;">
  <table style="width:100%;border-collapse:collapse;">
    <tr>
      <td style="font-size:10px;letter-spacing:2px;text-transform:uppercase;color:#b08850;padding:10px 0;border-bottom:1px solid #e8e2d9;width:40%;">Membresía</td>
      <td style="font-size:14px;color:#3a3a3a;padding:10px 0;border-bottom:1px solid #e8e2d9;">Platinum</td>
    </tr>
    <tr>
      <td style="font-size:10px;letter-spacing:2px;text-transform:uppercase;color:#b08850;padding:10px 0;border-bottom:1px solid #e8e2d9;">Entrega</td>
      <td style="font-size:14px;color:#3a3a3a;padding:10px 0;border-bottom:1px solid #e8e2d9;">4 botellas</td>
    </tr>
    <tr>
      <td style="font-size:10px;letter-spacing:2px;text-transform:uppercase;color:#b08850;padding:10px 0;border-bottom:1px solid #e8e2d9;">Valor</td>
      <td style="font-size:14px;color:#3a3a3a;padding:10px 0;border-bottom:1px solid #e8e2d9;">$470.000</td>
    </tr>
    <tr>
      <td style="font-size:10px;letter-spacing:2px;text-transform:uppercase;color:#b08850;padding:10px 0;">Ciclo</td>
      <td style="font-size:14px;color:#3a3a3a;padding:10px 0;">Mensual</td>
    </tr>
  </table>
</div>
```
---
## HTML aprobado — Black
```html
<div style="font-family:'Helvetica Neue',Helvetica,Arial,sans-serif;color:#1e1e1e;max-width:640px;">
  <p style="font-size:17px;letter-spacing:3px;text-transform:uppercase;color:#1e1e1e;margin:0 0 16px;font-weight:500;">No necesitás que te lo expliquen.</p>
  <hr style="border:none;border-top:1px solid #b08850;margin:0 0 28px;">
  <p style="font-size:13px;letter-spacing:3px;text-transform:uppercase;color:#b08850;margin:0 0 12px;font-weight:500;">Bienvenido a Vinos Guardados Wine Club</p>
  <p style="font-size:16px;color:#3a3a3a;line-height:1.8;margin:0 0 28px;">Cada mes, Alan Dayan hace una selección de 4 botellas de su cava para que lleguen a tu casa. Cada entrega combina distintas añadas, productores y estilos, para que cada mes sea un descubrimiento distinto.</p>
  <hr style="border:none;border-top:1px solid #b08850;margin:0 0 28px;">
  <p style="font-size:13px;letter-spacing:3px;text-transform:uppercase;color:#b08850;margin:0 0 12px;font-weight:500;">Membresía Black</p>
  <p style="font-size:16px;color:#3a3a3a;line-height:1.8;margin:0 0 28px;">Las botellas más raras de la cava. Etiquetas que llevan décadas guardadas, de añadas que ya no se repiten. Black es para quien sabe exactamente lo que tiene en la mano cuando abre una botella así.</p>
  <hr style="border:none;border-top:1px solid #b08850;margin:0 0 28px;">
  <table style="width:100%;border-collapse:collapse;">
    <tr>
      <td style="font-size:10px;letter-spacing:2px;text-transform:uppercase;color:#b08850;padding:10px 0;border-bottom:1px solid #e8e2d9;width:40%;">Membresía</td>
      <td style="font-size:14px;color:#3a3a3a;padding:10px 0;border-bottom:1px solid #e8e2d9;">Black</td>
    </tr>
    <tr>
      <td style="font-size:10px;letter-spacing:2px;text-transform:uppercase;color:#b08850;padding:10px 0;border-bottom:1px solid #e8e2d9;">Entrega</td>
      <td style="font-size:14px;color:#3a3a3a;padding:10px 0;border-bottom:1px solid #e8e2d9;">4 botellas</td>
    </tr>
    <tr>
      <td style="font-size:10px;letter-spacing:2px;text-transform:uppercase;color:#b08850;padding:10px 0;border-bottom:1px solid #e8e2d9;">Valor</td>
      <td style="font-size:14px;color:#3a3a3a;padding:10px 0;border-bottom:1px solid #e8e2d9;">$750.000</td>
    </tr>
    <tr>
      <td style="font-size:10px;letter-spacing:2px;text-transform:uppercase;color:#b08850;padding:10px 0;">Ciclo</td>
      <td style="font-size:14px;color:#3a3a3a;padding:10px 0;">Mensual</td>
    </tr>
  </table>
</div>
```
---
## HTML aprobado — Tier X (sin nombre)
```html
<div style="font-family:'Helvetica Neue',Helvetica,Arial,sans-serif;color:#1e1e1e;max-width:640px;">
  <p style="font-size:17px;letter-spacing:3px;text-transform:uppercase;color:#1e1e1e;margin:0 0 16px;font-weight:500;">Adentro de la cava. Una vez por mes.</p>
  <hr style="border:none;border-top:1px solid #b08850;margin:0 0 28px;">
  <p style="font-size:13px;letter-spacing:3px;text-transform:uppercase;color:#b08850;margin:0 0 12px;font-weight:500;">Bienvenido a Vinos Guardados Wine Club</p>
  <p style="font-size:16px;color:#3a3a3a;line-height:1.8;margin:0 0 28px;">Cada mes, Alan Dayan hace una selección de 4 botellas de su cava para que lleguen a tu casa. Cada entrega combina distintas añadas, productores y estilos, para que cada mes sea un descubrimiento distinto.</p>
  <hr style="border:none;border-top:1px solid #b08850;margin:0 0 28px;">
  <p style="font-size:13px;letter-spacing:3px;text-transform:uppercase;color:#b08850;margin:0 0 12px;font-weight:500;">Membresía</p>
  <p style="font-size:16px;color:#3a3a3a;line-height:1.8;margin:0 0 28px;">Una vez por mes, un grupo de seis miembros se reúne en la cava con Alan Dayan. Se abren botellas excepcionales, se habla de lo que hay detrás de cada una, y el mundo de afuera queda lejos. Las 4 botellas mensuales llegan a tu casa como extensión de esa noche.</p>
  <hr style="border:none;border-top:1px solid #b08850;margin:0 0 28px;">
  <table style="width:100%;border-collapse:collapse;">
    <tr>
      <td style="font-size:10px;letter-spacing:2px;text-transform:uppercase;color:#b08850;padding:10px 0;border-bottom:1px solid #e8e2d9;width:40%;">Membresía</td>
      <td style="font-size:14px;color:#3a3a3a;padding:10px 0;border-bottom:1px solid #e8e2d9;">—</td>
    </tr>
    <tr>
      <td style="font-size:10px;letter-spacing:2px;text-transform:uppercase;color:#b08850;padding:10px 0;border-bottom:1px solid #e8e2d9;">Entrega</td>
      <td style="font-size:14px;color:#3a3a3a;padding:10px 0;border-bottom:1px solid #e8e2d9;">4 botellas + encuentro mensual en la cava</td>
    </tr>
    <tr>
      <td style="font-size:10px;letter-spacing:2px;text-transform:uppercase;color:#b08850;padding:10px 0;border-bottom:1px solid #e8e2d9;">Valor</td>
      <td style="font-size:14px;color:#3a3a3a;padding:10px 0;border-bottom:1px solid #e8e2d9;">$1.500.000</td>
    </tr>
    <tr>
      <td style="font-size:10px;letter-spacing:2px;text-transform:uppercase;color:#b08850;padding:10px 0;">Ciclo</td>
      <td style="font-size:14px;color:#3a3a3a;padding:10px 0;">Mensual</td>
    </tr>
  </table>
</div>
```
---
## Hoja de ruta (roadmap)
1. ✅ Identidad y slogans de los 5 tiers
2. ✅ Páginas de producto de cada tier (short description Magento)
3. ⬜ Nombre y color del tier X
4. ⬜ Rediseño de landing `vinotecaligier.com/contenido-wineclub`
5. ⬜ Sistema de comunicación para socios activos (email + WhatsApp)
6. ⬜ Repensar el sistema completo para escalar a 1.000 socios
---
## Pendientes y decisiones abiertas
- **Nombre del tier X:** debe ser aspiracional, orientado al coleccionismo, moderno — referencia estética: Audemars Piguet (austero, no necesita explicarse). Ninguna propuesta aprobada aún.
- **Beneficios por tier:** acordados pero no incluidos en páginas de producto todavía. Se agregarán en una iteración posterior.
- **Comunicación mensual a socios:** no existe hoy. Punto crítico del roadmap.
- **Envíos:** sin cargo en CABA y GBA hasta 40 km. Todo el país con cotización aparte.


---
## ARCHIVO: modulo-ligier-experience/README.md
---

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


---
## ARCHIVO: modulo-cenas-casavg/README.md
---

# Módulo: Cenas Casa VG

**Fecha de creación:** 2026-06-08

**Última actualización:**

**Descripción:**

**Archivos en este módulo:**


---
## ARCHIVO: modulo-coleccion-legado/README.md
---

# Módulo: Colección Legado / Patrimonio

**Fecha de creación:** 2026-06-08

**Última actualización:**

**Descripción:** Copy aspiracional para la Colección Legado y Patrimonio.

**Archivos en este módulo:**


---
## ARCHIVO: modulo-magento/README.md
---

# Módulo: Magento

**Fecha de creación:** 2026-06-08

**Última actualización:**

**Descripción:**

**Archivos en este módulo:**


---
## ARCHIVO: modulo-general/README.md
---

# Módulo: General

**Fecha de creación:** 2026-06-08

**Última actualización:**

**Descripción:**

**Archivos en este módulo:**


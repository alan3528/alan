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

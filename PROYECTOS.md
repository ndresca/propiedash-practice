# Proyectos de práctica (para seguir después del onboarding)

Ya terminaste el recorrido y tu primera tarjeta. Estos proyectos son para **seguir
practicando** sin tocar producción: todo es en el sandbox, no se puede romper nada.

Cada uno es un escalón más que el anterior, y todos son cosas que Propiedash de verdad tiene
(así, mientras practicas, vas conociendo el producto). Van de HTML simple a un poco de
JavaScript. **Tu guía los construye contigo y te explica cada parte**: tú aprendes viendo y
entendiendo, no memorizando.

Cómo trabajarlos:
- Haz cada proyecto en tu propia carpeta: `proyectos/tu-nombre/`. Cada quien la suya, así
  nadie se pisa con nadie.
- Cada proyecto es un PR: rama → construir con tu guía → verlo → PR.
- Ve en orden. Sube un escalón cuando el anterior te salga cómodo.
- Punto de partida siempre a mano: `ejemplo/tarjeta-ejemplo.html`.

### Tus proyectos quedan EN VIVO en la web
Este repo publica en internet con **GitHub Pages**. O sea:
- Mientras construyes, tu guía te muestra el archivo para ir viendo los cambios rápido.
- Cuando tu **PR se fusiona a `main`**, tu proyecto queda **publicado en una URL real**, por
  ejemplo: `https://ndresca.github.io/propiedash-practice/proyectos/juan/resultados.html`
- Eso se llama un **deploy**: publicar tu cambio en la web. Es EXACTAMENTE lo que hace
  propiedash.com cuando fusionamos un cambio a `main` (ahí lo publica Vercel; aquí, Pages).

La portada del sitio de práctica está en `https://ndresca.github.io/propiedash-practice/`.
Cuando termines un proyecto y se fusione, abre tu URL y compártela: está en vivo de verdad.

---

## 1. Tu tarjeta de propiedad  ·  (ya la hiciste)
Una tarjeta de una propiedad inventada, con la marca de Propiedash. Base de todo lo demás.

## 2. Página de resultados (mini "buscar")
**Objetivo:** una página con **6 tarjetas** de propiedades en una cuadrícula, como la página
de búsqueda de Propiedash.
**Qué aprendes:** reutilizar un mismo componente muchas veces, y acomodar cosas en una
cuadrícula (CSS grid) que se vea bien en pantalla grande y en teléfono.
**Pistas:** parte de tu tarjeta; repítela 6 veces con datos distintos; ponlas en una grid.
**Hecho cuando:** ves 6 tarjetas ordenadas en el navegador, y en pantalla angosta se
reacomodan solas.

## 3. Ficha de propiedad (la página de una propiedad)
**Objetivo:** la página completa de UNA propiedad: foto grande, precio, título, ubicación,
specs (hab/baños/m²), una descripción, el agente, y un bloque de "ubicación".
**Qué aprendes:** armar una página con varias secciones y una jerarquía visual clara (lo
importante grande, lo secundario chico).
**Pistas:** piensa en secciones apiladas; usa los colores de la marca; el botón "Contactar"
en lima.
**Hecho cuando:** la página se siente como la ficha real de un inmueble y se lee de arriba
a abajo con sentido.

## 4. Perfil de agente (un Dashtag)
**Objetivo:** la página pública de un agente: su nombre, su `@dashtag`, una bio corta, y
abajo sus propiedades (reusa las tarjetas del proyecto 2).
**Qué aprendes:** combinar un encabezado (la persona) con una lista (sus propiedades); el
concepto de perfil/directorio de Propiedash.
**Hecho cuando:** se ve como el perfil de un agente con su inventario debajo.

## 5. Interactividad: favoritos y filtro (primer JavaScript)
**Objetivo:** en tu página de resultados, agrega dos cosas con un poquito de JavaScript:
(a) un corazón en cada tarjeta que se marca/desmarca al hacer clic (favorito), y (b) un
filtro para mostrar solo "Venta" o solo "Alquiler".
**Qué aprendes:** tu primer JavaScript, reaccionar a clics y cambiar la página en vivo. Son
funciones REALES de Propiedash (favoritos, filtros).
**Hecho cuando:** puedes marcar favoritos y filtrar, y la página responde al instante.

## 6. Cambio de moneda USD ↔ Bs (la tasa BCV)
**Objetivo:** un botón que cambia todos los precios entre dólares y bolívares, usando una
tasa BCV que pones tú (ej. 36,5).
**Qué aprendes:** más JavaScript (recorrer elementos, formatear números) y el concepto más
propio de Propiedash: precios en USD con su equivalente en Bs a la tasa BCV.
**Hecho cuando:** un clic convierte todos los precios y se ven bien formateados.

---

### Estírate (opcional, si quieres más)
- Una mini **landing** de Propiedash: un hero con el eslogan "Donde Venezuela compra, vende
  y alquila", un buscador falso, y una fila de tarjetas debajo.
- Modo **claro/oscuro** con un botón (como la guía visual del onboarding).

Cuando estos te salgan cómodos, ya no estás practicando de mentira: estás listo para tareas
reales pequeñas en el sitio de verdad (eso lo coordina Andrés). Cada tarea real es una
versión más grande de este mismo loop.

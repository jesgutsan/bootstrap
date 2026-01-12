# Bootstrap – Maquetación 
# Arranque 

## Contenedores

    <div class="contenedor"></div>
    <div class="fluido-del-contenedor"></div>

• contenedor → centrado

• contenedor-fluido → ancho completo

## Grid (Sistema de rejilla)

Bootstrap organiza el contenido usando una ** rejilla de 12 columnas ** .  

Cada fila ( ` row ` ) se divide en 12 partes iguales y las columnas ( ` col-* ` ) indican cuántas ocupa cada elemento.

## Breakpoints (tamaños de pantalla)

col- → móviles (<576px)

col-sm- → ≥576px → móvil grande

col-md- → ≥768px → tablet

col-lg- → ≥992px → portátil

col-xl- → ≥1200px → pantalla grande

col-xxl- → ≥1400px → pantalla muy grande

Los píxeles indican CUÁNDO cambia el diseño, las columnas indican CUÁNTO espacio ocupa.

La fila como 12 bloques, imagina una fila dividida así:

    |1|2|3|4|5|6|7|8|9|10|11|12|

---

Casos básicos, una fila ocupando todo

    <div class="col-12"></div>

Ejemplo práctico responsive

    <div class="container">
        <div class="row">
            <div class="col-12 col-md-6 col-lg-4">
                 Primera caja
            </div>
            <div class="col-12 col-md-6 col-lg-4">
                Segunda caja
            </div>
            <div class="col-12 col-md-6 col-lg-4">
                Tercera caja
            </div>
        </div>
    </div>

Comportamiento:

📱 Móvil → cada caja ocupa 12 columnas (una debajo de otra)

📲 Tablet (≥768px) → 6 columnas (2 por fila)

💻 Portátil (≥992px) → 4 columnas (3 por fila)

🧠 Idea clave

👉 Grid = estructura + responsive sin CSS propio

👉 Breakpoints dicen cuándo cambia

👉 Columnas dicen cuánto ocupa

## Espaciado RESPONSIVE

Cambiar el espacio según pantalla:

    mt-1 mt-md-4  <!-- en móvil: poco margen arriba  desde ≥768px (md): margen arriba grande-->

    px-2 px-lg-5 <!-- en móvil: poco padding izquierda/derecha desde ≥992px (lg): padding grande a los lados-->

👉 pequeño en móvil, grande en escritorio

## Espaciado (Margin & Padding)

Bootstrap permite añadir márgenes y rellenos usando clases, sin escribir CSS.

Tipos de espaciado

m → margin (margen exterior)

p → padding (relleno interior)

Ejemplos: m-3 → margen

p-3 → padding

---

Direcciones

t → top (arriba)

b → bottom (abajo)

s → start (izquierda)

e → end (derecha)

x → eje horizontal (izq + der)

y → eje vertical (arriba + abajo)

(sin letra) → todos los lados

Ejemplos:

    mt-3   <!-- margen arriba -->

    pb-2   <!-- padding abajo -->

    px-4   <!-- padding izquierda y derecha -->

    my-5   <!-- margen arriba y abajo -->

**Tamaños disponibles**

0 → sin espacio

1 → muy pequeño

2 → pequeño

3 → normal

4 → grande

5 → muy grande

TODAS las combinaciones útiles (ejemplos)

Separar por ABAJO mb-1

    mb-3

    mb-5

Separar por ARRIBA mt-1

    mt-3

    mt-5

Separar por la IZQUIERDA

    ms-2


Separar por la DERECHA

    me-2

    me-4

Separar ARRIBA y ABAJO

    my-3

    my-5

Separar IZQUIERDA y DERECHA

    mx-3

    mx-5

---

**Espacio INTERIOR (padding)**

    p-3      ← todos los lados

    pt-2 ← arriba

    pb-4 ← abajo

    px-5 ← izquierda y derecha

    py-3 ← arriba y abajo

---

**Quitar espacios**

    m-0 ← sin margen

    p-0 ← relleno de pecado

---
### Resumen mental 

👉 **m=fuera | p = dentro**  

👉 **tbsexy=dirección**  

👉 **0–5 = tamaño**


### Ejemplos prácticos

**Separar secciones verticalmente**

    <div class="my-5"></div>

**Dar aire interno a una caja**

    <div class="p-4"></div>

**Separar solo por arriba**

    <div class="mt-3"></div>

**Eliminar márgenes**

    <div class="m-0"></div>


Arrancar el servidor de MkDocs - **mkdocsserve**

Y entrar en: **http://127.0.0.1:8000**

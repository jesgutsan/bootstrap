
## Ejemplo de Maquetación    
    
    * {
        /reset/
        margin: 0;                 /* Elimina márgenes por defecto */
        padding: 0;                /* Elimina rellenos por defecto */
        box-sizing: border-box;    /* El padding y el borde no aumentan el tamaño */
    }

    body {
        font-family: Arial, Helvetica, sans-serif; /* Tipografía base */
        margin: 0;                 /* Sin margen exterior */
        padding: 0;                /* Sin relleno interior */
        line-height: 1.6;          /* Altura de línea para mejorar lectura */
    }

    header {
        background-color: steelblue; /* Color de fondo del encabezado */
        padding: 10px 0;             /* Espacio arriba y abajo */
        text-align: center;          /* Texto centrado horizontalmente */
    }

    header h1 {
        color: white;              /* Color del texto */
        font-size: 32px;            /* Tamaño del título */
    }

    nav {
        background-color: lightskyblue; /* Fondo del menú */
        display: flex;                 /* Activa Flexbox */
        justify-content: center;       /* Centra los enlaces */
        padding: 10px;                 /* Espacio interior */
    }

    nav a {
        text-decoration: none;         /* Quita el subrayado */
        color: white;                  /* Color del texto */
        font-size: 16px;               /* Tamaño de letra */
        padding: 1px 60px;             /* Espacio alrededor del enlace */
    }

    .main-content {
        display: flex;                 /* Coloca los bloques en fila */
        gap: 30px;                     /* Espacio entre tarjetas */
        justify-content: center;       /* Centra las tarjetas */
        padding: 20px 0;               /* Espacio arriba y abajo */
        background-color: whitesmoke;  /* Fondo de la sección */
        text-align: center;            /* Texto centrado */
    }

    .main-content > div {
        width: 280px;                  /* Ancho de cada tarjeta */
        background-color: #c0f0f0;     /* Fondo de la tarjeta */
        padding: 10px;                 /* Espacio interior */
        border-radius: 8px;            /* Esquinas redondeadas */
    }

    .main-content img {
        width: 100%;                   /* La imagen ocupa todo el ancho */
    }

    .main-content h2 {
        font-size: 18px;               /* Tamaño del título */
        margin-bottom: 10px;           /* Espacio inferior */
    }

    .main-content p {
        font-size: 14px;               /* Tamaño del texto */
        text-align: center;            /* Texto centrado */
    }

    footer {
        text-align: center;            /* Texto centrado */
        padding: 20px;                 /* Espacio interior */
        background-color: steelblue;   /* Color de fondo */
        color: white;                  /* Color del texto */
    }

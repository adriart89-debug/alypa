# Alypa Cerámica · Nueva web (propuesta)

Rediseño de la home de [alypa.es](https://alypa.es) hacia un enfoque más editorial y de marca, inspirado en el estilo de [bodegapiedrafluida.com](https://bodegapiedrafluida.com): storytelling de origen, fotografía como protagonista y el catálogo como capa secundaria en lugar de portada.

Es un prototipo de dirección de diseño (una sola página, HTML/CSS/JS estático), no un build de producción.

## Estructura

```
alypa-web/
├── index.html            Home completa (una sola página)
├── assets/
│   └── img/              Imágenes y logos
└── README.md
```

## Ver en local

Al ser HTML estático, basta con abrir `index.html` en el navegador. Para servirlo con rutas limpias:

```bash
# Python
python3 -m http.server 8000
# luego abrir http://localhost:8000
```

## Publicar con GitHub Pages

1. Sube el contenido de esta carpeta a un repositorio de GitHub.
2. En el repo: **Settings → Pages → Source: `main` / carpeta `/root`**.
3. La web quedará publicada en `https://<usuario>.github.io/<repo>/`.

## Secciones

- **Hero**: apertura editorial con narrativa de marca.
- **Origen**: manifiesto de marca (desde 2012).
- **Nosotros**: historia + exposición de 1.400 m² en Las Chafiras.
- **Materiales**: piscina, baño, revestimientos y pavimentos como portales.
- **Por qué Alypa**: sección interactiva con los 4 valores en puntos desplegables.
- **Proyectos**: casos reales en formato case study.
- **Journal**: contenido editorial (evolución del blog).
- **Reseñas**: prueba social curada.
- **CTA doble**: caminos separados para particulares y profesionales (B2B).

## Notas

- Paleta y tipografía derivadas del social book de marca: crema, carbón, rojo `#D93B44`, verde y arena. Tipos: Fraunces (display) + Inter (texto).
- El logo se muestra en dos variantes (clara/oscura) según el fondo.
- Algunas imágenes del hero y del journal son de stock (Unsplash) y deben sustituirse por material propio de Alypa antes de producción.

## Créditos

Propuesta de rediseño. Marca: Alypa Cerámica.

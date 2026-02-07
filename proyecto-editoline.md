# Editoline

Editorial, web compuesta por 6 páginas.. + 1 por cada obra y 1 por cada autor...

**6(principales) + 12(obras) + 6(autores) = 24 páginas!!!**

## Composición

- **Conócenos** (quienes somos?):
  1ra sección -> horario (`<table>` en PC, lista en mobile)
  2da sección -> contacto (`<form>`)
  3ra sección -> mapa (`<iframe>`)
  _Propuesta_: incluir sección con foto del local? con foto del personal?
- **Catálogo** (libros/novelas):
  1ra sección -> libro recomendado
  2da sección -> grid con cards del catálogo completo (card(flex): nombre del libro, imagen de portada, breve descripción, `<button>` "leer más..")
- **Autores**:
  1ra sección -> grid con cards de autores incluidos: Nombres, foto, reseña del autor (sugerido: aprox. 3 parrafos) y flexbox con catalálogo de cada autor (solo imágen).
- **Libros**(Novelas):
  1ra sección -> Imagen del libro
  Nombre del libro
  Reseña del libro
  Imagen del autor
  Reseña del autor (link a la pagina "Autores")
- **Términos Legales**:
  1ra sección -> Condiciones de adquisición para las distribuidoras/librerias... (Por definir inclusiones adicionales)
- **Destacados**:
  1ra sección -> La obra +reciente (card con diseño más grande, destacado)
  2da sección -> La obra +vendida
  4ta sección -> El autor con +ventas

## Consideraciones:

- HTML semántico
- index.html -> `<body id="index">`... y así en cada página, según su contenido. **Obligatorio**: En el CSS hacer referencia a todo el elemento para estilar (x ejm: #index #quienes h3 {...}).
- _Propuesta_: Poner "site map" en cada página ???
- **Importante**: Recolectar info para universo de 12(¿?) obras, escritas por 6(¿?) autores.
- De autor:
  2 fotos del autor: 1ra solo el rostro y 2da en un lugar y situación mas distendida (para la pagina "Autores"). Considerar generación vía IA de personas ficticias
  Datos (inventados) de reseña para presentación, y set de las obras disponibles.
- Del libro/novela:
  1 foto de la portada.
  Datos: Autor, género de novela, prólogo (introducción).
- Planificar el contenido y la realización del "readme.md"
- **Importante**: todas las páginas deben tener al menos 1 link hacia otra, cada obra y cada autor deben tener su propia página...

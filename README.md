# Titan Hard · Maquetación de tienda de hardware

Proyecto educativo frontend con HTML, CSS y Bootstrap para presentar productos de hardware y tecnología.

## Alcance disponible

Incluye página principal, categorías, fichas de productos, contacto, login, registro, carrito y página de error. La rama principal no incluye archivos JavaScript propios ni una API; estas vistas no se presentan como un sistema de compras o autenticación comercial.

## Ejecución local

```bash
git clone https://github.com/Franc-Devel/Proyecto-Ecomerce.git
cd Proyecto-Ecomerce
python3 -m http.server 8000
```

Abrir `http://localhost:8000/`. El servidor estático sólo entrega archivos: no procesa pagos, cuentas ni mensajes de contacto.

## Organización

- `index.html`: página principal.
- `css/`: estilos generales y de páginas.
- `pages/`: categorías, productos y formularios.
- `assets/`: imágenes de la presentación.

## Contexto y siguientes pasos

Repositorio educativo de Francisco Delgado. La implementación de lógica de carrito y formularios queda como trabajo futuro; no se modifica funcionalidad ni arquitectura en esta revisión documental.

Antes de una versión comercial, revisar derechos de uso de imágenes, validación de formularios, autorización de servidor, manejo de pedidos y pruebas de accesibilidad.

[Perfil profesional](https://github.com/Franc-Devel) · [LinkedIn](https://www.linkedin.com/in/francisco-delgado-ojeda/)

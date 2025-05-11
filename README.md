# Plantilla de email para PwC Colombia

¡Hola! Este repo contiene mi solución para la prueba técnica de PwC. Básicamente, he creado una plantilla de email HTML para su boletín informativo que funciona bien en la mayoría de clientes de correo.

## Sobre las imágenes
Para que puedan ver la plantilla funcionando sin problemas, subí todas las imágenes a mi servidor temporal (https://smartpark.kesug.com/). Así pueden visualizar todo sin configuraciones extra.

En el repo, las imágenes están en la carpeta `/img`:
- Logo de PwC: `/img/pwclogo.png`
- El banner principal: `/img/banner.png` 
- Imágenes para las noticias: `/img/noticia1.png` y `/img/noticia2.png`
- Los iconos de redes sociales en `/img/redes/`

## Lo técnico
Me enfoqué en que la plantilla:
- Se vea bien en cualquier dispositivo (móvil, tablet, escritorio)
- Funcione en la mayoría de clientes de email
- Sea fácil de modificar si necesitan hacer cambios
- Tenga los estilos inline para evitar problemas de compatibilidad

## Decisiones que tomé
Algunas cosas a destacar:
- Tuve que usar PNG para el logo porque Outlook no soporta bien los SVG
- Me costó un poco conseguir los sombreados, pero al final logré un truco que funciona bien
- En algunos clientes de email los estilos se pierden, así que la estructura está pensada para que aún así se vea decente

## Cómo usarlo
Es bastante simple:
1. Descarga todo
2. Edita el `index.html` según lo que necesites
3. Cambia las imágenes
4. Para producción, sube las imágenes a tu propio servidor y actualiza las URLs
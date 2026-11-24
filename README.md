# 4Pic

Red social multiplataforma (web, Android e iOS) centrada en la **privacidad** y la **personalización**.

## Reglas del producto

- Solo se comparten **imágenes**. No hay vídeos y no están previstos.
- Máximo de **4 stories al día** por usuario. Las stories desaparecen a las 24 horas.
- Privacidad por diseño: audiencias por publicación, sin rastreo y con control total sobre los datos.

## Landing

La documentación pública del proyecto vive en `index.html`. Es un sitio estático sin dependencias ni rastreadores:

```
index.html      Landing con la documentación del proyecto
css/styles.css  Estilos (tema oscuro, sin frameworks)
js/main.js      Navegación suave
```

Para verla en local:

```bash
npx serve .
```

o simplemente abre `index.html` en el navegador.

## Roadmap

1. **Landing y documentación** — visión y reglas del producto.
2. **Prototipo web** — autenticación, subida de imágenes, feed y límite de 4 stories diarias.
3. **Apps móviles** — Android e iOS.
4. **Privacidad avanzada** — audiencias por publicación y exportación de datos.

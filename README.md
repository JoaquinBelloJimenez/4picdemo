# 4Pic

Red social multiplataforma (web, Android e iOS) centrada en la **privacidad** y la **personalización**.

## Reglas del producto

- Solo se comparten **imágenes**. No hay vídeos y no están previstos.
- Máximo de **4 stories al día** por usuario. Las stories desaparecen a las 24 horas.
- Privacidad por diseño: audiencias por publicación, sin rastreo y con control total sobre los datos.

## Puntos clave de la aplicación

### Opciones

Cada preferencia funciona en niveles, del más restrictivo al más abierto:

| Opción | Niveles |
| --- | --- |
| Privacidad | `0` Oculta · `1` Seguidores · `2` pública |
| Perfil | `0` infantil · `1` personal · `2` profesional |
| Notificaciones | `0` todas · `1` esenciales · `2` ninguna |
| Sonidos | `0` reproducir · `1` silenciar |
| Personalización | `0` toda · `1` tema básico |
| Privacidad y contraseña | gestión de credenciales y acceso protegido |

### Mi perfil

- Nombre y logo/foto.
- Colores de perfil.
- Música de perfil.
- Sonido de perfil.
- Seguidores.

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

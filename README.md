# Hack Your Mind

Landing de Hack Your Mind: una plataforma interactiva de desarrollo humano. Con rigor, sin gurús y sin vender tus datos.

Es un solo archivo estático (`index.html`), sin dependencias ni build. Las fuentes se cargan desde Google Fonts.

## Verla en local

```bash
python3 -m http.server 4173
```

Luego abre http://localhost:4173.

## Qué incluye

- Hero con la constelación de puntos que se ordena en la H (respeta `prefers-reduced-motion`).
- Diagnóstico de 60 segundos: "¿Qué mundo necesitas hoy?". El resultado se guarda solo en el dispositivo.
- Los cinco mundos (Mente, Crecimiento, Liderazgo, Negocio, Futuro) y 20 ejercicios, cada uno con su fuente.
- Recomendaciones: podcasts, música para focus y libros.
- Gamificación ética, privacidad por diseño (exportar y borrar datos funcionan) y footer completo.
- Español e inglés, tema claro (Papel) y oscuro (Noche).

El contenido es visible sin JavaScript; las animaciones solo lo mejoran.

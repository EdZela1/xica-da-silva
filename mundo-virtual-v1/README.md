# Mundo Virtual $$$ V1

Prototipo web. Los **24 ciudadanos y 3 empresas** operan dentro de una simulación por reglas; no existe trabajo autónomo de IA generativa aún.

- 24 horas virtuales equivalen a 5 minutos reales.
- La oferta V-Coin tiene un libro contable sintético.
- El panel Banco Central mantiene ingresos reales en **S/ 0** hasta conectar verificación segura de pagos.
- El catálogo incluye muestras descargables, pero **no acepta cobros**.
- Esta rama está separada del repositorio principal; el flujo de GitHub Pages publica únicamente la subcarpeta de Mundo Virtual.

## Para activar alojamiento gratuito en GitHub Pages
1. Abrir **Settings → Pages** en el repositorio.
2. En **Build and deployment**, seleccionar **GitHub Actions**.
3. Abrir **Actions → Publicar Mundo Virtual V1 en GitHub Pages → Run workflow**, seleccionando la rama `mundo-virtual-v1`.
4. Revisar la URL efectiva de publicación en la ejecución y en Settings → Pages. La publicación exige que GitHub Pages esté habilitado y es pública.

No se requiere una computadora encendida. El estado simulado del mundo se calcula a partir del reloj cuando se abre la página, pero no hay procesos generativos activos en un servidor.

## Próxima etapa
Integrar una plataforma de pagos legítima, validación segura de webhooks y entrega posterior al cobro antes de aceptar pedidos. No introducir credenciales bancarias en el HTML.

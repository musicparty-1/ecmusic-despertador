# Despertador de EC Music

Tarea programada de GitHub Actions que consulta cada 10 minutos la base de EC Music en Render para que el plan gratis no se
duerma (dormida, la primera persona que entra espera entre 30 y 60 segundos para iniciar sesión o abrir un evento).

- No contiene código ni datos del proyecto: solo consulta una dirección pública.
- Es gratis porque el repositorio es público (los minutos de GitHub Actions no se cobran en repositorios públicos).
- Render da 750 horas gratis por mes: alcanza para un servicio despierto todo el mes.
- Para apagarlo: Actions > "Despertar la base de EC Music" > Disable workflow.

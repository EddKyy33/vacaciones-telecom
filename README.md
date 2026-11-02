# Vacaciones Telecom

Calendario de vacaciones del equipo de Telecomunicaciones.

- El equipo entra con el código del equipo (sin crear cuenta), consulta el calendario y envía solicitudes de vacaciones, cambios o cancelaciones.
- Solo el aprobador, con su usuario, aprueba o rechaza; nada cambia en el calendario hasta que lo aprueba.
- Los datos viven en una base de datos de Supabase con reglas de acceso; este repositorio solo contiene la página.

## Archivos

- `index.html`: la página completa (diseño, calendario y lógica).
- `supabase.js`: cliente de Supabase (supabase-js 2.117.3, licencia MIT en `supabase-js.LICENSE.txt`).

La conexión se configura con `SUPABASE_URL` y `SUPABASE_KEY` (clave *publishable*/*anon*, pública por diseño) dentro de `index.html`. El script de la base de datos y el código del equipo no se guardan aquí.

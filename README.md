# RD Nutrición — Landing + Portal de pacientes (demo)

Landing de **RD Nutrición** (Mtr. Rocío Agustina Dryon, Licenciada en Nutrición) con un portal de pacientes funcional como demostración.

**Demo en vivo:** https://emilianodn883.github.io/landing-rd-nutricion/

## Qué incluye

- **Landing:** hero, sobre mí, servicios (salud digestiva, nutrición deportiva, sobrepeso y obesidad), modalidad de trabajo, testimonio, contacto por WhatsApp, reserva por autogestión y direcciones.
- **Botón "Acceso pacientes"** que abre el portal.
- **Panel de la nutricionista:** crea pacientes, carga planes (título, indicaciones y un PDF o imagen), los filtra por paciente y los elimina.
- **Panel del paciente:** inicia sesión y ve sus planes, del más reciente al más antiguo, con descarga.

## Usuarios de demo

| Rol | Email | Contraseña |
|---|---|---|
| Profesional | `profesional@rdnutricion.demo` | `rocio2026` |
| Paciente | `paciente@demo.com` | `paciente123` |

## Importante: es una demo

Los datos (pacientes, planes y archivos) se guardan **solo en el navegador** de quien lo usa (`localStorage`). Lo que cargue la profesional en su computadora no lo ve un paciente desde su celular. Los archivos están limitados a 1,2 MB.

Para usarlo en producción hay que conectar un backend (por ejemplo Supabase o Firebase) reemplazando los métodos del objeto `Store` en `index.html`, que ya está aislado para eso.

## Cómo correrlo

Es un único archivo estático: abrí `index.html` en el navegador, o servilo con cualquier hosting estático (GitHub Pages, Netlify, Vercel).

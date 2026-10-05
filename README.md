# CarpinterSys

Sistema web para la gestión y presentación de servicios de Carpintería Morales.

## Tecnologías

- Next.js
- React 19
- TypeScript
- Tailwind CSS / estilos CSS
- Supabase

## Funcionalidades documentadas

- Página principal y presentación del negocio.
- Portafolio/proyectos.
- Servicios y precios.
- Formulario de cotización.
- Contacto.
- Panel de administración.
- Consulta de cotizaciones mediante Supabase.
- Estructuras para proyectos, servicios, cotizaciones y perfil.

## Configuración

1. Instalar dependencias:
   `npm install`
2. Crear `.env.local` a partir de `.env.example`.
3. Configurar `NEXT_PUBLIC_SUPABASE_URL` y `NEXT_PUBLIC_SUPABASE_ANON_KEY`.
4. Ejecutar:
   `npm run dev`

## Integración Jira

Para asociar cambios del repositorio con Jira se deben utilizar las claves de las actividades en las ramas, commits o pull requests.

Ejemplo:

`CARP-115 Evidencia de código Fase 2`

## Nota

Este repositorio es una implementación de referencia construida a partir de la documentación de la Fase 2. Los valores reales de Supabase, credenciales, imágenes y contenido operativo deben configurarse con los datos del proyecto.

# InfoBl@ck — Centro de referencia de proyectos

**Propósito:** recordar rápidamente qué es cada proyecto, para qué sirve, dónde está publicado, dónde vive su código y qué revisar antes de trabajar.

> Guía operativa. No contiene claves, contraseñas, tokens ni información privada de clientes.

## 1. InfoBl@ck — sitio institucional
- **Rol:** marca y sitio comercial de servicios digitales.
- **Sitio público:** https://infoblack.cl
- **Repositorio:** https://github.com/infoblacklinares/infoblack-cl
- **Hosting conocido:** el repositorio contiene configuración de Netlify (netlify.toml); el sitio institucional se ha gestionado por Netlify.
- **Servicios descritos en el sitio:** sitios web profesionales, tiendas online, sistemas a medida y asesoría digital.
- **Contacto publicado:** WhatsApp +56 9 8427 2557; correo infoblack.linares@gmail.com.
- **Instagram enlazado desde la presentación:** https://instagram.com/infoblack.linares
- **Uso:** captar consultas, presentar servicios y convertir interesados en oportunidades comerciales.
- **Antes de editar:** revisar index.html, assets/, pack-cumplimiento/ y politica-de-privacidad/. No conectar este repositorio al proyecto Vercel de la presentación.

## 2. LinaresYa — plataforma local
- **Rol:** directorio digital de negocios de Linares.
- **Sitio público:** https://linaresya.cl
- **Repositorio:** https://github.com/infoblacklinares/linaresya
- **Tecnologías declaradas:** Next.js y Supabase.
- **Desarrollo local:** npm ci y npm run dev.
- **Validación declarada:** npm test y npm run build.
- **Documentación técnica:** docs/estado-actual.md y docs/arquitectura/decisiones-abiertas.md.
- **Objetivo:** ayudar a descubrir negocios, servicios y lugares de Linares y ofrecer visibilidad a comercios y emprendimientos.
- **Estado técnico conocido:** la documentación tiene corte 2026-10-03 y reporta producción desplegada y CI con tests/build. Pendientes documentados: versionado del esquema Supabase, límites distribuidos para búsqueda/reseñas/reportes, estrategia de caché/service worker y revisión del bucket de imágenes. Confirmar antes de tratarlos como estado actual.
- **Seguridad:** nunca copiar ni publicar claves Supabase. La documentación menciona una Secret Key antigua expuesta que debe rotarse; verificar su estado antes de cerrar esa deuda.

## 3. Diario El Estratega — medio digital
- **Rol:** medio informativo regional y trabajo de modernización web/editorial.
- **Sitio público:** https://elestratega.cl
- **Plataforma de producción conocida:** WordPress.
- **Repositorio localizado:** https://github.com/infoblacklinares/diario-estretaga
- **Advertencia:** el README de ese repositorio lo describe como una maqueta funcional con contenido y fotografías de muestra, no como el código del WordPress de producción.
- **Tecnologías de la maqueta:** Next.js 14, React 18, TypeScript y Tailwind CSS.
- **Propósito de la maqueta:** prototipo de lectura, portada, secciones, notas, búsqueda, guardado local y newsletter.
- **Uso del proyecto real:** gestión WordPress, experiencia visual, contenidos, redes sociales y mejoras del portal.
- **Antes de editar:** confirmar si el cambio corresponde al WordPress de producción o a la maqueta de GitHub.

## 4. Presentación y portafolio InfoBl@ck
- **URL:** https://infoblack-presentacion-cl.vercel.app
- **Repositorio:** https://github.com/infoblacklinares/Infoblack-presentacion-cl
- **Hosting:** Vercel, conectado al repositorio.
- **Archivos principales:** index.html y assets/portfolio/.
- **Imágenes:** infoblack-small.jpg, linaresya-small.jpg y diario-small.jpg.
- **Propósito:** mostrar proyectos, explicar su utilidad, facilitar el contacto y compartir el perfil mediante QR.
- **Regla:** mantener esta presentación separada de los repositorios y despliegues de los tres proyectos.

## 5. Rutina de trabajo recomendada
1. Identificar el proyecto antes de modificar archivos.
2. Leer su README y documento de estado más reciente.
3. Distinguir producción de prototipos y entornos de prueba.
4. No cambiar hosting, dominios, claves, pagos ni configuración de producción sin aprobación explícita.
5. Registrar cada cambio relevante: fecha, proyecto, archivo, motivo, commit, despliegue y resultado verificado.
6. Verificar el sitio publicado después de cada despliegue.

## 6. Pendientes de documentación
- Confirmar el Instagram oficial de InfoBl@ck y si el enlace actual sigue vigente.
- Confirmar los perfiles sociales oficiales de LinaresYa y Diario El Estratega.
- Actualizar los estados técnicos leyendo repositorios y paneles de producción en la fecha de cada intervención.
- Agregar responsables, prioridades y fechas solo cuando estén confirmados.
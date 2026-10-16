# ANÁLISIS DE REQUERIMIENTOS

## Actores (según PDF original)
- Reportante ciudadano: comunica ubicación, descripción, circunstancias
- Coordinador de rescate: revisa reportes, prioriza, distribuye tareas
- Voluntario rescatista: consulta asignaciones, registra acciones
- Profesional veterinario: documenta evaluaciones y evolución
- Administrador del refugio: mantiene usuarios, permisos, supervisa adopción
- Persona adoptante: explora animales y presenta información para evaluación

## Requerimientos Funcionales
- RF01: Registrar aviso con fecha, ubicación, descripción y contacto
- RF02: Crear expediente único por animal y clasificar por especie
- RF03: Asignar coordinadores, rescatistas o veterinarios
- RF04: Registrar intervenciones, observaciones clínicas y seguimiento
- RF05: Cambiar estado solo cuando se cumplan condiciones
- RF06: Enviar avisos a usuarios autorizados
- RF07: Registrar solicitudes de adopción y documentar evaluación
- RF08: Buscar y filtrar por estado, especie, fecha o responsable
- RF09: Guardar historial de cambios y personas que los realizaron
- RF10: Controlar acceso según rol

## Requerimientos No Funcionales
- Seguridad: proteger datos personales, restringir por permisos
- Disponibilidad: consulta cuando necesiten usuarios autorizados
- Mantenibilidad: separar interfaz, reglas de negocio y acceso a datos
- Escalabilidad: incorporar nuevas especies, refugios, canales
- Integridad: validar obligatorios, evitar duplicados
- Usabilidad: formularios sencillos, mensajes comprensibles

## Ciclo de Estados
Aviso recibido -> Rescate confirmado -> En evaluación -> En tratamiento -> Disponible para adopción -> Adoptado -> Caso finalizado

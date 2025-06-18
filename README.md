Ejercicio Guiado: Automatización Continua con GitHub Actions.

Grupo 2 : Guillermo Torres - Francisco Leiva

- ¿Qué ventajas observaste al automatizar pruebas con GitHub Actions?
  Es todo más simple y rapido, no hay que configurar variables de entorno ni tampoco instalar dependencias de manera local.
  
- ¿Qué diferencia a GitHub de Jenkins u otras herramientas de CI?
  GitHub Action se diferencia en cuanto a:
    - Gestión : Cloud/Self-hosted.
    - Integración : Nativo con GitHub.
    - Complexidad : Baja/Media.
    - Mantenimiento : GitHub lo gestiona.
  
- ¿Qué mejoras podrías agregar a este pipeline?
  1.- Agregar una matriz de versiones.
  2.- Reportes de cobertura de pruebas.
  3.- Agregar validaciones de código.
  
- ¿Qué consideraciones de seguridad aplicarías en proyectos reales?
  1.- Gestionar los secrets desde GitHub Secrets.
  2.- Permisos mínimos en workflows y repositorios.
  3.- Triggers seguros y acciones verificadas.
  4.- Monitoreo continuo.
  
Ideas sobre cómo automatizar otros aspectos del proyecto.
- build :
  * Usar matrices para compilar en múltiples sistemas.
  * Integrar caché de dependencias.
  * Generar artefactos.
- Despliegue :
  * Implementar entornos con revisión manual para producción.
  * Desplegar etapas con verificaciones de salud automáticas.
  * Usar infraestructura como Código para despliegues consistentes.
- Auditoría Continua
  * Escanear código y dependencias.
  * Detectar secretos expuestos y validar compliance.
  * Enviar reportes a Slack/Email si fallan las pruebas de seguridad.

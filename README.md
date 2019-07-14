# Fiscal Digital
Sistema de registros de actas para la fiscalización electoral de Guatemala u otros países.

Esta es una iniciativa ciudadana para mejorar la transparencia de los procesos electorales en Guatemala, para lo cual se plantea un proceso de auditoría de terceros por medio de digitadores voluntarios, una entidad auditora que resguardará copia de las imagenes de las actas físicas guardandolas en un documento PDF firmado con un certificado X509 y llaves asimétricas ECSDA (Elliptic Curve Digital Signature Algorithm), en un sistema distribuido, en la nube, para la seguridad.

Las actas son subidas por medio de teléfonos inteligentes a traves de las redes de telecomunicaciones nacionales a un sistema de distribución, del cual la firma o entidad auditora, recibe las imagenes de las actas, y las procesa para generar su versión PDF con firma digital, y la cual se devuelve una copia al repositorio de ditribución, para que lo envíe a la consulta pública, la cual puede ser actualizada de nuevo con los archivos originales en necesidad de restaurar el repositorio. El sistema de distribución se encarga de enviar los archivos a las diferentes aplicaciones de procesamiento, para digitación distibuida, procesamiento por inteligencia artificial, etc. Esos datos se registran en sus propios sistemas y se sincronizan periodicamente al sistema público de consulta, para el analisis de la sociedad en general y el reporte de inconsistencias o precisión entre todas las metodologías de ingreso de datos.

## Proceso Inicial

*Preparativos de Fiscal Digital*
- Registro del Usuario por medio de documento de identificación y número teléfonico
- Registro del Sistema de Procesamiento de Actas

*Fiscales de Mesa*
- Validación del número de teléfono y registro de usuario y clave
- Captura de la Imágen del Acta de la Mesa
- Carga de la Imágen del Acta de la Mea al Sistema vía Web (PWA)

*Auditoría Externa*
- Registro del Certificado de la entidad Auditora
- Autorización por Fiscal Digital
- Recuperación de Imágenes para firma
- Envío de Imágen en PDF con Firma Digital

*Distribución*
- Envío del acta a la Consulta Pública
- Envío del acta a los sistemas de procesamiento

*Procesadores de Actas*
- Reciben el archivo y lo procesan
- Periodicamente envían copia de sus resultados al sistema de distribución
- Sincroniza los datos con la consulta publica

*Publico en General*
- Consulta del resultado oficial según actas en el sitio del Tributal Supremo Electoral
- Consulta de las actas almacenadas en Fiscal Digital
- Consulta de los resultados del TSE y los Procesadores de Actas
- Consulta del reporte de diferencias entre los diferentes procesos 

## Roadmap (Camino a recorrer) ***PROPUESTA*** 

Establecer un proceso para que las actas sean firmadas digitalmente por las juntas receptoras por medio de un algoritmo establecido y una firma digital autorizada previamnte para que la responsabilidad de garantizar que las imagenes cargadas son reales sea asumida por las personas involucradas en las mesas. El Tribunal Supremo Electoral (TSE) sería el responsable de la gestión, un ente auditor es quien revisa y da validez a los certificados digitales usados, el TSE recibe las actas de acuerdo a los certificados no revocados por el ente  auditor, y luego procesa las acta. Fiscal Digital podrá apoyar en proveer el sistema para que en base a este repositorio publico de código sea ejecutado el sistema y garantizar la transparencia del proceso, sin un costo para el estado.

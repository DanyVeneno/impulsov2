# Impulso V2
Sitio estático HTML/CSS/JS, sin dependencias. Servir dist con cualquier servidor HTTP.

## Organización
- index.html y styles.css: estructura y presentación responsive e impresión.
- app.js: funciones V1 conservadas (recorrido, diagnóstico comercial y piloto).
- domain.js: catálogo, fórmulas y modelo del sistema integral; no depende del DOM.
- repository.js: persistencia local y validación de respaldos.
- v2.js: vistas, formularios e informe ejecutivo.

Los datos V1 permanecen en impulso-v1. V2 usa impulso-v2 y schemaVersion 2. El respaldo V2 incluye los datos V1 como legacyV1; importar restaura el sistema integral V2, no reemplaza V1. Los registros son locales, no existe backend ni autenticación de aplicación multiusuario.

## Migración de corto plazo
1. Portar vistas a componentes React/Vue manteniendo el modelo del dominio.
2. Sustituir repository por API con base de datos, autorización por empresa y roles, auditoría y validación del servidor.
3. Incorporar adjuntos de evidencia y colaboración.
4. Crear endpoint de análisis de IA en servidor; las claves son secretos de servidor. Enviar únicamente datos autorizados. Mostrar referencias y supuestos; conservar aprobación humana antes de modificar acciones. El contrato propuesto figura en repository.js. No hay IA activa en esta versión.

## Informe
La sección Informe consolida la información real capturada. Imprimir / guardar PDF utiliza el navegador. Campos pendientes aparecen como tales. La priorización impacto × urgencia / esfuerzo es orientativa (escala 1–5), no una recomendación financiera. Los cambios locales se guardan automáticamente; se recomienda exportar un respaldo.
# impulsov2

==> Modalidad B —>>> DataStage

==> Reglas aplicadas

-Separación de registros válidos y no válidos (conteo por línea de comandos).
Conteo de registros en:
- Extracción
- Transformación
- Control básico de calidad de datos.

==> Para un entorno productivo propondría:

🔹 Parametrización de rutas y conexiones.
🔹 Si se requiere se puede forzar warning del job en caso de desconciliacion de registros
🔹 Tabla de auditoria con:
   	Fecha ejecución
   	Registros leídos
	Registros válidos
	Registros rechazados
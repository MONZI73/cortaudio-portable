# CORTAUDIO Portable

Proyecto preparado para generar un ejecutable portable para Windows.

## Compilación automática

Sube todos los archivos y carpetas de este proyecto a la raíz del repositorio
`MONZI73/cortaudio-portable`. GitHub Actions iniciará la compilación.

Cuando termine, abre **Acciones**, entra en la ejecución más reciente y descarga
el artefacto **CORTAUDIO-Portable-Windows**.

El audio se procesa localmente. La primera transcripción descarga el modelo de
voz y las siguientes reutilizan la copia guardada.

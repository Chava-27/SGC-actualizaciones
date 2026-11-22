# Actualizaciones de SGC

Aquí se publican los instaladores de **SGC - Sistema Gestor de Cuartos**. No hay código fuente: solo los instaladores de cada versión y su manifiesto.

## Para quien usa SGC

No necesita entrar aquí. SGC revisa este repositorio al abrir y en *Sistema → Buscar actualizaciones*. Si hay una versión nueva, avisa en la campana y el Propietario o un Administrador la instala con *Actualizar ahora*.

Si prefiere instalar a mano, descargue `SGC_vNN_instalacion.exe` de la [última versión](../../releases/latest) y ejecútelo en cada computadora. Empiece por la computadora donde está la base de datos (el servidor).

## Qué hay en cada versión

| Archivo | Para qué sirve |
|---|---|
| `SGC_vNN_instalacion.exe` | Instalador de esa versión. |
| `manifiesto.json` | Versión, fecha, notas, tamaño y huella SHA-256 del instalador, firmados con la clave de actualizaciones de SGC. |

SGC solo instala una versión si la firma del manifiesto es válida y la huella del archivo descargado coincide. Nunca instala una versión más vieja que la que ya tiene.

Las versiones marcadas como *pre-release* son pruebas internas: SGC no las ofrece.

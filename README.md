# iECG · Inventario de electrocardiógrafos del SMS

Herramienta interna de trabajo del Servicio Murciano de Salud: el parque de electrocardiógrafos
Philips PageWriter TC de hospitales, SUAP y atención primaria, con su ubicación, su configuración
de red, sus opciones y licencias, el despliegue del flujo nuevo y las incidencias.

**Los datos van cifrados** (AES-256-GCM con clave derivada por PBKDF2-SHA256, 310.000 iteraciones)
y solo se descifran en el navegador al introducir la contraseña. En este repositorio no hay ningún
dato en claro: ni direcciones IP, ni MAC, ni tokens.

- Página: https://idoctor2000.github.io/iecg/
- Los cambios del equipo se guardan cifrados en `estado.json`, en la rama `datos`, y se publican
  con un token personal de GitHub que cada uno introduce una vez en la propia página.

iDoctor@2026

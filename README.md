- ¿Qué importancia tiene probar en múltiples entornos de Node.js? 

Probar en diferentes versiones de Node.js asegura que tu aplicación funcione correctamente en distintos entornos. Ayuda a detectar errores por incompatibilidades, anticipar cambios o deprecaciones, y mantener la estabilidad del proyecto sin importar la versión que se use. Además, mejora la calidad y confianza antes de desplegar a producción.

- ¿Por qué es importante validar la salida de una API desde un workflow? 

Validar la salida de una API desde un workflow es importante porque te ayuda a asegurarte de que todo funciona como debe, cada vez que haces un cambio. Así puedes detectar errores rápido, evitar que algo que antes funcionaba deje de hacerlo, y mantener la calidad sin tener que probar todo a mano. Es una forma inteligente de automatizar y cuidar tu API desde el principio.

- ¿Qué pasos podrías agregar si fueras a hacer despliegue a producción? 

Si fuera a hacer despliegue a producción, agregaría algunos pasos clave para asegurarse de que todo salga bien: primero, revisar que las pruebas hayan pasado; luego, hacer un build optimizado del proyecto. Desplegar a una plataforma AWS y finalmente, verificaría que la app esté corriendo bien y, si es posible, enviaría una notificación al equipo avisando que el despliegue fue exitoso.


- ¿Qué limitaciones tiene GitHub Actions y cómo las enfrentamos?

GitHub Actions es súper útil, pero tiene algunas limitaciones. Por ejemplo, en repos gratuitos hay un límite de minutos de ejecución y recursos por mes. También puede ser complicado manejar secretos o trabajar con entornos muy personalizados. Para enfrentarlo, puedes optimizar los workflows para que corran solo cuando sea necesario, usar runners propios si necesitas más control o potencia, y manejar los secretos con cuidado, usando herramientas como GitHub Secrets.

# Política de privacidad

Última actualización: mayo de 2026

## 1. Introducción

Gracias por utilizar esta aplicación (la “App”). Valoramos mucho su privacidad. Esta Política de privacidad explica cómo recopilamos, utilizamos, almacenamos y compartimos su información personal cuando usa la App.

## 2. Información que recopilamos

### 1) Datos de rendimiento del juego

- Tiempo de desviación: la diferencia entre el momento en que toca el botón de detener y el tiempo objetivo (9,9 segundos) en cada partida, medida con cuatro decimales en segundos, incluyendo valores positivos y negativos.
- Marca de tiempo del juego: la hora en que se completó cada partida.
- Información de clasificación: calificaciones generadas según su desviación (Perfect / Master / Expert / Good / Miss) y si acertó la desviación perfecta (Perfect Hit).

### 2) Información del dispositivo

- Modelo del dispositivo (por ejemplo, iPhone 15 Pro): se utiliza para analizar el rendimiento en diferentes dispositivos.
- Versión del sistema operativo (por ejemplo, iOS 18.0): se utiliza para análisis de compatibilidad y estadísticas.
- Identificador único del dispositivo: un UUID generado automáticamente por el sistema y almacenado localmente, que se usa para identificar el mismo dispositivo a lo largo de varias sesiones del juego. No se sube al servidor a menos que decida enviar una puntuación a la tabla de clasificación.

### 3) Información que usted proporciona voluntariamente

- Apodo: opcional, puede completarse al enviar una puntuación a la tabla de clasificación. Si se deja vacío, el sistema mostrará “Anonymous”. Su apodo se envía junto con los datos de la puntuación al servidor de la tabla de clasificación.

### 4) Preferencias de la aplicación (solo almacenadas localmente)

- Estado del sonido
- Estado de la respuesta háptica
- Preferencia de idioma
- Fecha del primer inicio

Estas configuraciones solo se almacenan en su dispositivo y no se suben a ningún servidor.

## 3. Cómo utilizamos su información

1. Función principal: calcular y mostrar su desviación temporal y ofrecer comentarios sobre la calificación del juego.
2. Almacenamiento local: guardar el historial de partidas en su dispositivo mediante Core Data.
3. Servicio de clasificación: con su consentimiento, enviar resultados del juego (desviación, calificación, apodo, modelo del dispositivo, versión del sistema) al servidor de la clasificación en la nube para que usted y otros puedan consultarlos.
4. Identificación del dispositivo: usar el UUID local como marcador de identidad para distinguir registros entre dispositivos.
5. Mejora del producto: analizar estadísticas anónimas para optimizar la experiencia del usuario.

## 4. Declaración sobre la función de audio

Esta App utiliza las siguientes tecnologías relacionadas con el audio:

| Tecnología | Propósito | ¿Se requiere permiso del micrófono? |
| --- | --- | --- |
| AVAudioSession | Configurar la sesión de audio y permitir la coexistencia con otras apps de audio (modo de mezcla) | No |
| AVAudioEngine / AVAudioPlayerNode | Reproducir efectos de sonido dentro de la app (cuenta atrás, latido, parada, golpe perfecto, mensajes de error) | No |
| CoreHaptics | Proporcionar respuesta háptica (vibración) | No |

Aviso importante: esta App no utiliza el micrófono ni recopila ningún dato de entrada de audio. Todo el audio se reproduce a partir de archivos de sonido integrados en la app, y no se requiere autorización del micrófono.

En la declaración de permisos de la App Store, el permiso de audio declarado por esta App está limitado a la gestión de la sesión de audio del sistema y no implica captura del micrófono. La app solo reproduce efectos de sonido integrados y no accede ni registra la entrada de audio del usuario.

## 5. Compartición y divulgación de información

No venderemos, alquilaremos ni compartiremos su información personal con terceros.

La única excepción es que, si decide enviar una puntuación a la tabla de clasificación, sus datos del juego se transmitirán a nuestro servidor en la nube (Supabase). El proveedor del servidor cumple con la normativa aplicable de protección de datos y hemos tomado medidas razonables para garantizar la seguridad de sus datos.

## 6. Almacenamiento y conservación de datos

- Datos locales: su historial de juego se almacena de forma permanente en su dispositivo. Puede borrar el historial desde la configuración de la aplicación.
- Datos en la nube: las puntuaciones de la tabla de clasificación se almacenan en el servidor de Supabase y se conservan según un límite diario de envíos. Las puntuaciones que superen el límite no se enviarán, pero esto no afectará a sus registros locales.
- Limpieza de datos: cuando el número de registros locales supera 1.000, el sistema elimina automáticamente los registros más antiguos para liberar espacio de almacenamiento.

## 7. Sus derechos

De acuerdo con la legislación aplicable de protección de datos, usted tiene los siguientes derechos:

1. Derecho de acceso: puede consultar en cualquier momento sus datos personales generados en la App.
2. Derecho de rectificación: corregir información inexacta (por ejemplo, un apodo).
3. Derecho de eliminación: solicitar la eliminación de sus registros de puntuación del juego.
4. Derecho a retirar el consentimiento: puede decidir no enviar puntuaciones a la tabla de clasificación en cualquier momento, y esta decisión no afectará al uso continuado de las funciones principales de la App.
5. Derecho de oposición: si considera que el tratamiento de sus datos personales es inadecuado, puede oponerse.

Para ejercer estos derechos, por favor contáctenos en yufei.cjn@outlook.com.

## 8. Seguridad de los datos

Tomamos medidas técnicas y organizativas razonables para proteger su información personal, incluyendo:

- Uso de HTTPS para cifrar todas las transmisiones de red
- Implementación de seguridad a nivel de fila (RLS) en el servidor para restringir el acceso a los datos
- Cifrado del almacenamiento local de datos

Sin embargo, no podemos garantizar una seguridad absoluta en la transmisión por Internet. Por favor, guarde adecuadamente su información personal.

## 9. Protección de menores

Esta App está dirigida a usuarios de todas las edades. Para los usuarios menores, recomendamos que la utilicen bajo la supervisión de un tutor. No recopilamos intencionadamente información personal de menores. Si detectamos la recopilación de información de menores sin el consentimiento de sus tutores, la eliminaremos lo antes posible.

## 10. Actualizaciones de la política

Podemos actualizar esta Política de privacidad de vez en cuando. Las políticas actualizadas se anunciarán en la App o se le comunicarán por otros medios apropiados. Le recomendamos que revise esta política periódicamente para comprender cómo protegemos su información.

## 11. Contacto

Si tiene preguntas, comentarios o sugerencias sobre esta Política de privacidad, o si desea ejercer sus derechos sobre los datos, contáctenos a través de:

- Correo electrónico: yufei.cjn@outlook.com

Responderemos lo antes posible después de recibir su solicitud.

---

Esta Política de privacidad entra en vigor desde la fecha de publicación. Gracias por su confianza y apoyo.

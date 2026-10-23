# Control por MQTT

Publica órdenes digitales y un valor analógico mediante MQTT.

- Entrada: Botones ON/OFF o valor de 0 a 100.
- Resultado: Mensajes JSON publicados en los tópicos de control configurados.
- Tecnología: Paho MQTT · JSON

## Uso

Con el receptor preparado, usa ON/OFF o ajusta el valor y pulsa Enviar valor analógico.

## Límites

Requiere un broker y un receptor disponibles. Publicar un mensaje no confirma que el dispositivo lo haya ejecutado.

## Evidencia de ejecución

La ficha describe el funcionamiento del código. Una ejecución del modelo o una conexión a un dispositivo debe documentarse con su entrada, resultado observado y captura real; no se presentan resultados simulados como evidencia académica.

[Demo](https://sendcmqtt-mdrghytcblpjzstjsqupkm.streamlit.app/) · [Código](https://github.com/Jhuza/send_cmqtt)

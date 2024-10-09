# Análisis del Perfil de LinkedIn de Inverbyte

Este proyecto realiza un análisis detallado del perfil de LinkedIn del dueño de Inverbyte. Utilizando herramientas de análisis de datos como Python y pandas, se extraen insights para optimizar su presentación profesional y destacar aspectos clave del perfil en la plataforma. El resultado del análisis se presenta en un Dashboard interactivo en Tableau.

## Tabla de Contenidos
- [Descripción del Proyecto](#descripción-del-proyecto)
- [Tareas Realizadas](#tareas-realizadas)
- [Descripción de los Datos](#descripción-de-los-datos)
- [Resultados](#resultados)
- [Contribución](#contribución)
- [Licencia](#licencia)
- [Contacto](#contacto)

## Descripción del Proyecto
El proyecto se inició con la entrega de 38 datasets por parte del dueño de Inverbyte. Después de revisar el contenido de cada uno, se seleccionaron los datasets con la mayor cantidad de información relevante. El análisis se centró principalmente en el dataset `messages`, que contenía información sobre las conversaciones mantenidas a través de LinkedIn.

## Tareas Realizadas
1. **Revisión de los datasets**: De los 38 datasets proporcionados, se identificaron aquellos que contenían la mayor cantidad de datos útiles.
2. **Selección del dataset principal**: El dataset `messages` fue seleccionado para un análisis más profundo, ya que incluía información detallada de las conversaciones.
3. **Análisis de los datos**: Se utilizaron Python y pandas para limpiar y procesar el dataset, obteniendo insights relevantes sobre las interacciones.
4. **Visualización de los resultados**: Los resultados del análisis se presentaron en un Dashboard interactivo en Tableau, que incluye:
   - Nube de palabras con las más repetidas en los mensajes.
   - Top de remitentes más frecuentes.
   - Duración de las conversaciones.
   - Frecuencia de mensajes a lo largo del tiempo.

## Descripción de los Datos
El dataset `messages` contiene los siguientes campos:

- **CONVERSATION ID**: Identificador único de cada conversación.
- **CONVERSATION TITLE**: Título de la conversación, si está disponible.
- **FROM**: Nombre de la persona que envió el mensaje.
- **SENDER PROFILE URL**: Enlace al perfil de LinkedIn del remitente.
- **TO**: Nombre del destinatario del mensaje.
- **RECIPIENT PROFILE URLS**: Enlace al perfil de LinkedIn del destinatario.
- **DATE**: Fecha y hora en que se envió el mensaje, en formato UTC.
- **SUBJECT**: Asunto del mensaje (generalmente vacío en las conversaciones).
- **CONTENT**: Texto del mensaje.
- **FOLDER**: Indica si el mensaje se encuentra en la bandeja de entrada (INBOX) u otra carpeta.

El dataset contiene información valiosa para entender las interacciones de la persona analizada, como la frecuencia de las conversaciones, los temas discutidos, y las personas con las que se conecta más a menudo.

## Resultados
Los resultados del análisis se resumen en un Dashboard interactivo creado en Tableau, que incluye:
1. **Nube de Palabras**: Muestra las palabras más repetidas en los mensajes, proporcionando insights sobre los temas más discutidos.
2. **Top de Remitentes**: Lista de los remitentes más frecuentes en las conversaciones.
3. **Duración de las Conversaciones**: Tiempo promedio de duración de las conversaciones en LinkedIn.
4. **Frecuencia de Mensajes**: Gráfico que muestra cómo varía la cantidad de mensajes enviados a lo largo del tiempo.

## Contribución
Las contribuciones son bienvenidas. Si tienes alguna sugerencia, abre un **issue** o envía un **pull request**.

## Licencia
Este proyecto se encuentra bajo la licencia MIT.

## Contacto
Para más información, contacta a [Nombre del Responsable](mailto:correo@ejemplo.com).

Para nuestro espacio en vivo, queremos que pruebes tus habilidades de documentación!

1. Crea un documento, puede ser en Notion, Google Drive, README.md, o el formato que prefieras.
2. Este documento deberá llevar los pasos necesarios para conectar nuestra API a una base de datos en MongoDB Atlas.
3. Puedes incluir imágenes, texto, GIFs, mapas interactivos.
4. La idea es probar juntos estos pasos en nuestro espacio en vivo y entregar feedback y recomendaciones sobre documentación.

### 06. DESAFÍO TÉCNICO

- Objetivo
    
    Desarrollar una API RESTful en **TypeScript** utilizando **Express** que actúe como un proxy entre los feeds RSS de El País y los consumidores de la API. 
    
    Esta API debe:
    
    1. Consumir y transformar datos XML de múltiples feeds RSS de El País.
    2. Enriquecer la información con metadatos adicionales.
    3. Almacenar los datos transformados en **MongoDB**.
    4. Exponer endpoints para consultar y filtrar las noticias, implementando paginación.
    5. Documentar la API utilizando **Swagger**.
    6. Implementar pruebas automatizadas para garantizar la calidad del código.
    7. Desplegar la aplicación en un entorno accesible públicamente.

    Utiliza los siguientes feeds RSS como fuentes de datos, la informacion se encuentra en formato XML:

- **Chile**: https://feeds.elpais.com/mrss-s/pages/ep/site/elpais.com/section/chile/portada
- **Argentina**: https://feeds.elpais.com/mrss-s/pages/ep/site/elpais.com/section/argentina/portada
- **México**: https://feeds.elpais.com/mrss-s/pages/ep/site/elpais.com/section/mexico/portada
- **Tecnología**: https://elpais.com/rss/tecnologia/portada.xml[El País+1El País+1](https://elpais.com/rss/tecnologia/portada.xml?utm_source=chatgpt.com)

Puedes encontrar más feeds en la página oficial de RSS de El País: https://elpais.com/info/rss/

- 🛠️ Requisitos Técnicos
    
    ### 1. Consumo y Transformación de Feeds RSS
    
    - Implementar un proceso que consuma los feeds RSS en formato XML.
    - Transformar el XML a JSON.
    - Extraer los siguientes campos de cada noticia:
        - Título de la noticia
        - Enlace de la noticia
        - Descripción de la noticia
        - Fecha de publicación de la noticia
        - Imagen (si está disponible) de la noticia
        - Sección o categoría de la noticia

        
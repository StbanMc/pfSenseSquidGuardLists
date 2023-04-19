# 🛡️ pfSenseSquidGuardLists

pfSenseSquidGuardLists es un repositorio comunitario de listas negras y blancas de URLs 🌐 para su uso con SquidGuard en pfSense.

## ❓ ¿Qué es pfSenseSquidGuardLists?

Este proyecto tiene como objetivo proporcionar un conjunto actualizado y fácil de usar de listas negras 🚫 y blancas ✅ de URLs para ayudar a los administradores de redes que utilizan pfSense y SquidGuard a filtrar contenido inapropiado o no seguro en sus redes. Las listas están organizadas en categorías 📁 y son mantenidas por la comunidad, lo que permite a los usuarios colaborar y mejorar continuamente las listas.

## 🧩 ¿Cómo funciona?

pfSenseSquidGuardLists contiene listas negras 🚫 y blancas ✅ de URLs organizadas por categorías. Cada categoría tiene archivos de dominios y URLs separados para facilitar su configuración en SquidGuard dentro de pfSense.

Los usuarios pueden contribuir al proyecto agregando ➕, eliminando ➖ o modificando ✏️ entradas en las listas negras y blancas. Las actualizaciones periódicas 🔄 son esenciales para garantizar que las listas sean efectivas y precisas.

## 🎯 ¿Para qué sirve?

pfSenseSquidGuardLists sirve como un recurso para administradores de redes que buscan implementar políticas de filtrado de contenido en sus redes utilizando SquidGuard en pfSense. Las listas negras y blancas de este repositorio pueden utilizarse para bloquear 🚫 o permitir ✅ el acceso a sitios web específicos o categorías de sitios web.

## ⚙️ Configuración

Para utilizar las listas de pfSenseSquidGuardLists con SquidGuard en pfSense, sigue estos pasos:

1. Clona el repositorio 📦 o descarga y extrae los archivos del proyecto en tu servidor pfSense.
2. Configura SquidGuard para utilizar las listas de pfSenseSquidGuardLists. Edita el archivo de configuración de SquidGuard (generalmente accesible a través de la interfaz web de pfSense) y actualiza las rutas de las listas negras y blancas con las rutas de los archivos descargados.
3. Comprueba y aplica la configuración de SquidGuard ✅ y reinicia el servicio de Squid en pfSense a través de la interfaz web o utilizando comandos apropiados en la línea de comandos.
4. Asegúrate de mantener las listas actualizadas 🔄 utilizando el script `update_lists.sh` incluido en la carpeta `scripts` o mediante tus propios métodos.

## 🤝 Contribuir

Agradecemos la colaboración de la comunidad para mantener y mejorar las listas de pfSenseSquidGuardLists. Si deseas contribuir, por favor sigue las pautas de contribución y realiza tus cambios en una rama separada antes de enviar una solicitud de extracción (pull request).

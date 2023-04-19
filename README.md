# 🛡️ pfSenseSquidGuardLists

pfSenseSquidGuardLists is a community-driven repository of URL blacklists and whitelists 🌐 for use with SquidGuard in pfSense.

## ❓ What is pfSenseSquidGuardLists?

This project aims to provide an up-to-date and easy-to-use set of URL blacklists 🚫 and whitelists ✅ to help network administrators using pfSense and SquidGuard filter inappropriate or unsafe content on their networks. The lists are organized into categories 📁 and are maintained by the community, allowing users to collaborate and continually improve the lists.

## 🧩 How does it work?

pfSenseSquidGuardLists contains URL blacklists 🚫 and whitelists ✅ organized by categories. Each category has separate domain and URL files to facilitate their configuration in SquidGuard within pfSense.

Users can contribute to the project by adding ➕, removing ➖, or modifying ✏️ entries in the blacklists and whitelists. Periodic updates 🔄 are essential to ensure the lists are effective and accurate.

## 🎯 What is it for?

pfSenseSquidGuardLists serves as a resource for network administrators looking to implement content filtering policies in their networks using SquidGuard in pfSense. The blacklists and whitelists in this repository can be used to block 🚫 or allow ✅ access to specific websites or categories of websites.

## ⚙️ Configuration

To use the lists from pfSenseSquidGuardLists with SquidGuard in pfSense, follow these steps:

1. Clone the repository 📦 or download and extract the project files to your pfSense server.
2. Configure SquidGuard to use the lists from pfSenseSquidGuardLists. Edit the SquidGuard configuration file (usually accessible through the pfSense web interface) and update the blacklists and whitelists paths with the paths of the downloaded files.
3. Check and apply the SquidGuard configuration ✅ and restart the Squid service in pfSense through the web interface or using appropriate commands in the command line.
4. Ensure you keep the lists updated 🔄 using the `update_lists.sh` script included in the `scripts` folder or through your own methods.

## 🤝 Contributing

We appreciate community collaboration in maintaining and improving the lists in pfSenseSquidGuardLists. If you wish to contribute, please follow the contribution guidelines and make your changes in a separate branch before submitting a pull request.

---------------------------------------------------------------------------------------

# 🛡️ pfSenseSquidGuardLists (Español)

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

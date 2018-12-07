# Mailing Boilerplate

Template que ayudara a la creación rápida de Mailing para cualquier cliente, mediante el uso de componentes pre-fabricados, dando libertad de costumizacion segun las necesidades.

## Configuración Previa

Para crear los templates deseados, primero se debe configurar el entorno de trabajo para que pueda funcionar todo al 100%. Se debe instalar [MJML Framework](https://mjml.io/) para que se puedan compilar los archivos .mjml 

Para la instalación:

*Instalar via NPM de forma global el framework.* 

    $ npm install -g mjml

Una vez instalado se debe instalar localmente

    $ npm init -y && npm install mjml
Ya con esta configuración deberia correr los comandos basicos de MJML. En caso contrario ejecutar el siguiente comando via YARN:

    $ yarn install mjml
Por ultimo, en la terminal ubicarse en la carpeta del boilerplate. Ejemplo:

    ~/Escritorio/mailing-boilerplate$

## Creando Templates

En la estructura del proyecto se encontrara una carpeta de componentes donde se podrán costumizar e importar al index.mjml mediante el uso del tag mj-include:

    <mj-include path="./components/header" />

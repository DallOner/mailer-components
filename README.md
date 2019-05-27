# Mailer Components

Template that will help the rapid creation of Mailing for any client, through the use of pre-fabricated components, giving freedom of customization according to the needs.

## Previous Set-up!

To create the desired templates, you must first configure the work environment so that everything can work 100%. You must install [MJML Framework](https://mjml.io/) so that the .mjml files can be compiled.

Installation:

*Install MJML framework via NPM in a global way.*

    $ npm install -g mjml

Once installed it must be installed locally.

    $ npm init -y && npm install mjml
Already with this configuration should run the basic commands of MJML. Otherwise, execute the following command via YARN:

    $ yarn install mjml
Finally, in the terminal located in the boilerplate folder. Example:

    ~/Escritorio/mailing-boilerplate$

## Creating Templates

In the structure of the project you will find a folder of components where you can customize and import the index.mjml by using the mj-include tag:

    <mj-include path="./components/header" />

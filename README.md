## Requisitos

- Node.js (v14 o superior recomendado)
- npm (v6 o superior recomendado)

## Instalación

Clona este repositorio:
   git clone (https://github.com/oesanchez/prueba.git)
Navega a la carpeta del proyecto:
  cd cypress-e2e-framework

Instala las dependencias necesarias:
  npm install

Ejecución de las Pruebas
Para abrir la interfaz gráfica de Cypress y ejecutar las pruebas:
  npm run cypress:open
  
Para ejecutar las pruebas en modo headless (sin interfaz gráfica):
  npm run cypress:run

Estructura de Archivos
cypress/e2e/userTests.feature: Archivo de pruebas en formato Gherkin.
cypress/e2e/users.spec.js: Archivo de pruebas en JavaScript para casos específicos.
cypress/fixtures/automatizacion.json: Archivo de ejemplo de datos para pruebas (opcional).

NOTA: Los comandos `npm run cypress:open` y `npm run cypress:run` deben estar definidos en tu archivo `package.json` para ejecutar Cypress correctamente.


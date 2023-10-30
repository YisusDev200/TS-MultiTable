# TS-MultiTable

Esta es una sencilla aplicación de consola construida en TypeScript que genera tablas de multiplicar. Simplemente proporciona un número base y, opcionalmente, un límite, y la aplicación creará un archivo con la tabla de multiplicar correspondiente.

- Sigue una arquitectura limpia y es fácil de usar.

## Instalación

Para ejecutar este proyecto en tu máquina local, sigue estos pasos:

1. Clona este repositorio en tu máquina local.
2. Instala las dependencias: `npm install`

## Uso

Para ejecutar la aplicación, utiliza el siguiente comando:

`npx ts-node ./src/app.ts -b 5`

1. -b (obligatorio): Define la base para la tabla de multiplicar.
2. -l (opcional): Define el límite para la tabla de multiplicar. Si no se proporciona, se asume un valor predeterminado. (10)
3. -s (opcional): Muestra la tabla de multiplicar en la consola.
4. -n (opcional): Define el nombre del archivo donde se guardará la tabla de multiplicar.
5. -d (opcional): Define la ubicación donde se guardará el archivo.

### Ejemplo:

`npx ts-node ./src/app.ts -b 5 -l 10 -s -n tabla.txt -d ./archivos`

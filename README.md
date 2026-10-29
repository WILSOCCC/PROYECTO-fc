# Fundamentos de Computación

# Prof. Ubaldo Narvaéz Montoya

## Integrantes:

- Wilberth Yussef Solís Cruz(Líder)
- Daniel Josias Chan Osalde
- Guillermo de Jesús Canto Dzul

## Grupo 1-A

### I. Problemática

En el tecnológico de software existe una tienda informal que ofrece productos con un sistema
de honor, es decir, el dueño no está presente a la hora de la venta y, por lo tanto, se confía en
que el cliente será honesto y pagará la cantidad exacta de dinero; a su vez, los clientes no
siempre traen cambio exacto o dinero en efectivo. Aunque no podemos solucionar la parte de
responsabilidad social por completo, creemos que añadir una forma de pago extra por medio
de transferencia interbancaria, un método muy usado hoy en día, podría reducir la frecuencia
de abuso del sistema actual y, al mismo tiempo, ofrecer una forma adicional al usuario de esta
para hacer su compra.

## II. Objetivo y propuesta de solución.

Nuestro objetivo es añadir transferencias interbancarias como una nueva forma de pago que facilite el pago exacto al usuario, aumente las ventas al aumentar las opciones del usuario y ayude al administrador de la tienda al disminuir casos donde se paga menos de lo solicitado.

La propuesta consiste en la creación de un código QR que al escanearlo redirija al cliente a un formulario en el que visualizará la información requerida para la transferencia; deberá también seleccionar lo que compró, ver su total y adjuntar el comprobante de la transferencia. Esa información se enlazará a una base de datos para su visualización y posterior confirmación por el encargado.

## III. Definición del alcance.

- **Se incluye:**
  - Generación de código QR estático que dirija a los usuarios a un formulario de pago.
  - Desarrollo del formulario donde el usuario pueda visualizar los datos para la transferencia interbancaria, seleccionar los productos consumidos y adjuntar su comprobante de pago.
  - Funcionalidad para adjuntar el comprobante de transferencia.
  - Creación de una base de datos con los comprobantes, las fechas y los artículos consumidos.
  - Creación de una utilidad de visualización básica, para que el administrador (el dueño) pueda consultar las transacciones que se hicieron de esta manera y ver qué artículos se consumieron.

### IV. Distribución de actividades

1. **Frontend**: Guillermo Canto.
Creación del formulario y su correspondiente diseño, además de la generación del código QR.


2. **Backend**: Daniel Chan.
Enlazar las entradas del formulario a la herramienta que se utilizará como base de datos.

3. **Base de datos**: Wilberth Solís.
Desarrollo de la base de datos para que la información obtenida sea fácil de visualizar por el administrador.
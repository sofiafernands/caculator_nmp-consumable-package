# Calculadora

Este paquete proporciona funciones para realizar operaciones aritméticas básicas: suma, resta, multiplicación y división.

## Instalación

Para instalar este paquete, puedes usar npm:

```bash
npm install caculator_nmp-consumable-package

Uso

const { suma, resta, multiplicacion, division } = require('caculator_nmp-consumable-package');

Luego, puedes usar las funciones para realizar operaciones aritméticas:

let resultado = suma(5, 3);  // resultado es 8
resultado = resta(5, 3);  // resultado es 2
resultado = multiplicacion(5, 3);  // resultado es 15
resultado = division(6, 3);  // resultado es 2

Ten en cuenta que la función de división lanzará un error si intentas dividir por cero:

resultado = division(5, 0);  // Lanza un error: "No se puede dividir por cero"

Licencia
Este paquete está licenciado bajo la licencia MIT.




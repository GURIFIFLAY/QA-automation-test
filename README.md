# QA-automation-test
Respuesta al challenger

Paso a realizar la explicacion del razonamiento utilizado en ambos puntos 

Para el diseño de casos de prueba, me base en la particion de equivalencia en todos los test case (pense en usar valores fronteras para los request con id, pero no encontre info clara de los limites, solo supuestos)

Gracias a la implementación de partición de equivalencia podemos validar gran parte del happy pass en 1 o 2 test case -dependiendo las variables-.

Luego para los test realizados en postman decidi validar el JsonSchema mediante tiny validator, status code, payload.

Para los request con id, agregue una validacion de este mismo id , ya que es el unico dato con valor que poseo

Al ser una api dummy desde mi punto de vista no require mucho dimensionamiento  

Ante cualquier duda o consulta estoy a su disposicion.

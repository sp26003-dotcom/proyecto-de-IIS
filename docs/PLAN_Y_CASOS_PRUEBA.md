---Titulo_LLENADO DE FORMULARIO DE ENVÍO DE MENSAJE EXITOSO---
---Numero: A1
---Version: 2.1
---Ambiente: Produccion
---Responsable: EVELYN VILLALTA
---Dispositivo: Laptop on Windows 10
---Datos de prueba: 
                   email: "evelynvillaltadevelasco@gmailcom"
                   contact name: "Evelyn Villalta"
                   message: Mas información del producto
Al completar los datos del el formulario  el envío   es exitoso

---Titulo_LLENADO DE FORMULARIO  DE ENVÍO OMITIENDO CORREO ELECTRÓNICO---
---Numero: A2
---Version: 2.1
---Ambiente: Produccion
---Responsable: EVELYN VILLALTA
---Dispositivo: Laptop on Windows 10
---Datos de prueba: 
                   email: Vacio
                   contact name: "Evelyn Villalta"
                   message: Mas información del producto
Al no completar el campo email que es obligatorio el formulario de envio siempre se realiza con éxito .es un bug.

---Titulo_CARRITO CON UNA COMPRA EXITOSA--
---Numero: A3
---Version: 2.1
---Ambiente: Produccion
---Responsable: EVELYN VILLALTA
---Dispositivo: Laptop on Windows 10
---Datos de prueba: 
                   Seleccionar: galaxy s6  $360
                   Name: Benjamin Velasco
                   Contry: El Salvador 
                   City: San Salvador
                   Credit card: 4344 3545 2345 5678
                   Month: september
                   Year: 2023
Al seleccionar un producto, y adicionarlo al carrito, nos despliega formulario para completar datos de entrada para la compra al rellenar todos los datos la compra es exitosa.

---Titulo_CARRITO DE COMPRA NO COMPLETANDO DATOS OBLIGATORIOS CREDIT CARD---
---Numero: A4
---Version: 2.1
---Ambiente: Produccion
---Responsable: EVELYN VILLALTA
---Dispositivo: Laptop on Windows 10
---Datos de prueba: 
                   Seleccionar: galaxy s6  $360
                   Name: Benjamin Velasco
                   Contry: El Salvador 
                   City: San Salvador
                   Credit card: Vacio
                   Month: september
                   Year: 2023
Al realizar todo el proceso de compra y omitir uno de sus campos mandatorios que son name y credit card, que en este caso fue credit card la compra no es procesada 







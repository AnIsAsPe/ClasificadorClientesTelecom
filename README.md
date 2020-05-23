# ClasificadorClientesTelecom
Análisis para la retención de clientes de una empresa de telecomunicaciones

Se utiliza el algoritmo de arbol de decision para obtener un arbol de decisión para entender las características más relevantes para la retension de clientes de una empresa de telecomunicaciones.
El conjunto de datos se tomó de Kaggle https://www.kaggle.com/blastchar/telco-customer-churn. Éste cuenta con 7,043 renglones y 21 columnas.

Cada renglón representa un cliente y cada columna un atributo de éstos, considerando:
- características socidemograficas: sexo, si tienen pareja y dependientes económicos
- Información de la cuenta: antiguedad como cliente en la compañía, contrato, forma de pago, monto del pago mensual, etc
- Servicios que recibe: telefono, si tiene multiples líneas, internet, seguridad, respaldos, TV, etc
- Clientes que se abandonaron la compañía en el último mes ('Churn')

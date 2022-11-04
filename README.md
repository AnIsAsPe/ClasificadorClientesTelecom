# ClasificadorClientesTelecom

El presente repositorio se refiere a un curso sobre árboles de decisión, impartido en colaboración con el [Colegio de Matemáticas Bourbaki](https://www.colegio-bourbaki.com/) 

Se realiza un análisis para la retención de clientes de una empresa de telecomunicaciones, utilizando árboles de decisión y bosque aleatorio para entender las características más relevantes para la retención de clientes de una empresa de telecomunicaciones.

El conjunto de datos se tomó de Kaggle https://www.kaggle.com/blastchar/telco-customer-churn. Éste cuenta con 7,043 renglones y 21 columnas.

Cada renglón representa un cliente y cada columna un atributo. Entre los atributos se incluyen:
- Características socidemograficas: sexo, si tienen pareja y dependientes económicos
- Información de la cuenta: antiguedad como cliente en la compañía, contrato, forma de pago, monto del pago mensual, etc
- Servicios que recibe: telefono, si tiene multiples líneas, internet, seguridad, respaldos, TV, etc
- Clientes que se abandonaron la compañía en el último mes ('Churn')

En la fase de preprocesamiento, se elimina el ID del cliente, se sustituyen los valors nulos por 0 (solo 11, presentes en la variable TotalCharges), y se realiza una transformación de las variables categóricas en binarias mediante la codificación _One Hot Encoding.


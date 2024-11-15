DataScience-Prediccion-de-precio-de-computadoras


Como parte de mi exploración en el mundo del data science y con la meta de alcanzar la independencia económica,he decidido analizar un conjunto de datos sobre computadoras portátiles. 
Este proyecto surge de mi interés en comprender el comportamiento del mercado de dispositivos electrónicos y, específicamente, en evaluar qué factores influyen en el precio y la 
demanda.
Mi objetivo principal es identificar los modelos y características más populares entre los consumidores, con el fin de tomar decisiones informadas al momento de abastecer mi futura
tienda de computadoras.

Para lograr esto, he formulado las siguientes hipótesis:

H0: Asumo que los productos más caros son los más demandados.

H1: Creo que los equipos más pesados tienden a ser más costosos.

H2: Las notebooks, las gaming y las netbooks son los tipos de computadoras más demandados por los consumidores.

H3: Existe una relación directa entre el precio de una computadora y el tamaño de su pantalla.

H4: A mayor precio, mayor será la capacidad de almacenamiento primario (por ejemplo, SSD).

H5: Un modelo que considere la RAM, el peso y el almacenamiento primario podrá predecir precios arriba de los 1000 euros.

Obtuve este dataset de https://www.kaggle.com/datasets/owm4096/laptop-prices/data y lo componen las siguientes columnas:

Company: Nombre de la compañía 
Product: Nombre específico del modelo del dispositivo.(EJ, MacBook Pro) 
TypeName: Categoría general del dispositivo (Ej, Notebook,etc) 
Inches: Tamaño de la pantalla en pulgadas. 
Ram: Cantidad de memoria RAM en GB. 
OS: Sistema operativo instalado (EJ., Windows, macOS).
Weight: Peso del dispositivo en kilogramos. 
Price_euros: Precio del dispositivo en euros. 
Screen: Tipo de pantalla (EJ., Standard, Full HD). 
ScreenW: Resolución horizontal de la pantalla. 
ScreenH: Resolución vertical de la pantalla. 
Touchscreen: Indica si la pantalla es táctil (Sí/No).
IPSpanel: Indica si la pantalla es IPS (Sí/No). 
RetinaDisplay: Indica si la pantalla es Retina Display (Sí/No). 
CPU_company: Compañía que fabrica el procesador (EJ, Intel, AMD). 
CPU_freq: Frecuencia del procesador en GHz. 
CPU_model: Modelo del procesador (EJ., Core i5, Ryzen 5).
PrimaryStorage: Capacidad de almacenamiento primario en GB. 
SecondaryStorage: Capacidad de almacenamiento secundario en GB. 
PrimaryStorageType: Tipo de almacenamiento primario (EJ., SSD, HDD). 
SecondaryStorageType: Tipo de almacenamiento secundario (EJ., SSD, HDD). 
GPU_company: Compañía que fabrica la tarjeta gráfica. 
GPU_model: Modelo de la tarjeta gráfica.










# Proyecto-de-analisis-de-datos con python, microsoft 
Basado en el tutorial https://learn.microsoft.com/en-us/power-bi/connect-data/desktop-python-visuals
<img width="1152" height="720" alt="python-POWERBI" src="https://github.com/user-attachments/assets/f2306ad3-84b7-4567-b37b-cb3a529553ff" />

Obtener datos - script de python :

### DataFrame a importar: 


``` 
import pandas as pd 
df = pd.DataFrame({ 
    'Fname':['Harry','Sally','Paul','Abe','June','Mike','Tom'], 
    'Age':[21,34,42,18,24,80,22], 
    'Weight': [180, 130, 200, 140, 176, 142, 210], 
    'Gender':['M','F','M','M','F','M','M'], 
    'State':['Washington','Oregon','California','Washington','Nevada','Texas','Nevada'],
    'Children':[4,1,2,3,0,2,0],
    'Pets':[3,2,2,5,0,1,5] 
}) 
print (df)
``` 
NOTA: 
para poder ejecutar cada script de python de cada grafico es necesario que los valores que se usan en cada grafico no esten "resumidos"

### 1 script por grafico

### Grafico de barras
``` import matplotlib.pyplot as plt 
dataset.plot(kind='bar',x='Fname',y='Age')
# plt.title('Grafico de barras') # <- Añade esta línea exactamente aquí 
plt.show()
```

### Gráfico de líneas

```
import matplotlib.pyplot as plt 
ax = plt.gca() 
dataset.plot(kind='line',x='Fname',y='Children',ax=ax) 
dataset.plot(kind='line',x='Fname',y='Pets', color='red', ax=ax) 
# plt.title('Grafico de lineas') # <- Añade esta línea exactamente aquí
plt.show()
```

### Grafico de dispersion 

```
import matplotlib.pyplot as plt 
dataset.plot(kind='scatter', x='Age', y='Weight', color='red', )
# plt.title('Grafico de dispersion') # <- Añade esta línea exactamente aquí
plt.show()
```
## Otros proyectos con  Power BI
### Tablero principal, filtros , transformando datos

 1. [BD CURSOS](https://github.com/lismarcamacho/Proyecto-analisis-de-datos---BD-CURSOS-)

### Vista de informe: Grafico de anillos , grafico de barras 100 % apiladas, segmentacion de datos , tarjeta, Vista de informe : Tablas y matriz

2. [BD FACTURAS](https://github.com/lismarcamacho/Proyecto-de-analisis-de-datos-de-BD-FACTURAS-)

3. [BD GASTOS DE EMPLEADOS](https://github.com/lismarcamacho/BBDD-GASTOS)


### Jerarquia de fechas
- Matriz ,
- Grafico de barras 100% apiladas
- Segmentacion de datos
- Graficos de lineas con leyenda
- Graficos de lineas con multiplos pequeños
- Mapa coropletico
- Interacciones
-4. [BD CURSOS - Intermedio](https://github.com/lismarcamacho/proyecto-intermedio-BD-CURSOS)

### Combinando columnas

5. [BBDD-VENTAS-Y-CODIGOS - Intermedio](https://github.com/lismarcamacho/BBDD-VENTAS-Y-CODIGOS-POWER-BI/blob/main/README.md)

### Anexando columnas, agregando columnas personalizadas
6. [BBDD GASTOS POR DEPARTAMENTO- Intermedio](https://github.com/lismarcamacho/BBDD-GASTOS-POR-DEPARTAMENTO---POWER-BI)

7. [Modelo de Datoa- Intermedio](https://github.com/lismarcamacho/Modelo-de-datos/)

8. [MODELO DE DATOS PEDIDOS PROVEEDOR- Intermedio](https://github.com/lismarcamacho/MODELO-DE-DATOS-PEDIDOS-PROVEEDOR)


9. [Importando carpetas en power bi- Intermedio](https://github.com/lismarcamacho/Carpeta-gastos-mensuales)

10. [Modelo de datos estrella en power bi- Intermedio](https://github.com/lismarcamacho/Modelo-de-datos)

11 [Modelo de datos snow flake power bi- Intermedio](https://github.com/lismarcamacho/Modelo-de-datos-snow-flake)

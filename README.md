
# Analisis de potabilidad de agua | Embotelladora
El análisis se enmarca dentro de un trabajo final para un curso sobre el el lenguaje R. El mismo fue realizado integramente en el software Rstudio. El dataset es totalmente ficticio, generado a fines praácticos. Pero manteniendo el realismo.

1) VERIFICACIÓN DE LA INTEGRIDAD DE LOS DATOS OBTENIDOS
   
   1.A) Variables a analizar y valores:
   - Fecha y hora: producción durante todo el año 2025
   - Línea de producción: Líneas 1, 2 y 3
   - Turno: Mañana, tarde y noche.
   - Temperatura en C° de las muestras: 12,7 - 29,3
   - pH: 5,5 - 8,9
   - Turbidez (NTU): 0 - 4,78
   - Conductividad (uS): 200 - 799
   - Cloro libre (ppm): 0,1 - 1,5
   - Recuento de bacterias (UFC/ml): 0 - 7
   - Calidad de la muestra: Aprobado o de calidad marginal.

  1.B) Registros:
  - 60.000 registros obtenidos, clasificados en muestras "aprobadas" y muestras de "calidad marginal". No hay registros duplicados ni valores faltantes.

 2) ANALISIS DE MUESTRAS CON CALIDAD COMPROMETIDA - EMBOTELLADORA
    
    2.A) ¿En que líneas de producción hay mas muestras de rechazada o de baja calidad?


<img width="900" height="547" alt="Rplot" src="https://github.com/user-attachments/assets/c4186c7e-4a43-418e-bb2e-8d13406a7c19" />

Todas las líneas de producción tienen un numero similar de muestras rechazadas, lo que indica que el problema sería algo general y no particular de cada línea.

    2.B) ¿Influye la época del año en el recuento de bacterias?

<img width="800" height="486" alt="bacterias mes a mes" src="https://github.com/user-attachments/assets/31858f23-b807-4a82-96f5-1b7bea591bfc" />

Se observa que cada dos meses, los niveles de recuento de bacterias tieneden a elevarse y mantenerse por otros dos meses. Quizás este patron pueda eliminarse si se realizara una limpieza mas frecuente en las líneas de producción.

2.C) ¿Influye la época del año en la turbidez del agua?

<img width="437" height="440" alt="turbidez_niveles" src="https://github.com/user-attachments/assets/edaf5a03-3678-45e7-9114-bc61cd06689f" />

En cuanto a la turbidez del agua, un patrón similar se repite: en algunas epocas del año la turbidez del agua es bastante alta, lo que disminuye su potabilidad. Posiblemente, sea necesario cambiar con mayor frecuencia los filtros.

3) CONCLUSIONES
   De las 60.000 muestras recopiladas, 3110 son de calidad dudosa (el 5%). De este porcentaje, el principal problema está en la calidad del agua antes del tratamiento potabilizador. Se observan altos niveles de turbidez y bacterias durante algunos meses seguidos, mientras que luego (por un período similar) no se observan valores extremos.



    

   


    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    




   


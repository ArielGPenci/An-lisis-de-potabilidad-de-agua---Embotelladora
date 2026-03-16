
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

 2) ANÁLISIS EXPLORATORIO DE DATOS
    
    2.A) ¿En que líneas de producción hay mas muestras de rechazada o de baja calidad?


<img width="900" height="547" alt="Rplot" src="https://github.com/user-attachments/assets/c4186c7e-4a43-418e-bb2e-8d13406a7c19" />

Todas las líneas de producción tienen un numero similar de muestras rechazadas, lo que indica que el problema sería algo general y no particular de cada línea.

    2.B)  ¿hay correlcion entre las muestras de calidad baja con la cantidad de cloro, turbidez y conductividad?

                                          <img width="241" height="126" alt="tabla correlaciones" src="https://github.com/user-attachments/assets/e54f2446-5efb-434e-bdf4-b153cb66958b" />


   


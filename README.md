# Proyecto 2 campo profundo

En este proyecto se presenta el análisis del campo profundo del cielo en las
región de (135.5° RA, 0.5° DEC), donde se analizaron las estrellas, galaxias
y cuásares allí presentes. 

Para tal motivo se hicieron dos consultas de ADQL en la región con un radio de 0.5°
alrededor del punto central previamente indicado. Para analizar las galaxias y cuásares
distantes se hizo la consulta al SDSS pidiendo la magnitud de los objetos en las bandas
ultravioleta (u) y visible (g), así como su respectivo redshift (z) para medir su distancia.

Las estrellas por otro lado, fueron consultadas de la base de datos de VizieR, de las
tablas de GAIA para extraero su magnitud visible, su paralaje y movimiento propio, pero
además se pidió la magnitud infrarroja contenida en los archivos de WISE.

Una vez limpios los datos, descartando objetos cercanos o con paralajes dudosos por su
señal-ruido, se elaboraron los diagramas color magnitud correspondientes. Para los objetos
distantes (cuásares y galaxias) se puede observar que las galaxias se ubican en el universo
local mientras que los cuásares están más en el universo temprano.

Ahora bien, las estrellas se descartaron aquellas que estaban muy cercanas a la Tierra, ya
que su paralaje era considerablemente grande, así como también se descartaron objetos lejanos
y con paralajes con mucha incertidumbre. Se llegó entonces a que las estrellas en esa región
estaban aglomeradas en un cúmulo y esto se evidenció por la similaridad en los movimientos
propios de éstas. 

## Declaración de autoría

Para este trabajo, los gráficos presentados fueron hechos sin Inteligencia Artiifical, utilizando
los conceptos aprendidos en el curso y documentándose por medio de la página de Matplotlib.
Las consultas ADQL fueron revisadas en ciertos detalles por la IA debido a unos pequeños 
errores (de redacción) en la elaboración de estas cuando se les probó.

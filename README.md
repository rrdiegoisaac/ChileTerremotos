# <div style="padding:20px;color:white;margin:0;font-size:30px;font-family:Georgia;text-align:left;display:fill;border-radius:5px;background-color:#14213d;overflow:hidden; border-left: 10px solid #fca311;">Acerca del proyecto</div>

<span style="font-size:18px; font-family:Roboto;color:#ac0018"><strong> Contexto</strong> </span>
    
<ul style="list-style-type:circle;">
    <span style='font-size:18px; font-family:Roboto;'>Chile es un país altamente sísmico debido a su ubicación en el Cinturón de Fuego del Pacífico, una región con alta actividad tectónica y sísmica. Esto significa que Chile experimenta una gran cantidad de terremotos y eventos sísmicos a lo largo de los años.<br>
    El objetivo de este proyecto es entender la relación entre variables sísmicas como magnitud y profundidad, así como su distribución temporal y geográfica.</span>
</ul>
 

# <div style="padding:20px;color:white;margin:0;font-size:30px;font-family:Roboto;text-align:left;display:fill;border-radius:5px;background-color:#14213d;overflow:hidden; border-left: 10px solid #fca311;">Conclusiones (También disponibles en el Jupyter Notebook)</div>

<span style="font-size:18px; font-family:Roboto;color:#ac0018"><strong> Correlación entre variables</strong> </span>

<ul style="list-style-type:circle;">
    <span style='font-size:18px; font-family:Roboto;'>La magnitud muestra solo un 12% de correlación con la profundidad. Por otro lado, la variable que más afecta la profundidad es la latitud.</span>
</ul>

<span style="font-size:18px; font-family:Roboto;color:#ac0018"><strong> Distribución de la Magnitud</strong> </span>

<ul style="list-style-type:circle;">
    <span style='font-size:18px; font-family:Roboto;'>La distribución de la magnitud muestra una tendencia asimétrica hacia la izquierda, teniendo una moda cercana a la magnitud 3. Se observan valores atípicos (outliers), especialmente en las magnitudes más altas.</span>
</ul>

<span style="font-size:18px; font-family:Roboto;color:#ac0018"><strong> Distribución de la Profundidad</strong> </span>

<ul style="list-style-type:circle;">
    <span style='font-size:18px; font-family:Roboto;'>La distribución de la profundidad es asimétrica, con una cola derecha más corta que la izquierda. Hay más observaciones en profundidades pequeñas que en grandes. El valor modal se encuentra en los 15 km. Los eventos sísmicos descienden alrededor de los 80 km, pero vuelven a subir a los 100 km, y después, vuelven a descender, lo que refuerza la idea de una distribución multimodal.</span>
</ul>

<span style="font-size:18px; font-family:Roboto;color:#ac0018"><strong> Tendencia Temporal</strong> </span>

<ul style="list-style-type:circle;">
    <span style='font-size:18px; font-family:Roboto;'>Se nota un aumento considerable en la cantidad de eventos sísmicos a través de los años, probablemente asociado a mejoras en la metodología de medición. Los años 2010 y 2017 son los años con más eventos sísmicos registrados.</span>
</ul>

<span style="font-size:18px; font-family:Roboto;color:#ac0018"><strong> Profundidad y Magnitud Promedio</strong> </span>

<ul style="list-style-type:circle;">
    <span style='font-size:18px; font-family:Roboto;'>La profundidad promedio de los terremotos muestra fluctuaciones considerables a lo largo del período analizado. No se observa una tendencia lineal clara en ninguna de las dos variables analizadas. Es importante notar que la magnitud promedio se mantiene relativamente estable, fluctuando alrededor de 3.5 en la escala de Richter.</span>
</ul>

<span style="font-size:18px; font-family:Roboto;color:#ac0018"><strong> Análisis Geográfico</strong> </span>

<ul style="list-style-type:circle;">
    <span style='font-size:18px; font-family:Roboto;'>El análisis geográfico muestra que los eventos sísmicos a mayor profundidad tienden a ocurrir más al Este. Las zonas con alta densidad de terremotos superficiales (Q1 y Q2) son las que presentan un mayor riesgo sísmico para las poblaciones y las infraestructuras. Esto se debe a que los terremotos superficiales suelen causar mayores daños debido a la menor atenuación de las ondas sísmicas, lo que los convierte en un peligro significativo para las áreas afectadas.</span>
</ul>

<span style="font-size:18px; font-family:Roboto;color:#ac0018"><strong> Relación entre Profundidad y Magnitud</strong> </span>

<ul style="list-style-type:circle;">
    <span style='font-size:18px; font-family:Roboto;'>No hay una relación clara y directa entre profundidad y magnitud al observar los boxplots. Todos los cuartiles tienen una altura similar, lo que sugiere que la magnitud promedio de los terremotos es similar en todos los grupos de profundidad.</span>
</ul>

<span style="font-size:18px; font-family:Roboto;color:#ac0018"><strong> Regresión ligera Lineal</strong> </span>

<ul style="list-style-type:circle;">
    <span style='font-size:18px; font-family:Roboto;'>La línea de mínimos cuadrados ordinarios en el gráfico de dispersión demuestra que existe una tendencia ligeramente positiva entre la magnitud y la profundidad. Esto significa que, en promedio, los terremotos de mayor magnitud tienden a ocurrir a mayores profundidades. Sin embargo, esta relación no es muy fuerte y presenta una gran dispersión de los datos. Es importante mencionar que los tres terremotos con mayor magnitud en el dataset ocurrieron a muy poca profundidad.</span>
</ul>

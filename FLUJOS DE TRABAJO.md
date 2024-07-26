# FLUJO DE TRABAJO O CANALIZACIÓN

Las lecturas del secuenciador pasan por herramientas en un orden específico.
![image](https://github.com/user-attachments/assets/d2ac4d12-c263-4b7d-97b9-9f04ce189085)

!! Se utiliza como entrada para otra herramienta sin ninguna configuración extensa. Tener estándares para los formatos de datos es lo que hace que esto sea factible
Los datos se almacenen de una manera que sea generalmente aceptada y acordada dentro de la comunidad.




## 1. Control de calidad: evaluación de la calidad mediante FastQC y recorte y/o filtrado de lecturas (si es necesario)
Evaluar la calidad de lecturas de secuencia en archivos FASTQ
  ### FASTQ
  REGLAS
  1	Siempre comienza con '@' seguido de la información sobre la lectura
2	La secuencia real de ADN
3	Siempre comienza con un '+' y a veces contiene la misma información que en la línea 1
4	Tiene una cadena de caracteres que representan las puntuaciones de calidad; debe tener el mismo número de caracteres que la línea 2
  
   
Ensamblaje del metagenoma
4. Binning
4 Asignación taxonómica


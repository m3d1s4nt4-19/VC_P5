## Práctica 5. Reconocimiento de matrículas


## 5.1 Tarea

Como se pide para el desarrollo de esta tarea, se ha entrenado un modelo de YOLOv8 para que reconozca matrículas, con un dataset de matrículas españolas con varios ángulos y rotaciones. Tras esto, las imágenes recortadas de la matrícula del vehículo se pasan al detector de textos, que lo procesa y si devuelve un resultado válido se muestra en la pantalla.

Cada frame se analiza la imagen para detectar matrículas. Para el detector de textos utilicé funciones separadas para llamar más cómodamente desde cada frame del vídeo. El mayor problema que experimenté fue que el vídeo necesita mucha calidad para poder pasar la imagen de la matrícula y que el texto sea detectado.

![image](https://github.com/m3d1s4nt4-19/VC_P5/assets/132598339/cfc64792-178f-4ee6-ae02-81d3f7e214ca)

## 1. Logica que maneja las solicitudes entrantes.
### Escritura
- Publicar un tweet
- Dar like a un tweet
- Seguir a un usuario

### Lectura
- Visualizacion de datos de tweets
- Visualizacion de datos de usuario


Si tenemos 100 Millones de so

## 2. Almacenamiento de datos persistentes.
#### Tamaño por tweet

- teet_id - 8 bytes
- user_id - 32 bytes
- content - 140 bytes
- media - 10kb
- total 10Kb


"Asumiendo que nuestro diseño es como el Twitter real, cada tweet es de 140 caracteres, los tweets se generan a razón de 10 mil millones por día, lo que se traduce en 115 por cada segundo. Durante 1 año habrá al menos 3,650 millones de tweets, que en 5 años serán 17,800 millones de tweets. Entonces apuntaremos a que nuestra solución pueda almacenar eficientemente estos registros.Si los tweets son de 140 caracteres, entonces 140 $\times$ 17,800 millones serán 2.5 billones de caracteres. Asumiendo 2 bytes por carácter, necesitaríamos $5 \times 10^{12}$ bytes, que es equivalente a 5 TB de almacenamiento.x 17800 millones seran 2.5 billones dew caracteres, asumiendo 2 bytes por caracter, necesaritariamos  5x10^12 bytes
que es equivalente a 5TB de almacenamiento.




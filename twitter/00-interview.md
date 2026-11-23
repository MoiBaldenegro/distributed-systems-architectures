## Aclarando dudas
En este ocasion analizaremos twitter, pero sin saber que es twitter realmente por dentro, 
necesitamos saber mucho más para poder tomar las decisiones adecuadas.

## Cuantos usuarios esperamos que gestione nuestro sistema?
- Debemos apuntar a 10 millones de usuarios que aproximadamente generan 100 millones de solicitudes al dia.
- esperamos a que cada usuario siga a otros 200 usuarios en promedio, esperando usuarios extraordinarios con decenas de miles de seguidores.


## Cuales son las operaciones de escritura principales?.
- Producir nuevos tweets y darles like, seran las operaciones de escritura mas comunes en la aplicacion.

##  Cuantas  solicitudes generaran?
- Aunque es algo dificil 1 tweet por usuario diario me parece un buen numero y en promedio cada uno de estos tenga 5 likes cada uno de estos.

Porsupuesto tambien habra excepciones pero hagamos calculos con la informacion que acabamos de recibir.
El numero promedio de usuarios seguidos es de 100, significa que la red de usuarios tendra al rededor de **200 x 1x10^6** de aristas, es decir **2x10^9** de aristas.

Si el numero promedio de tweets por dia es de **10x10^6**, el numero de de likes seria de  **5x10^6**.

## Que disponibilidad se espera?
 - Se espera que este en linea todo el tiempo.


## Que tiempos de respuesta se espera?
- Se espera un tiempo de respuesta casi inmediato, podemos decir unos cientos de milisegundos.


## Ahora sabemos
- 10 Millones de usuarios.
- 10 Millones de tweets diarios.
- 50 Millones de likes por dia.
- 100 Millones de peticiones HTTP al sitio.
- 2 Mil Millones de follows en relaciones.
- Algunos usuarios y tweets podrian generar cantidades de trafico extraordinarias.


Ahora podemos avanzar con el diseñom de alto nivel.



  




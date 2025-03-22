#PPS-Unidad3Actividad2-InyeccionSQL
Explotación y Mitigación de SQL Injection (SQLi)

Tenemos como objetivo:

> Recordar cómo se pueden hacer ataques de inyección de SQL
>
> Analizar el código de la aplicación que permite inyección SQL
>
> Implementar diferentes modificaciones del codigo para aplicar mitigaciones o soluciones.

---
## ACTIVIDADES A REALIZAR
> Lee el siguiente [documento sobre Explotación y Mitigación de ataques de Inyección SQL](files/ExplotacionYMitigacionSQLInjection.pdf) de Raúl Fuentes. Nos va a seguir de guía para aprender a explotar y mitigar ataques de inyección SQL en nuestro entorno de pruebas.
Vamos realizando operaciones:
### Iniciar entorno de pruebas
-Inicia el entorno de pruebas de nuestro servidor LAMP: `docker-compose up -v`

![](images/sqli1.png)

### Creación de base de datos
Para crear la Base de datos que vamos a utilizar para esta actividad tenemos varias opciones:

**OPCIÓN 3: completamente de manera gráfica**
- Accedemos via web al servicio de phpmyadmin que tenemos instalado: <http://localhost:8080>

![](images/sqli2.png)

- Creamos una base de datos nueva, pulsando el botón de _Nueva_

![](images/sqli3.png)

- Vamos a llamar a la tabla SQLi

![](images/sqli4.png)

- Una vez creada, inmediatamente nos sugiere que creemos una tabla nueva. La tabla que necesitamos se llamará **Usuarios* y debe de tener 3 columnas:**id, nombre y contrasenya**, cada una con su tipo de valor correspondiente.

![](images/sqli6.png)

- Una vez creada podemos introducir los valores de los usuarios que queramos pulsando en **Insertar**

![](images/sqli7.png)
- y introducimos los valores que queremos. 

![](images/sqli8.png)
 

![](images/sqli4.png)
![](images/sqli4.png)
![](images/sqli4.png)

---	
## ENTREGA

>__Realiza las operaciones indicadas__

>__Crea un repositorio  con nombre PPS-Unidad3Actividad3-Tu-Nombre donde documentes la realización de ellos.__

> No te olvides de documentarlo convenientemente con explicaciones, capturas de pantalla, etc.

>__Sube a la plataforma, tanto el repositorio comprimido como la dirección https a tu repositorio de Github.__


GUARDAR DONDE IMAGENES DESPUES

**asdasdsa**
[hola](https://google.es)
![imagenSanic](https://as.com/meristation/imagenes/2019/12/27/videos/1577426311_569791_1577426352_noticia_normal_recorte1.jpg)


    if(noRespeto){
        alert("adios");
    }

|hola   |adios |uno |
| - | - | -:  |
|1      |2  |3      |
|2      |1  |4      |

# Despliegue de aplicación Web con Laravel en Docker:
  
## 1. Paso mas difícil, Instalar laravel :


- Creamos nuestro directorio
- Entramos en él
- Realizamos un git clone de entornods con sudo

![imagen](1.png)


















- Entramos a entornods
- Cambiamos de rama a laravel

![imagen](2.png)













- Levantamos el docker

- Salimos de todos los directorios

![imagen](3.png)


- Entramos a /etc/hosts


![imagen](4.png)

- Introducimos las direcciones con los puertos enseñados


![imagen](5.png)





- Entramos a data
- Clonamos mediante git nuestro laravel





![imagen](6.png)








- Otorgamos permisos sobre la carpeta laravel a todos los usuarios -Nos hacemos dueño del directorio laravel




![imagen](7.png)



- Entramos a laravel
- Realizamos el composer install (si no esta instalado sudo “apt-get install composer”)

- Tras 5 minutos, si no hay ningún error recibirás este mensaje:


![imagen](8.png)


- En la carpeta laravel, copiamos el archivo de configuración y le damos otro nombre a la copia
- Generamos la clave de nuestra aplicación





![imagen](9.png)





- Modificamos dicho archivo

- Volvemos al directorio entornods
- Reiniciamos docker por seguridad



![imagen](10.png)





















- Vamos a nuestro navegador y en laravel.local ya estará nuestro laravel ya operativo.
## 2. Despliegue Final
- Accedemos mediante Atom por ejemplo, en el directorio	routes tenemos el archivo web.php donde pondremos que si el usuario introduce laravel.local/DespliegueLaravel le devolverá una vista con 	“hola que tal”.




![imagen](once.png)

![imagen](12.png)

![imagen](13.png)
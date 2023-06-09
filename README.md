# DockerComposeMoodle.
Proyecto Final Despliegue de un Sistema con Docker.Equipo2


# Instalar Moodle y Crear un curso.

## Moodle y MariaDB.

- Instalación con docker-compose 

## Usuarios y Contraseñas que se deben cambiar en el archivo docker-compose.yml
   
   - MARIADB_USER=bn_moodle
   - MARIADB_PASSWORD=mypassword
    
    - MOODLE_DATABASE_USER=bn_moodle
    - MOODLE_DATABASE_PASSWORD=mypassword


### Correr localmente usando docker.

1. Clonar el repositorio al directorio local de instalación.

    git clone https://github.com/AndreAban619/DockerComposeMoodle.git

2. Para correr los contenedores.

        $cd DockerComposeMoodle

        $docker-compose up -d

3. Para detener los contenedores.

        $docker-compose stop


# Paso 1) Correr Moodle y Crear un curso.

- http://localhost/

- usuario = user
- contraseña = bitnami


![Moodle-Screen01](DockerComposeMoodle/img/imagen1.png)

# Paso 2)Login Moodle. 

- Press Log In button.

![Moodle-Screen02](img/imagen2.png)

# Paso 3) Vamos a my courses 

- click en el botón create course.

![Moodle-Screen03](img/imagen3.png)

# Paso 4) Rellenamos el formulario, en este caso se llama "Curso 1".

![Moodle-Screen04](img/imagen4.png)

# Paso 5) Le damos click a save and display.

![Moodle-Screen05](img/imagen5.png)

# Como podemos observar nuestro curso ya esta publicado.

![Moodle-Screen06](img/imagen6.png)

# Desde la pestaña de home se observa asi.
- Como se puede observar le añadimos una descripción acompañada de una imagen y tambien una imagen representativa del curso.

![Moodle-Screen07](img/imagen7.png)





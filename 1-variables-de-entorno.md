# Variables de Entorno
### ¿Qué son las variables de entorno?
Las variables de entorno son valores dinámicos que informan a los programas y procesos sobre el entorno en el que se están ejecutando. Sirven para personalizar contenedores
# COMPLETAR

### Para crear un contenedor con variables de entorno

```
docker run -d --name <nombre contenedor> -e <nombre variable1>=<valor1> -e <nombre variable2>=<valor2>
```

### Crear un contenedor a partir de la imagen de nginx:alpine con las siguientes variables de entorno: username y role. Para la variable de entorno rol asignar el valor admin.
<img width="771" height="166" alt="image" src="https://github.com/user-attachments/assets/d5ecf6bb-002a-4c07-976b-625df1c2a6f5" />

# COMPLETAR

# CAPTURA CON LA COMPROBACIÓN DE LA CREACIÓN DE LAS VARIABLES DE ENTORNO DEL CONTENEDOR ANTERIOR
<img width="533" height="216" alt="image" src="https://github.com/user-attachments/assets/90c627ff-d33d-4506-8335-9d63fa20c783" />

### Crear un contenedor con la imagen de mysql, mapear todos los puertos
<img width="707" height="88" alt="image" src="https://github.com/user-attachments/assets/d602e327-2dcd-4baf-8293-09e35416613e" />

# COMPLETAR

### ¿El contenedor se está ejecutando?
<img width="1263" height="254" alt="image" src="https://github.com/user-attachments/assets/fceae312-0e12-4df7-b1f2-01d01e1f0ee3" />

# COMPLETAR

### Identificar el problema
# COMPLETAR

### Para crear un contenedor con variables de entorno especificadas
- Portabilidad: Las aplicaciones se vuelven más portátiles y pueden ser desplegadas en diferentes entornos (desarrollo, pruebas, producción) simplemente cambiando el archivo de variables de entorno.
- Centralización: Todas las configuraciones importantes se centralizan en un solo lugar, lo que facilita la gestión y auditoría de las configuraciones.
- Consistencia: Asegura que todos los miembros del equipo de desarrollo o los entornos de despliegue utilicen las mismas configuraciones.
- Evitar Exposición en el Código: Mantener variables sensibles como contraseñas, claves API, y tokens fuera del código fuente reduce el riesgo de exposición accidental a través del control de versiones.
- Control de Acceso: Los archivos de variables de entorno pueden ser gestionados con permisos específicos, limitando quién puede ver o modificar la configuración sensible.

### ¿Qué bases de datos existen en el contenedor creado?
# COMPLETAR

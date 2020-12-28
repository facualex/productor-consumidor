Código para el problema productor-consumidor implementando para el curso de sistemas operativos UTEM

```
Rama de desarrollo: development
Rama de entrega (código final): main
```

# Instrucciones para desarrollo

1. Clonar proyecto ejecutando: 

```
git clone https://github.com/facualex/productor-consumidor.git
```

2. Una vez dentro de la carpeta del proyecto ejecutar: 

```
git checkout -b development # Esto creará la rama de desarrollo en tu computador y te moverá a ella para trabajar ahí
```

3. La idea es no hacer cambios directamente en la rama development si no que sacar una rama DESDE development para la funcionalidad que se vaya a trabajar, por ejemplo, imaginemos que en development hay un código que está funcionando bien, pero falta implementar una funcionalidad, digamos una función para sumar dos numeros, entonces creamos una rama desde development llamada por ejemplo feature/sumarDosNumeros y trabajamos ahi solo en esa funcionalidad. Cuando esté lista se hace una revisión del código por parte del equipo. Para esto se hace un PULL REQUEST a development (una petición para combinar el codigo nuevo de feature/sumarDosNumeros y lo que está en development). Si está todo OK si hace MERGE (se pasa lo de feature/sumarDosNumeros a development)

Una vez ejecutado el paso 2, si queremos sacar una nueva rama DESDE DEVELOPMENT para implementar una funcionalidad nueva hacemos:

```
git checkout -b feature/nombreDeLaFuncionalidad
```

4. Trabajamos sobre nuestra nueva rama del paso 3 normalmente, y cuando queramos subir los cambios que realizamos local en nuestro computador a github (a nuestra rama feature/nombreDeLaFuncionalidad) hacemos:

```
git add .
git commit -m 'Descripción de lo que se hizo' # con comillas
git push # asegurarse que estamos en la rama feature/nombreDeLaFuncionalidad
```

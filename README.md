# Docker


Los contenedores a diferencia de las máquinas virtuales, se caracterizan por ser mucho más livianos. Se usan para ejecutar aplicaciones de forma rápida y confiable en diferentes entornos y ofrecen ventajas como su portabilidad, facilitan el reuso, la integración y el despliegue de aplicaciones además de proporcionar un uso eficiente de recursos. En pocas palabras, los contenedores son unidades de software que empaquetan código y todas sus dependencias que permiten ejecutar paquetes de software independientes (imágenes).

## API Students
La ruta de la API Students es `/student`

BODY para registrar alumnos:
{   
    name: {
        type: String
    },
    surename: {
        type: String
    },
    level: {
        type: Number
    },
    average_grade: {
        type: Number
    }
}

### Recursos

### GET

`/student` --> Entrega todos los registros de la colección students.

`/student/{id}` --> Entrega un registro específico de estudiante por id.

`/student/delete/{id}` --> Elimina un registro específico de estudiante por id.

### POST

`/student/add` --> Crea nuevo registro de estudiante.

`/student/update/{id}` --> Modifica un registro de estudiante por id.

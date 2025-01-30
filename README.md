# 🎉 Bienvenidos a Nuestro Proyecto

## 📑 Tabla de Contenidos
- [🎉 Bienvenidos a Nuestro Proyecto](#-bienvenidos-a-nuestro-proyecto)
  - [📑 Tabla de Contenidos](#-tabla-de-contenidos)
  - [👥 Sobre nosotros](#-sobre-nosotros)
  - [📊 Datos del Proyecto](#-datos-del-proyecto)
  - [🔗 Enlaces](#-enlaces)
    - [📹 Videos de Ejercicios](#-videos-de-ejercicios)

## 👥 Sobre nosotros 
[🔝 Volver a la Tabla de Contenidos](#-tabla-de-contenidos)

<p align="justify">
En este proyecto, buscamos proporcionar una solución innovadora para la gestión de un gimnasio. Nuestro objetivo es ayudar a las personas a realizar deporte de manera eficiente y organizada.
</p>

<p align="justify">
Nuestra aplicación móvil para el gimnasio está diseñada para mejorar la experiencia de nuestros miembros, permitiéndoles gestionar sus rutinas de entrenamiento y seguimiento de progreso de manera eficiente. Con la aplicación, los usuarios pueden:
</p>

- **📅 Reservar clases**: Planificar y reservar clases fácilmente.
- **📹 Acceder a tutoriales**: Ver videos y tutoriales de ejercicios.
- **📊 Monitorear progreso**: Llevar un registro detallado de sus entrenamientos.
- **🔔 Recibir notificaciones**: Obtener recordatorios y alertas personalizadas.

## 📊 Datos del Proyecto
[🔝 Volver a la Tabla de Contenidos](#-tabla-de-contenidos)


<p align="center">
  
```mermaid
erDiagram
        CLASES {
                int id
                string nombre
                string descripcion
                datetime fecha
        }
        USUARIOS {
                int id
                string nombre
                string email
        }
        TUTORIALES {
                int id
                string titulo
                string descripcion
                string url
        }
        NOTIFICACIONES {
                int id
                string mensaje
                datetime fecha
        }
        USUARIOS ||--o{ CLASES: reserva
        USUARIOS ||--o{ TUTORIALES: accede
        USUARIOS ||--o{ NOTIFICACIONES: recibe
```

</p>


## 🔗 Enlaces

[🔝 Volver a la Tabla de Contenidos](#-tabla-de-contenidos)

### 📹 Videos de Ejercicios
<p align="center">
        <a href="https://www.youtube.com/watch?v=CRqZKxKKEAw">
                <img src="https://img.youtube.com/vi/CRqZKxKKEAw/0.jpg" alt="Rutina de bíceps con mancuernas">
        </a>
        <br>
        <strong>Rutina de bíceps con mancuernas</strong>
</p>

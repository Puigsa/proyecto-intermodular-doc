---
title: Uso
nav_order: 4
---

## 🚀 Uso de la plataforma

Esta sección describe cómo interactúan los usuarios con el **Sistema de Gestión Escuela de Música**.

## 👥 Tipos de usuario

| Usuario       | Funcionalidades principales |
|---------------|----------------------------|
| Profesor      | Visualizar grupos de alumnos, publicar recursos educativos, registrar calificaciones |
| Alumno        | Consultar información y calificaciones, gestionar matrícula |
| General       | Acceder a información general de la escuela y calendario de eventos |

## Funcionalidades principales

### 1️⃣ Información general de la escuela
- Consultar plazos de matrícula y requisitos  
- Ver la historia de la institución  
- Consultar el calendario de eventos (audiciones, conciertos, talleres)  
- Contactar con la escuela mediante formulario  

### 2️⃣ Funcionalidades para profesores
- Visualizar los grupos de alumnos asignados  
- Publicar recursos educativos (PDF, enlaces, vídeos)  
- Registrar calificaciones simples por asignatura o instrumento
- Reserva de aulas  

### 3️⃣ Funcionalidades para alumnos
- Consultar información publicada por los profesores  
- Acceder a calificaciones y comentarios  
- Gestionar matrícula para el nuevo curso (estado admitido/no admitido)
- Reserva de aulas 


## 📸 Ejemplo de uso: registrar calificación

### PHP
```php
// Registrar calificación de un alumno
$calificacion = [
  "alumno_id" => 123,
  "materia" => "Guitarra",
  "nota" => 8.5
];
insertarCalificacion($calificacion);

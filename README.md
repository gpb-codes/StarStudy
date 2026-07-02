<div align="center">

# StarStudy

### Plataforma educativa inteligente para la gestión académica, hábitos y gamificación.

<p>
StarStudy centraliza la administración de tareas, horarios, hábitos y comunicación entre estudiantes, docentes, personal administrativo y desarrolladores en una única plataforma.
</p>

</div>

---

## Descripción

StarStudy es una plataforma desarrollada con Django que busca mejorar la organización académica mediante herramientas de productividad, seguimiento de hábitos y un sistema de gamificación.

La aplicación permite que estudiantes, docentes, personal administrativo y desarrolladores trabajen dentro de un mismo entorno, con funcionalidades adaptadas a cada rol.

---

## Características

<table>
<tr>
<td width="50%">

### Gestión de tareas

- Creación de tareas
- Asignación de tareas
- Prioridades
- Seguimiento de progreso
- Estados de tareas
- Filtros

</td>

<td width="50%">

### Gestión de horarios

- Horarios personales
- Horarios por curso
- Organización visual
- Acceso según el rol

</td>
</tr>

<tr>
<td>

### Sistema de hábitos

- Registro diario
- Seguimiento
- Sistema de experiencia
- Niveles
- Misión Principal

</td>

<td>

### Notificaciones

- Recordatorios automáticos
- Avisos de vencimiento
- Confirmación de tareas
- Recordatorios de hábitos

</td>
</tr>
</table>

---

## Sistema de vinculación

Los docentes generan un código único que permite vincular automáticamente a los estudiantes.

Beneficios:

- Asociación profesor-estudiante
- Asignación automática de tareas
- Acceso al horario correspondiente

---

## Gamificación

- Sistema de niveles
- Experiencia
- Misiones
- Seguimiento del progreso
- Incentivos para mantener la constancia

---

## Roles

<table>
<thead>
<tr>
<th>Rol</th>
<th>Descripción</th>
</tr>
</thead>

<tbody>

<tr>
<td><strong>Estudiante</strong></td>
<td>Visualizar tareas, horarios, progreso y notificaciones.</td>
</tr>

<tr>
<td><strong>Profesor</strong></td>
<td>Crear tareas, administrar cursos, gestionar horarios y generar códigos de vinculación.</td>
</tr>

<tr>
<td><strong>Personal</strong></td>
<td>Gestionar tareas internas, horarios y hábitos.</td>
</tr>

<tr>
<td><strong>Programador</strong></td>
<td>Acceso al panel técnico e integración con GitHub.</td>
</tr>

</tbody>
</table>

---

## Tecnologías

<div align="center">

| Backend | Frontend | Base de Datos | Automatización |
|----------|----------|---------------|----------------|
| Django 6 | Bootstrap 5 | SQLite | APScheduler |
| Python 3.13 | HTML5 · CSS3 · JavaScript | | |

</div>

---

## Estructura

```text
StarStudy/
│
├── accounts/
├── tasks/
├── habits/
├── schedules/
├── notifications/
├── templates/
├── static/
├── media/
├── manage.py
└── requirements.txt
```

---

## Instalación

### Clonar el repositorio

```bash
git clone https://github.com/tu-usuario/StarStudy.git
cd StarStudy
```

### Crear entorno virtual

**Windows**

```bash
python -m venv venv
venv\Scripts\activate
```

**Linux / macOS**

```bash
python3 -m venv venv
source venv/bin/activate
```

### Instalar dependencias

```bash
pip install -r requirements.txt
```

### Aplicar migraciones

```bash
python manage.py migrate
```

### Crear administrador (opcional)

```bash
python manage.py createsuperuser
```

### Ejecutar el servidor

```bash
python manage.py runserver
```

Abrir:

```text
http://127.0.0.1:8000/
```

---

## Primeros pasos

### Profesor

1. Crear una cuenta.
2. Generar un código de vinculación.
3. Crear horarios.
4. Asignar tareas.

### Estudiante

1. Registrarse.
2. Ingresar el código del profesor.
3. Consultar tareas.
4. Completar actividades.

### Personal

1. Gestionar tareas.
2. Registrar hábitos.
3. Completar la Misión Principal.

### Programador

1. Conectar GitHub.
2. Acceder al panel técnico.

---

## Roadmap

- [ ] Inteligencia Artificial
- [ ] Calendario inteligente
- [ ] Aplicación móvil
- [ ] Modo offline
- [ ] Integración con Google Calendar
- [ ] Dashboard avanzado
- [ ] Sistema de logros
- [ ] API REST
- [ ] OAuth
- [ ] Chat en tiempo real
- [ ] Exportación de horarios

---

## Contribuir

```bash
# Fork del proyecto

git checkout -b feature/nueva-funcionalidad

git commit -m "feat: nueva funcionalidad"

git push origin feature/nueva-funcionalidad
```

Posteriormente abre un Pull Request.

---

## Reportar errores

Si encuentras algún problema:

1. Abre un Issue.
2. Describe el error.
3. Explica cómo reproducirlo.
4. Adjunta capturas si es necesario.

---

## Licencia

Este proyecto está destinado a fines educativos y de aprendizaje.

Consulta el archivo **LICENSE** para más información.

---

<div align="center">

### Si este proyecto te resulta útil

<strong>Considera darle una estrella al repositorio y contribuir con nuevas ideas o mejoras.</strong>

</div>

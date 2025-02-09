# Odoo-Ejer06

## 📌 Descripción del Proyecto
Este repositorio contiene la implementación de diversos módulos en **Odoo 17** que abarcan diferentes áreas de gestión empresarial, tales como:
- **Gestión de Tareas** (vistas Kanban y Calendar).
- **Gestión de Biblioteca** (préstamos de cómics y socios).
- **Gestión Hospitalaria** (pacientes, médicos y consultas).
- **Gestión Educativa** (ciclos formativos, módulos, alumnos y profesores).

Cada módulo incluye modelos de datos, vistas personalizadas y configuraciones de seguridad para una correcta administración dentro de Odoo.

---

## 🚀 Instalación y Configuración
Para instalar y ejecutar este proyecto en tu entorno de desarrollo Odoo, sigue los siguientes pasos:

### **1️⃣ Clonar el Repositorio**
```bash
git clone https://github.com/CevicheConAji/Odoo-Ejer06.git
cd Odoo-Ejer06
```

### **2️⃣ Copiar los Módulos a Odoo**
Ubica la carpeta de módulos de Odoo y copia los directorios de los módulos dentro:
```bash
cp -r modules/* /ruta/a/odoo/addons/
```

### **3️⃣ Reiniciar el Servidor de Odoo**
```bash
sudo service odoo restart
```

Si estás ejecutando Odoo desde código fuente:
```bash
./odoo-bin --addons-path=/ruta/a/odoo/addons/ -d tu_base_de_datos
```

### **4️⃣ Instalar los Módulos**
Accede a la interfaz de Odoo:
1. **Ir a Apps** → Activar *Modo Desarrollador*.
2. Buscar los módulos y hacer clic en **Instalar**.

---

## 📂 Estructura del Proyecto
```
Odoo-Ejer06/
│── modules/
│   ├── gestion_tareas/  # Módulo de tareas con Kanban y Calendar
│   ├── gestion_biblioteca/  # Préstamos de cómics y socios
│   ├── gestion_hospital/  # Pacientes, médicos y consultas
│   ├── gestion_educativa/  # Ciclos formativos, módulos y seguridad
│── docs/  # Documentación del proyecto
│── README.md  # Descripción del repositorio
```

---

## ⚡ Módulos Implementados

### 📌 **Gestión de Tareas**
- Lista de tareas con vistas **Kanban** y **Calendario**.
- Modelo con estados (`Pendiente`, `En progreso`, `Completado`).
- Restricciones de seguridad según el usuario.

### 📌 **Gestión de Biblioteca**
- Registro de **socios** con identificador único.
- Control de **préstamos de cómics** con validaciones de fechas.
- Vistas de formulario y lista.

### 📌 **Gestión Hospitalaria**
- Modelos de **pacientes**, **médicos** y **consultas médicas**.
- Relación **muchos a muchos** entre médicos y pacientes.
- Validación de datos en la asignación de consultas.

### 📌 **Gestión Educativa**
- **Ciclos formativos** y **módulos educativos**.
- Gestión de **alumnos matriculados** y **profesores**.
- Seguridad implementada para restringir accesos.

---

## 🔐 Seguridad
Cada módulo incluye configuraciones de seguridad en `security/ir.model.access.csv`, permitiendo:
- Acceso restringido a ciertos usuarios.
- Permisos diferenciados para usuarios estándar y administradores.

---

## 🛠️ Tecnologías Usadas
- **Odoo 17** 🏗️
- **Python 3** 🐍
- **XML** (definición de vistas y menús)
- **PostgreSQL** (base de datos)
- **GitHub** (control de versiones)

---

## 📝 Contribuciones
¡Toda contribución es bienvenida! Para colaborar:
1. **Haz un Fork** del repositorio.
2. **Crea una rama** con tu nueva funcionalidad: `git checkout -b feature/nueva-funcionalidad`.
3. **Sube los cambios**: `git commit -m 'Añadida nueva funcionalidad'`.
4. **Haz un Pull Request** 🚀.

---

## 📧 Contacto
Si tienes preguntas o sugerencias, puedes contactarme en:
📌 **GitHub:** [CevicheConAji](https://github.com/CevicheConAji)
📌 **Email:** zavalachirapiero@gmail.com

---

## 📜 Licencia
Este proyecto está bajo la licencia **MIT**. Puedes usarlo libremente bajo los términos establecidos.

📌 *Hecho con ❤️ por CevicheConAji*


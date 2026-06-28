# 🧬 BioBank · Sangre Digital  
**Proyecto de Tecnologías Emergentes**  
Universidad · Ingeniería en Sistemas  

![Vista previa del proyecto](https://via.placeholder.com/800x400?text=BioBank+Sangre+Digital)

---

## 📖 Descripción

**BioBank · Sangre Digital** es una aplicación web educativa que combina **biotecnología** y **salud digital** para simular un sistema de banco de sangre. Permite:

- Registrar pacientes con nombre, cédula, fecha y tipo de sangre.
- Calcular automáticamente la **compatibilidad de transfusiones** (a quién puede donar y de quién puede recibir).
- Visualizar una **matriz de compatibilidad** completa con el sistema ABO y factor Rh.
- Almacenar los datos en la nube mediante **Supabase**.
- Gestionar el historial de pacientes (listar y eliminar registros).

Este proyecto fue desarrollado como trabajo práctico para la asignatura **Tecnologías Emergentes**, demostrando la integración de bases de datos en la nube, diseño responsivo y lógica de negocio aplicada a la salud.

---

## ✨ Características

- ✅ **Registro de pacientes** con validación de campos.
- 🩸 **Análisis de compatibilidad** basado en reglas inmunológicas reales (sistema ABO y Rh).
- 📊 **Matriz de compatibilidad** dinámica que resalta el tipo de sangre seleccionado.
- ☁️ **Persistencia en la nube** con Supabase (PostgreSQL).
- 📱 **Diseño responsivo** (adaptado a PC, tablet y móvil).
- 🎨 **Interfaz moderna** con efecto glassmorphism y colores neón.
- 🔔 **Notificaciones tipo toast** para confirmar acciones.
- 🗑️ **Eliminación de registros** con confirmación.

---

## 🛠️ Tecnologías utilizadas

| Tecnología | Propósito |
|------------|-----------|
| **HTML5 + CSS3** | Estructura y estilos visuales (glassmorphism, responsive). |
| **JavaScript (Vanilla)** | Lógica de compatibilidad, interacción con Supabase y manipulación del DOM. |
| **Supabase** | Base de datos en la nube (PostgreSQL) y API REST. |
| **Vercel** | Plataforma de despliegue continuo (hosting). |
| **Git / GitHub** | Control de versiones y repositorio remoto. |

---

## 🚀 Demo en vivo

Puedes probar la aplicación en el siguiente enlace:  
🔗 [https://biobank-sangre.vercel.app](https://biobank-sangre.vercel.app)  
*(Reemplaza con tu URL real)*

---

## 👥 Equipo

- **José Malala Morón**  
- **Shandee Campos Cespedes**  
- **Yeiko Daniel Añez Cortez**  

**Materia:** Tecnologías Emergentes  
**Año:** 2026

---

## 📋 Requisitos previos

- Navegador web moderno (Chrome, Firefox, Edge, Safari).
- (Opcional) Editor de código como VS Code.
- (Opcional) Node.js y npm para ejecutar Vercel CLI.

---

## 🔧 Instalación y configuración local

1. **Clona el repositorio**
   ```bash
   git clone https://github.com/tu-usuario/biobank-sangre.git
   cd biobank-sangre

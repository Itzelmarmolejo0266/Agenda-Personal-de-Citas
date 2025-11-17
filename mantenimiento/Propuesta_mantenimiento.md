# 📘 README — Agenda Personal de Citas

## 🏫 Universidad
**Facultad:** Ciencias e Ingeniería  
**Carrera:** Ingeniería de Software  
**Asignatura:** Introducción a la Ingeniería en Software  
**Docente:** Jorge Dumar Guevara Serrano  
**Periodo:** Agosto – Diciembre 2025  
**Lugar:** Milagro, Ecuador  

---

## 👥 Autores
- Emilio Javier Falcones Troya  
- Kasey Roy Andrade Hernández  
- Jhon Elkin Benavides Ruiz  
- Bryan Damián Cedeño Pincay  
- Itzel Valentina Marmolejo Santana  
- Allison Baiola Reyes Suárez  

---

# 📌 Agenda Personal de Citas

## 📖 Descripción del Sistema
La **Agenda Personal de Citas** es una aplicación diseñada para registrar, organizar y gestionar citas personales o profesionales.  
Permite al usuario:

- Crear nuevas citas  
- Editar y eliminar citas  
- Visualizar el calendario por día, semana o mes  
- Recibir recordatorios  

Su objetivo es mejorar la organización del tiempo, evitar olvidos y optimizar la productividad de los usuarios.

---

# 🛠️ Mantenimiento de Software

El mantenimiento de software consiste en **modificar y actualizar un sistema después de su entrega** para:

- Corregir errores  
- Mejorar su rendimiento  
- Adaptarlo a nuevos entornos  

(Basado en Pressman, 2010 y Sommerville, 2011)

---

## 🔧 Tipos de Mantenimiento

### 1. Correctivo  
Corrige errores o defectos detectados durante el uso del sistema.

### 2. Adaptativo  
Adapta el software a nuevos entornos tecnológicos (nuevas versiones de SO, navegadores, hardware).

### 3. Perfectivo  
Mejora funciones existentes o agrega nuevas, atendiendo necesidades del usuario.

### 4. Preventivo  
Refactoriza o mejora el código para prevenir fallas futuras y aumentar la mantenibilidad.

---

## 💰 Costos de Mantenimiento
Según Sommerville:

- Constituyen entre **60% y 80%** del costo total del ciclo de vida del software.  
- Los mantenimientos **correctivos y perfectivos** son los más comunes.  
- Aumentan si no existe buena documentación o si el sistema tiene baja calidad inicial.

---

# 🔄 Etapas del Mantenimiento  
(Basado en Sommerville y Pressman)

## 1. Identificación y Análisis del Cambio
- Se detecta la necesidad de un cambio.  
- Se evalúa su viabilidad técnica y económica.

**Objetivo:** comprender qué se debe modificar.

---

## 2. Evaluación del Impacto y Planificación
- Se analiza cómo el cambio afectará el sistema completo.  
- Se planifican tareas, recursos, tiempos y riesgos.

**Objetivo:** evitar impactos negativos.

---

## 3. Implementación y Pruebas
- Se realiza la modificación del código.  
- Se aplican pruebas unitarias e integradas.

**Objetivo:** garantizar que el cambio funcione correctamente.

---

## 4. Liberación y Documentación
- Se entrega la nueva versión del sistema.  
- Se actualiza documentación técnica y de usuario.

**Objetivo:** mantener trazabilidad del software.

---

## 5. Revisión Post-Implementación
- Se evalúa si el cambio resolvió el problema.  
- Se recoge retroalimentación para futuras mejoras.

**Objetivo:** mejorar la calidad del proceso de mantenimiento.

---

# 🧩 Análisis del Problema

Durante el uso del sistema se identificaron dos problemas principales:

1. Falta de sincronización con calendarios externos (Google, Outlook).  
2. Ausencia de notificaciones en tiempo real cuando la aplicación está cerrada.

Estos factores reducen la eficiencia, usabilidad y competitividad del sistema.

---

# 🚀 Tipos de Mantenimiento Aplicados al Caso

## Cambio Funcional Propuesto  
### **Módulo de Sincronización y Recordatorios Inteligentes**

### Descripción
Se propone integrar funcionalidades que permitan:

- Sincronización de citas con Google Calendar y Outlook  
- Notificaciones en tiempo real  
- Recordatorios automáticos vía correo o push  

### Objetivos
- Mejorar la usabilidad  
- Reducir duplicación de tareas  
- Aumentar confiabilidad del sistema  

---

# ⚙️ Implementación Técnica

1. Integrar **API de Google Calendar** y **Microsoft Graph**.  
2. Implementar un servicio en segundo plano para recordatorios.  
3. Añadir opciones de configuración de alertas.  
4. Actualizar la base de datos con IDs externos.  
5. Realizar pruebas unitarias e integradas.

---

# 🎯 Impacto en la Calidad y Mantenibilidad

- **Mantenibilidad:** mejora debido a diseño modular.  
- **Calidad:** aumenta la confiabilidad y portabilidad.  
- **Prevención:** reduce pérdida de citas y errores futuros.

---

# 📝 Reflexión Final

El mantenimiento es esencial no solo para corregir errores, sino para garantizar la **evolución y vigencia** del sistema.  
Para la Agenda Personal de Citas, los mantenimientos **perfectivo y adaptativo** permitirán que el sistema responda a las necesidades actuales del usuario.  
Aplicar prácticas de mantenimiento preventivo prolongará la vida útil del software y reducirá costos a largo plazo.

---

# 📊 Evidencia del Cambio
El diagrama del proyecto muestra cómo se aplicará una mejora funcional centrada en:

- Agregar opción para eliminar citas  
- Mejorar la interfaz de usuario  
- Representar el flujo de acciones mediante bloques conectados  

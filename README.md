# Expedita - Sistema de Gestión Inter-Áreas 🚀

> **Nota:** El código fuente de este proyecto se encuentra en un repositorio privado por razones de seguridad y propiedad intelectual. Este repositorio funciona como demostración (Showcase) de la arquitectura, funcionalidades y tecnologías implementadas.

## 🎬 Demo del Sistema
Hacé clic en la imagen para ver el recorrido completo de la aplicación:

[![Demo Expedita](https://img.youtube.com/vi/kWybaBKLf84/0.jpg)](https://youtu.be/kWybaBKLf84)

## 📌 Sobre el Proyecto
Expedita es un gestor de requerimientos diseñado para centralizar pedidos, dar trazabilidad en tiempo real y ordenar el flujo de trabajo entre distintos departamentos de una misma organización. Resuelve el problema clásico de la pérdida de información en hilos de correo o canales informales.

## 🛠️ Stack Tecnológico y Arquitectura

**Backend:**
* Desarrollado en **.NET (C#)** construyendo una API REST robusta.
* Implementación de seguridad y manejo de sesiones con **JWT (JSON Web Tokens)**.
* Control estricto de accesos y visibilidad del lado del servidor, basado en roles y áreas departamentales.

**Frontend:**
* Interfaz de usuario dinámica construida con **React**.
* Consumo de API para renderizar dashboards en tiempo real.
* Manejo de estados condicionales según el nivel de permisos del usuario logueado.

## ✨ Funcionalidades Principales
* **Creación de Tickets:** Asignación directa a áreas resolutoras específicas.
* **Trazabilidad:** Dashboard en tiempo real con el estado de cada requerimiento (Abierto, En Pausa, Cerrado).
* **Comunicación Centralizada:** Hilos de comentarios oficiales por ticket para despejar dudas entre áreas.
* **Gestión de Subtareas:** El área asignada puede desglosar un requerimiento en tareas internas y marcar su progreso.

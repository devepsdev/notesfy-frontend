# 📌 Notes App - Frontend

Este proyecto es el **frontend** de una aplicación CRUD de notas, desarrollado en **Angular** y consumiendo la API REST del backend.

## 🚀 Tecnologías utilizadas

- **Angular 20+**
- **TypeScript**
- **Angular Router**
- **Bootstrap** (para estilos y diseño responsive)
- **SCSS** (para personalización de estilos)

## 📂 Estructura del proyecto

```Esquema
src/app
 ├── components   → Componentes reutilizables
 ├── pages        → Páginas principales (Home, Notes)
 ├── services     → Servicios para consumir la API REST
 ├── models       → Interfaces/DTOs
 └── app-routing.module.ts
```

## 🖥️ Páginas principales

- **Home** → Presentación del proyecto con gif de demostración.
- **Notes** → Muestra todas las notas registradas.

## 🛠️ Requisitos

- **Node.js 22 (LTS)**
- **Angular CLI 20+**

## ▶️ Cómo ejecutar

1. Clonar el repositorio:

   ```bash
   git clone https://github.com/devepsdev/notesfy-frontend.git
   ```

2. Instalar dependencias:

   ```bash
   npm install
   ```

3. Levantar el servidor de desarrollo:

   ```bash
   ng serve -o
   ```

4. La app estará disponible en:

   ```URL
   http://localhost:4200
   ```

## 🔗 Conexión con el backend

Asegúrate de que el backend está corriendo en `http://localhost:8080`.  
El **servicio Angular** (`note.service.ts`) está configurado para consumir la API REST del backend.



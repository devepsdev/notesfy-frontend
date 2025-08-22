# 📌 Notes App - Frontend

Este proyecto es el **frontend** de una aplicación CRUD de notas, desarrollado en **Angular** y consumiendo la API REST del backend.

## 🚀 Tecnologías utilizadas

- **Angular 18+**
- **TypeScript**
- **Angular Router**
- **Bootstrap** (para estilos y diseño responsive)
- **SCSS** (para personalización de estilos)

## 📂 Estructura del proyecto

```Esquema
src/app
 ├── components   → Componentes reutilizables
 ├── pages        → Páginas principales (Home, Listado, Crear, Editar)
 ├── services     → Servicios para consumir la API REST
 ├── models       → Interfaces/DTOs
 └── app-routing.module.ts
```

## 🖥️ Páginas principales

- **Home** → Presentación del proyecto con gif de demostración.
- **Listado de notas** → Muestra todas las notas registradas.
- **Crear nota** → Formulario para añadir una nueva nota.
- **Editar nota** → Formulario para actualizar una nota existente.
- **Eliminar nota** → Confirmación y borrado de notas.

## 🛠️ Requisitos

- **Node.js 22 (LTS)**
- **Angular CLI 18+**

## ▶️ Cómo ejecutar

1. Clonar el repositorio:

   ```bash
   git clone
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

# 🏗️ KAWU Backoffice

Interfaz web para arquitectos donde pueden gestionar la información de obras cargada por WhatsApp por los contratistas. Esta app consume el backend de KAWU para mostrar la información de forma ordenada, editable y exportable.

---

## 🚀 Requisitos

- Node.js v18 o superior  
- npm  
- Backend de KAWU corriendo (`http://localhost:3000`)  
- Base de datos SQLite (se genera con Prisma)

---

## 📦 Instalación

```bash
git clone https://github.com/juanpablosolari/kawu-backoffice.git
cd kawu-backoffice
npm install
```
---

## 🧪 Levantar entorno de desarrollo
```bash
npm run dev
```
- Abrir navegador en: http://localhost:5173

---

## 📡 Conexión con el backend

La app asume que el backend de KAWU está corriendo en:
http://localhost:3000

Si querés cambiar esa URL, podés hacerlo creando un archivo .env en la raíz del proyecto con:

```json
VITE_API_URL=http://localhost:3000
```
---

## 🧹 Tareas pendientes iniciales
 Limpiar componentes de Vite por defecto

 Crear listado de mensajes en el backend

 Integrar API REST con Axios o Fetch

 Agregar diseño mínimo con Tailwind o similar

 ---

## 📁 Estructura inicial
 kawu-backoffice/
├─ public/
├─ src/
│  ├─ App.tsx
│  ├─ main.tsx
│  └─ components/
├─ .env
├─ package.json
└─ vite.config.ts

---
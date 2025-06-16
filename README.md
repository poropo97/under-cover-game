# Under Cover Game - Backend 🪨🪨🪨

**Primera piedra del proyecto.**  
**Estado:** _Work in Progress._

---

## 📖 Descripción

Este es el backend API para la aplicación _Under Cover Game_. Se encarga de la gestión de usuarios, sesiones de juego y almacenamiento de datos utilizando **MongoDB**.

---

## 🛠️ Tecnologías

- **Node.js** + **TypeScript**
- **Express.js**
- **MongoDB** (recomendado ejecutarlo con Docker)
- **dotenv** para variables de entorno
- **nodemon** para desarrollo

---

## ⚙️ Prerrequisitos

Asegúrate de tener instalados los siguientes programas:

- **Node.js**
- **Docker** (para MongoDB)
- Contenedor de **MongoDB** en ejecución (recomendado con Docker)

---

## 🚀 Comenzando

Sigue estos pasos para configurar y ejecutar el proyecto:

### 1. Clonar el repositorio

```bash
git clone <your-repo-url>
cd under-cover-game/backend
```
### 2. Instalar dependencias

```bash
npm install
```

### 3. Configurar variables de entorno

Crea un archivo `.env` en la raíz de la carpeta del backend con el siguiente contenido:

```env
MONGODB_URI=mongodb://localhost:27017/undercover
PORT=4000
```

Ajusta `MONGODB_URI` si tu MongoDB se ejecuta en otro lugar.

### 4. Iniciar MongoDB con Docker (opcional pero recomendado)

```bash
docker run -d -p 27017:27017 --name mongodb mongo
```

O, si utilizas `docker-compose`:

```bash
docker-compose up -d
```

### 5. Ejecutar el servidor backend

Para desarrollo con recarga en caliente:

```bash
npm run dev
```

O para compilar y ejecutar:

```bash
npm run build
npm start
```

### 6. Abre tu navegador o cliente API en:

```arduino
http://localhost:4000
```

---

## 📜 Scripts

- `npm run dev` — Inicia el servidor con recarga en caliente (nodemon + ts-node)
- `npm run build` — Compila TypeScript a JavaScript
- `npm start` — Ejecuta el código JavaScript compilado

---

## 📝 Notas

Este proyecto está en progreso. ¡Espera actualizaciones y nuevas características pronto!

Siéntete libre de contribuir o abrir issues.

🪨🪨🪨


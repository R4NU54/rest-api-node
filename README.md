# Desarrollo de API REST con Express.

---

Recuperar los datos de un archivo JSON y exponerlos a traves de una API REST.
Crear, modificar y eliminar datos a traves de una API REST.

### Dependencias

- [ExpressJs](https://expressjs.com/) - Framework web rápido, minimalista y sin opiniones para Node.js.
- [Cors](https://expressjs.com/en/resources/middleware/cors.html) - Es un paquete node.js para proporcionar un middleware Connect/Express que se puede utilizar para habilitar CORS con varias opciones.
- [Zod](https://zod.dev/) - Es una biblioteca de validación y declaración de esquemas basada en TypeScript.

Para instalar las dependencias del proyecto ejecutar el comando.

`pnpm install`

Para ejecutar el proyecto ejecutar el comando.

`pnpm start`

### Solucion de CORS con Middleware de Express.

`app.use(cors());`

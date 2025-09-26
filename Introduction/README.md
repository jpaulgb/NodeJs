Node.js: es orientado a eventos y utiliza E/S asíncrona y no bloqueante.

Pasos: Del lado del cliente la accion que se realiza en el html por el usuario pasa a la lógica de negocio de javascript.
En el paso 3, la aplicación javascript realiza una llamada a un servicio web a través de HTTP usando el formato .JSON.
El servicio web REST recibe la solicitud HTTP.
4. El servicio web REST procesa la solicitud y devuelve una respuesta .JSON a través de HTTP.

Express.js:
Framework para construir aplicaciones sobre node.js
Abstrae lower-level APIs en Node.js usando HTTP utilizando metodos utilitarios y middleware.

### 2. /public/: *archivos publicos como imagenes html, ccs, js*
### 3. /server/routes: *define los endpoints que aceptan y procesan las solicitudes del cliente*
### 4. /server/server.js: *contiene el código principal de la aplicación*
  ## *1. Express.js application:*

```bash
const app = express();
```

### 5. package.json: METADATA
   *información de metadatos del proyecto, como dep, scripts y más*
   
![](https://github.com/jpaulgb/NodeJs/blob/main/Introduction/node_y_express.png)

# HTTP-Request-Methods

Este repositorio está diseñado para **aprender y practicar el manejo de solicitudes HTTP** utilizando los métodos más comunes: **GET**, **POST**, **PUT** y **DELETE**, implementados en tres lenguajes de programación: **Python**, **JavaScript** y **PHP**.

## **Objetivo del Proyecto**
El objetivo principal es demostrar cómo realizar peticiones HTTP hacia APIs externas utilizando diferentes lenguajes de programación. Esto incluye la interacción con servicios web RESTful para realizar operaciones básicas como:
- **GET**: Obtener información.
- **POST**: Crear un nuevo recurso.
- **PUT**: Actualizar un recurso completo.
- **DELETE**: Eliminar un recurso.

Al final, este proyecto será una guía práctica para el manejo de APIs en proyectos futuros.

---

## **Estructura del Repositorio**

El proyecto está organizado en carpetas, cada una correspondiente a un lenguaje de programación:
```
HTTP-Request-Methods/
├── python/
│   ├── get_request.py        # Ejemplo de solicitud GET en Python
│   ├── post_request.py       # Ejemplo de solicitud POST en Python
│   ├── put_request.py        # Ejemplo de solicitud PUT en Python
│   ├── delete_request.py     # Ejemplo de solicitud DELETE en Python
├── javascript/
│   ├── get_request.js        # Ejemplo de solicitud GET en JavaScript
│   ├── post_request.js       # Ejemplo de solicitud POST en JavaScript
│   ├── put_request.js        # Ejemplo de solicitud PUT en JavaScript
│   ├── delete_request.js     # Ejemplo de solicitud DELETE en JavaScript
├── php/
│   ├── get_request.php       # Ejemplo de solicitud GET en PHP
│   ├── post_request.php      # Ejemplo de solicitud POST en PHP
│   ├── put_request.php       # Ejemplo de solicitud PUT en PHP
│   ├── delete_request.php    # Ejemplo de solicitud DELETE en PHP
├── README.md
```


---

## **Descripción de los Métodos HTTP**

### **1. GET**
- **¿Qué hace?**: Recupera información de un recurso existente.
- **Uso común**: Obtener datos como listas de usuarios, publicaciones, o detalles de un producto.
- **Ejemplo**: Consultar una lista de publicaciones en una API pública.

### **2. POST**
- **¿Qué hace?**: Crea un nuevo recurso en el servidor.
- **Uso común**: Registrar un nuevo usuario, agregar un producto, o enviar datos de un formulario.
- **Ejemplo**: Enviar datos como nombre, correo electrónico y contraseña para registrar un usuario.

### **3. PUT**
- **¿Qué hace?**: Actualiza un recurso existente por completo.
- **Uso común**: Editar información de un usuario o reemplazar datos en un registro.
- **Ejemplo**: Cambiar todos los detalles de un producto en un inventario.

### **4. DELETE**
- **¿Qué hace?**: Elimina un recurso existente.
- **Uso común**: Borrar un usuario, eliminar un producto o remover un registro.
- **Ejemplo**: Eliminar un comentario de un blog.

---

## **Lenguajes Usados**

### **1. Python**
- Se utiliza la librería `requests` para manejar las peticiones HTTP.
- Es un lenguaje simple y versátil para integrarse con APIs.

### **2. JavaScript**
- Se utiliza `fetch` (nativo de JavaScript) para realizar las peticiones.
- Ideal para proyectos web debido a su compatibilidad con navegadores.

### **3. PHP**
- Se utiliza `cURL` para manejar las solicitudes HTTP.
- Es ampliamente usado en servidores backend para integrar APIs.

---

## **Cómo Ejecutar el Código**
<img src="https://skillicons.dev/icons?i=python,javascript,php" alt="Languages" />

<details>
  <summary><b>Python</b></summary>
  <code>Instala la librería requests si aún no la tienes</code>
  <br>
  <pre><code>pip install requests</code></pre>
  <code>Ejecuta los scripts desde la terminal: </code>
  <br>
  <pre><code>python get_request.py</code></pre>
</details>

<details>
  <summary><b>JavaScript</b></summary>
  <code>Abre un archivo .js en tu navegador o usa Node.js.</code>
  <br>
  <pre><code>node get_request.js</code></pre>
</details>

<details>
  <summary><b>PHP</b></summary>
  <code>Ejecuta los scripts desde la terminal:</code>
  <br>
  <pre><code>php get_request.php</code></pre>
</details>

---

# API de Pruebas

Para este proyecto utilizaremos la API pública **JSONPlaceholder**, que permite probar todos los métodos HTTP sin necesidad de configuración adicional.

## Endpoints Usados:

- **GET**: https://jsonplaceholder.typicode.com/posts
- **POST**: https://jsonplaceholder.typicode.com/posts
- **PUT**: https://jsonplaceholder.typicode.com/posts/1
- **DELETE**: https://jsonplaceholder.typicode.com/posts/1


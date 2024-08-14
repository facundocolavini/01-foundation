# Estructura del proyecto

- `tsconfig` de modo estricto si instalamos el proyecto con typescript
  - alias
  - compiler options
- `package json`
  - ``scripts`` definmos nuestros scripts para los distintos tipos de ambientes
  - ``checks``  astro hace un chequeo al compilar nuestra aplicación
  - ``preview`` para poder ver nuestra app con el producto final construido
  - `astro` es un alias para no usar npm
- `astro-config` donde hacemos las configuraciones de astro
- `env.d.ts` definimos nuestras variables de entorno.
- `src` donde ira todo nuestro codigo fuente
  - ``content`` para trabajar con contenido markdown
  - ``actions`` iran nuestras actions
  - variables locales donde podemos tomar en nuestra app
- `pages` donde creamos nuestras paginas y automaticamente crean las rutas
- `public` la carpeta publica donde  vamos a poner todo el contenido estatico que no va a ser optimizado por astro todo lo que vaya a dentro quedara estatico
`.astro` se almacena preferencias del usuario normalmente para configuraciones como para desactivar el dev toolbar

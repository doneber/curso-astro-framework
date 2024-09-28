# Curso de Astro

## 01 - Empecemos

Como ya saben, podemos crear páginas web utilizando HTML, CSS y JS. También vimos el concepto de "Framework" o marco de trabajo.

Tambien vimos de forma rápida el uso de herramientas como [Bootstrap](https://getbootstrap.com/) para acelerar el desarrollo de los estilos.

Así que, antes de continuar veamos primero el problema que resuelve [Astro](https://astro.build/)


## 02 - Creando mi proyecto

Con mis conocimientos básicos en  HTML, CSS y JS estoy listo para empezar a crear el próximo facebook. Empezaré creando algo básico en el archivo `index.html` y como ando algo corto de tiempo, usaré Bootstrap.

## 03 - Definiendo la idea de mi proyecto

Lo he estado pensando bien y decidí hacer una especie de tienda de stickers (como los que usamos en whatsapp). Así que dentro del archivo `index.html` desarrollaré los componentes mas comunes.

## 04 - Mejorando la tienda

Ahora que el proyecto va tomando forma necesito agregar imágenes y tener una mejor estructura de carpetas para el proyecto. Además sería bueno que mejore los elementos del sitio web y cualquier otro detalle que se me ocurra.

## 05 - Agregando Astro al proyecto

Ahora si quisiera hacer una nueva página como `about.html` tengo demasiado código que actualizar. Para mejorar mi **experiencia de desarrollo** utilizaré Astro.

Lo normal sería crear otro proyecto y ejecutar:

```shell
npm create astro@latest
```

Pero por esta vez simplemente agregaré los siguientes archivos:
- `package.json`
- `astro.config.mjs`
- `src/env.d.ts`

Moveré mis archivo `.html` a la carpeta `src/pages`

Y después de que ejecute

```shell
npm install
```

Se creará automáticamente el archivo `package-lock.json`.

Ya que estamos controlando las vesriones también debemos copiar el archivo `.gitignore`

Finalmente ya podemos levantar el proyecto ejecutando

```shell
npm run dev
```

y dirigirnos a [http://localhost:4321/](http://localhost:4321/)

### 06 - Creando un componente en astro

Quizás aún no veas muchos cambios en el proyecto, pero ahora podemos usar difrentes funcionalidades de astro.

Así que para empezar nos creamos el componente de la Barra de Navegación, así que para esto necesitamos hacer los siguiente:
- Crear dentro de la carpeta `src` una nueva carpeta llamada `components`
- Luego crear un archivo llamado `Navegacion.html`
- Y ahora para poder usar este componente, el archivo donde queremos llamarlo debe ser `.astro`, así que remplazamos la extensión de nuestro `index.html` a `index.astro`
- Y finalmente desde `index.astro` ya podemos llamar al componente que acabamos de crear (`Navegacion.html`)

Ahora podremos usar este componente en cualquier otra página que necesitemos.

Nota: Instala la extensión de Astro para que el editor coloree el archivo. 
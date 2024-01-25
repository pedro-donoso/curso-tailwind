![cards](https://github.com/pedro-donoso/curso-tailwind/assets/68760595/fc930ad0-a816-44d2-9dd0-84dde7b696a4)

## https://tailwind-noticias.netlify.app/

### curso-tailwind

#### 1. Iniciar npm:
`npm init -y`

#### 2. Instalar tailwindcss en las dependencias de desarrollo:
`npm install -D tailwindcss`

#### 3. Ignorar carpeta node_modules:
Crear archivo .gitignore -> agregar node_modules

`/node_modules` (la carpeta se sombreará)

#### 4. Creo archivo de configuración de tailwind:
`npx tailwind init`

utilizo expresion regular ['./*.html'] (indico que todos los archivos utilizaran tailwind y el index.html)

#### 5. Compilar archivo de salida css cada vez que se realice algun cambio:
`npx tailwindcss -i tailwind.css -o styles.css`

indico archivo base que utilizara para compilar y nombre del archivo de salida

#### 6. Agrego compilador vite al proyecto:
`npm i -D vite postcss autoprefixer`

#### 7. Configuro postcss:
`npx tailwindcss init -p`

#### 8. Agrego scripts a package.json:
    "dev": "vite dev",
    "build": "vite build",
    "preview": "vite preview"

#### 9. Reemplazo archivo tailwind.css en index.html y vite lo compilara:

  `<link rel="stylesheet" href="tailwind.css">`

#### 10. Ejecuto seervidor vite para correr appicación:

`npm run dev`

#### 11. Creo archivo de producción:
`npm run build`

se crea la carpeta dist con assets y archivos index.html y css para producción

#### 12. Visualizar archivo:
`npm run preview`


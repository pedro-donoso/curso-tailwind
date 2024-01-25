![cards](https://github.com/pedro-donoso/curso-tailwind/assets/68760595/fc930ad0-a816-44d2-9dd0-84dde7b696a4)

## https://tailwind-noticias.netlify.app/

### curso-tailwind

#### 1. Iniciar npm:
`npm init -y`

#### 2. Instalar tailwindcss en las dependencias de desarrollo:
`npm install -D tailwindcss`

#### 3. Creo archivo de configuración de tailwind:
`npx tailwind init`

utilizo expresion regular ['./*.html'] (indico que todos los archivos utilizaran tailwind y el index.html)

#### 4. Compilar archivo de salida css cada vez que se realice algun cambio:
`npx tailwindcss -i tailwind.css -o styles.css`

indico archivo base que utilizara para compilar y nombre del archivo de salida

#### 5. Agrego compilador vite al proyecto:
`npm i -D vite postcss autoprefixer`

#### 6. Configuro postcss:
`npx tailwindcss init -p`

#### 7. Agrego scripts a package.json:
    "dev": "vite dev",
    "build": "vite build",
    "preview": "vite preview"

#### 8. Reemplazo archivo tailwind.css en index.html y vite lo compilara:

  `<link rel="stylesheet" href="tailwind.css">`

#### 9. Ejecuto seervidor vite para correr appicación:

`npm run dev`

#### 10. Creo archivo de producción:
`npm run build`

se crea la carpeta dist con assets y archivos index.html y css para producción

#### 11. Visualizar archivo:
`npm run preview`


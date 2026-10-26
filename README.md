# CryptoInfo v0.2.1

Es una Plataforma Web Desarrollada con el propósito de proporcionar información actualizada sobre el Precio de Criptomonedas más relevantes del mercado, presentando sus valores expresados en moneda argentina. 

El Sistema busca facilitar el acceso a datos financieros relacionados con activos digitales, permitiendo a los usuarios consultar Información de manera rápida, organizada y confiable. La aplicación se estructura sobre una base de datos que almacena información detallada de cada criptomoneda, incluyendo su nombre, precio actual, variación porcentual registrada durante las últimas 24 hs y capitalización bursátil. Estos datos son consultados por los usuarios a través de una interfaz web intuitiva diseñada para optimizar la experiencia de navegación. Asimismo, el sistema incorpora un módulo de gestión de usuarios que permite el registro e inicio de sesión mediante un formulario seguro. Durante el proceso de registro se recopilan datos personales básicos, tales como Nombre, Apellido, Correo Electrónico y Contraseña, garantizando la identificación de cada Usuario dentro de la Plataforma.


# CryptoInfo

Plataforma Web para visualizar información y métricas de Criptomonedas.

## Requisitos

Antes de ejecutar el proyecto, asegúrate de tener instalado:

- Node.js v18 o superior.
- npm v7.8.5 (incluido con Node.js).
- Expressjs v5.3.0

## Instalación

1. Clonar el repositorio:

```bash
git clone https://github.com/tu-usuario/tu-repositorio.git
```

2. Acceder al directorio del proyecto:

```bash
cd tu-repositorio
```

3. Instalar las dependencias:

```bash
npm install
```

## Configuración

Crear un archivo `.env` en la raíz del proyecto si es necesario.

Ejemplo:

```env
PORT=3000
JWT_SECRET=tu_clave_secreta
```

## Ejecución

Iniciar el proyecto:

```bash
npm start
```

o, si utilizas Nodemon:

```bash
npm run dev
```

## Dependencias principales

- Express v5.3.0
- JSON Web Token (JWT) RFC 7519 v1.1.0
- Dotenv v18.0.9
- Nodemon v1.4.7

### Autor

Matías Daniel Silvestri

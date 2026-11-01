# Manual tècnic - GreenLife


## Arquitectura
Aplicació client-servidor amb API REST.


## Tecnologies
- Backend: Node.js
- Frontend: React
- Base de dades: PostgreSQL


## Estructura del codi
- `/backend` - API i lògica de negoci
- `/frontend` - Interfície d'usuari
- `/database` - Migracions i models

## Autenticació JWT

GreenLife utilitza JSON Web Tokens (JWT) per autenticar els usuaris.

Quan un usuari inicia sessió correctament, el servidor genera un token JWT.

Aquest token permet verificar la identitat de l'usuari en les peticions a l'API.
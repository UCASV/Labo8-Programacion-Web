# Labo8-Programacion-Web
Integración con datos

## Diferencia entre Autenticación y Autorización
### Autenticación (Authentication)
Es la verificación de la identidad de un usuario (generalmente con usuario y contraseña).
### Autorización (Authorization)
Es la verificación de los permisos o derechos que tiene un usuario (ya autenticado) para acceder a un recurso o realizar una acción específica.


## Función del Token JWT en la Guía
El Token JWT (JSON Web Token) se usa como un pase digital seguro.

Se emite tras la autenticación y se envía en cada solicitud.

Su función es transportar de forma segura la identidad y los permisos del usuario (los claims), permitiendo al servidor verificar la autorización en cada petición sin consultar repetidamente la base de datos. Facilita la autorización sin estado (stateless).
# Frontend: aprendizaje de Angular

Repositorio de aprendizaje para avanzar desde las bases de HTML y CSS hasta el desarrollo de aplicaciones con Angular.

## Objetivos

- Practicar la estructura semántica y la accesibilidad con HTML.
- Aprender a crear interfaces y layouts con CSS.
- Comprender los fundamentos de Angular mediante ejemplos progresivos.
- Mantener cada etapa del aprendizaje separada y fácil de consultar.

## Estructura del proyecto

```text
Frontend/
├── 00-HTML/    # Primeros ejercicios de HTML y CSS
└── 01-BASES/   # Proyecto Angular con los fundamentos del framework
```

Las carpetas se numeran para reflejar el orden recomendado de aprendizaje. A medida que avance el proyecto se añadirán nuevas carpetas para los siguientes temas.

## Ruta de aprendizaje

### `00-HTML`

Contiene las primeras prácticas de HTML y CSS, incluyendo páginas, vistas y recursos gráficos. Es el punto de partida para familiarizarse con la estructura de una web y su presentación visual.

### `01-BASES`

Es la primera aplicación Angular del repositorio. Aquí se trabajan las bases del framework y la estructura generada por Angular CLI.

Para trabajar en esta aplicación:

```bash
cd 01-BASES
npm install
ng serve
```

Después, abre [http://localhost:4200/](http://localhost:4200/) en el navegador.

Comandos útiles:

```bash
ng build   # Genera una compilación de producción
ng test    # Ejecuta los tests unitarios
ng generate component nombre-componente
```

Consulta el [README de 01-BASES](01-BASES/README.md) para obtener las instrucciones específicas de esa aplicación.

## Cómo usar este repositorio

1. Empieza por `00-HTML` para repasar HTML y CSS.
2. Continúa con `01-BASES` y ejecuta la aplicación Angular.
3. Revisa los ejemplos y experimenta con cambios pequeños.
4. Añade cada nuevo bloque de aprendizaje en una carpeta numerada.

## Progreso

- [x] Bases de HTML y CSS
- [x] Creación del primer proyecto Angular
- [ ] Componentes y templates
- [ ] Data binding
- [ ] Directivas y pipes
- [ ] Servicios e inyección de dependencias
- [ ] Routing
- [ ] Formularios
- [ ] Consumo de APIs
- [ ] Testing y despliegue

## Requisitos

- Node.js y npm.
- Angular CLI para ejecutar y generar elementos del proyecto Angular.

La versión de Angular CLI utilizada inicialmente en `01-BASES` es la `13.3.11`.

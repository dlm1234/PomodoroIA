# Pomodoro IA

## Descripción
Pomodoro IA es una aplicación web que implementa la técnica Pomodoro para gestión del tiempo, añadiendo un componente de inteligencia artificial que recomienda actividades personalizadas durante los descansos. La aplicación aprende de las preferencias del usuario y adapta sus recomendaciones con el tiempo.

## Características

- Temporizador Pomodoro configurable (duración de trabajo, descansos cortos y largos)
- Sistema de recomendaciones inteligentes para los descansos
- Interfaz de usuario intuitiva y responsive
- Aprendizaje de preferencias del usuario mediante interacciones
- Adaptación de sugerencias según la hora del día
- Conteo de ciclos completados

## Tecnologías utilizadas

- HTML5
- CSS3 (con variables CSS para fácil personalización)
- JavaScript (vanilla, sin dependencias externas)
- LocalStorage para persistencia de datos (en desarrollo)

## Sistema de IA

La aplicación implementa un sistema simple de IA que:

1. Mantiene un perfil de preferencias del usuario entre diferentes categorías de actividades
2. Adapta las recomendaciones según la hora del día
3. Aprende de las interacciones del usuario (cuando selecciona una actividad)
4. Evita repeticiones en las sugerencias
5. Adapta las sugerencias según la duración del descanso

## Cómo usar

1. Abre el archivo `index.html` en cualquier navegador moderno
2. Configura los tiempos deseados para periodos de trabajo y descansos
3. Haz clic en "Iniciar" para comenzar el temporizador
4. Durante los descansos, selecciona las actividades recomendadas que te interesen
5. El sistema irá adaptándose a tus preferencias con el tiempo

## Estructura del proyecto

```
pomodoro-ia/
│
├── index.html      # Archivo principal HTML con CSS y JavaScript integrados
├── README.md       # Este archivo de documentación
└── LICENSE         # Licencia del proyecto
```

## Futuras mejoras

- Persistencia de datos mediante LocalStorage
- Estadísticas de productividad y uso
- Exportación e importación de configuraciones
- Sistema de notificaciones en el navegador
- Integración con servicios externos como Spotify (para música durante los descansos)
- Mejoras en el algoritmo de recomendación

## Licencia
Este proyecto está licenciado bajo la Licencia MIT.

# Gym App

App personal y semanal para registrar entrenamientos de gimnasio y ver el progreso.

## Funciones

- Rutinas con lista de ejercicios reutilizable.
- Registro de series, repeticiones, peso y RPE por sesión.
- Progreso por ejercicio: peso máximo, 1RM estimado (fórmula de Epley) y volumen por sesión.
- Resumen semanal: sesiones y volumen frente a la semana anterior.
- Peso corporal con promedio móvil de 7 registros.
- Exportar e importar copia en JSON.

## Uso

Abrí `index.html` en el navegador o publicá el repositorio con GitHub Pages.
Los datos se guardan en el `localStorage` del navegador: no salen del dispositivo ni se sincronizan entre equipos.

## Privacidad

Esta app maneja peso corporal, que es un dato de salud. Mantené el repositorio privado y no lo compartas en espacios públicos.

## Próximos pasos

- Sincronización con Supabase y login propio, para usar varios dispositivos.
- Temporizador de descanso entre series.
- Modo instalable en el celular (PWA).

# basesDatosNosqlAct1
# Documento de Requerimientos para la Base de Datos del Torneo Deportivo

## Introducción
Este documento establece los requerimientos para el diseño y desarrollo de una base de datos MongoDB que permita la gestión eficiente de los participantes en un torneo deportivo. El tipo de evento deportivo seleccionado para este proyecto es la Copa Mundial de Fútbol de la FIFA, que es un evento real y ampliamente conocido, con resultados y detalles disponibles.

## Objetivos
El objetivo principal de la base de datos es proporcionar una plataforma para administrar los participantes, equipos, entrenadores, árbitros, encuentros deportivos, resultados y tabla de posiciones de la Copa Mundial de Fútbol de la FIFA.

## Requerimientos de la Base de Datos

### Colección "deportistas"
- Almacenar información sobre los jugadores que participan en el torneo.
- Campos requeridos: nombre del jugador, posición, edad, equipo al que pertenece.

### Colección "equipos"
- Mantener datos sobre los equipos participantes en el torneo.
- Campos requeridos: nombre del equipo, entrenador, grupo al que pertenece.

### Colección "entrenadores"
- Registrar información sobre los entrenadores de los equipos participantes.
- Campos requeridos: nombre del entrenador, equipo al que pertenece.

### Colección "árbitros"
- Almacenar datos sobre los árbitros encargados de dirigir los partidos.
- Campos requeridos: nombre del árbitro, país de origen.

### Colección "encuentros deportivos"
- Registrar los detalles de los partidos jugados en el torneo.
- Campos requeridos: equipo local, equipo visitante, fecha del partido, estadio, árbitro principal.

### Colección "resultados"
- Mantener los resultados de los encuentros deportivos.
- Campos requeridos: ID del encuentro, equipo local, equipo visitante, resultado del equipo local, resultado del equipo visitante, ganador del encuentro.

### Colección "tabla de posiciones"
- Generar y actualizar la tabla de posiciones del torneo.
- Campos requeridos: nombre del equipo, puntos acumulados, partidos jugados, partidos ganados, partidos empatados, partidos perdidos, goles a favor, goles en contra, diferencia de goles.

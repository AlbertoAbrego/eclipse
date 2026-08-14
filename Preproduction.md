# Roadmap

## Direccion creativa

### Concepto

Eres encomendado con la tarea de adentrarte en una región corrupta del reino de X y recuperar un objeto de la Santa Iglesia, descubrirás los secretos del mundo y decidirás cuánto riesgo estás discpuestoa a asumir antes de regresar, extraer objetos y obtener tu recompensa.

**Partida**: diseño objetivo 18 minutos.

**Complejidad**:
🟢Baja-Media
Complejidad del jugador: baja
Complejidad del sistema: media

**Riesgo**: Bajo
Riesgo de producción: bajo
Riesgo de diseño: medio

**Ventaja**: extremadamente producible para un solo desarrollador y se pueden reutilizar para futuros proyectos.

### Genero

**Principal**: Roguelite de accion

_Secundarios:_

- Supervivencia
- Exploracion
- Estrategia ligera

### Tematica

**Fantasía oscura de corrupción y reliquias**

Un antiguo territorio fue consumido por un fenómeno conocido como el Renacer.

La Santa Iglesia difunde que la corrupción en:

animales,
personas,
estructuras,
y la propia naturaleza.

Es creada por gente pagana y pecadora que con sus actos provoca que el mal se manifieste.

Las reliquias permitirán que el orden y paz vuelvan a sus vidas.

El jugador es una persona que necesita el dinero para subsistir, alguien que entra en búsqueda de una recompensa a la región para recuperar un objeto robado a la Santa Iglesia.

### Estilo visual

Pixel art 2D top-down

- Resolución base: 320x180
- Pixel art 32x32
- Cámara top-down ligeramente inclinada
- Iluminación simple
- Paleta limitada

### Tipo de experiencia

- Tensión creciente
- Descubrimiento constante
- Construcción de builds
- Decisiones de riesgo/recompensa
- Sensación de “una partida más”

### Referencias

**Referencias de gameplay**

- Vampire Survivors
- Halls of Torment
- Death Must Die

**Referencias de atmósfera**

- Fear and Hunger
- Dark Souls
- Blasphemous

### Publico objetivo

#### Primario

Jugadores de:

- Vampire Survivors
- Halls of Torment
- Death Must Die
- Brotato

#### Secundario

Jugadores que disfrutan:

- fantasía oscura
- exploración
- builds
- progresión
- rejugabilidad

Edad aproximada:

18–35.

## Concepto seleccionado

### Elevator pitch

Un juego roguelite de supervivencia y exploración, ambientado en una fantasía oscura, donde el jugador se adenrtra en una región del pais consumida por criaturas desconocidas, después de un suceso llamado El Renacer, se te encomienda recuperr objetos para la Santa Iglesia quien busca restaurar el orden, derrota enemigos, obtiene objetos y mejoras, desbloquea nuevas clases, armas, modificadores, objetos permanentes entre partidas.

### Core fantasy

Soy fan del horror/terror psicológico y del horror cósmico, aún me falta por conocer, pero me parece sumamente interesante, así que la idea es construir algo al rededor de eso.

**Mi propuesta**: Un mundo completamente nuevo de fantasía, la historia se desarrollaría en un planeta Tierra, sí, pero no nuestra historia universal, estamos en una realidad donde la magia es real, otras criaturas fantásticas son reales y todavía el mundo está en una etapa de edad medieval, no existe la tecnología avanzada, existen campos de cultivos, granjas, lagos, reinos, hechizeros, brujos, caballeros, monjes, healers y muchos más. Existen entidades, dioses, espiritus, angeles, demonios, vampiros, no muertos, huecos, pesadillas, entre otros. El mundo estaría en una etapa donde el protagonista podrá investigar y encontrar pistas como simbología, nombres, ciudades, objetos y poco a poco embullirse en la historia oscura del mundo que vive, de hombres y mujeres con renombre y sus origenes oscuros, magia, rituales, mundo demoniaco, mundo de ángeles y mucho más.

- Tomar una lista corta de criaturas para incluir en la fantsía

Para esta idea propondría hacer la lista completa, pero limitar los tipos de personajes para el MVP y si esto tiene mejor cuerpo, avanzamos.

Core Fantasy refinada

“Soy un explorador enviado por una institución sagrada que podría estar ocultando la verdadera naturaleza del horror que consume el mundo.”

### Game pillars

1. Expediciones significativas
   Cada incursión debe generar una historia.

No una repetición.

1. Horror religioso y descubrimiento

El mundo debe ser inquietante.

El jugador debe querer encontrar la siguiente nota, reliquia o santuario.

3. Builds expresivas

Las decisiones de objetos y mejoras cambian radicalmente la forma de jugar.

4. Riesgo con consecuencias

Quedarse más tiempo aumenta la recompensa y el peligro.

5. Mundo coherente

Cada enemigo, objeto, lugar y reliquia debe sentirse parte del mismo universo.

### Core gameplay loop

Propondría algo como:

1. Entrada a zona inicial
2. Exploración
3. Batallas (enemigos)
4. Encontrar objetos
5. Oportunidad que el jugador vuelva a casa (guardar objetos o entregar misiones) o continuar explorando
6. Regresa a base - se me ocurre que cada lugar tenga iglesias o santuarios donde guardar
7. Entrega quests - repetir
8. Jugador muere (pierde inventario)
9. Vuelve a iniciar, pero con objetos guardados

Algo que estaba pensando, esto sale un poco del juego inicial que era propuesto, pero lo siento más mío si el jugador puede moverse con libertad, atacar a voluntad, explorar, encontrar objetos, avanzar y me apego más al tipo de juego roguelike donde mueres y empiezas desde el inicio o en su defecto tener puntos de guardado estilo dark souls, pero eso cambiaría el tipo de juego y quizás la dificultad del juego, creo que dejarlo como roguelite/roguelike es mejor, esa opción de darle al jugador volver está genial, pero no logro vislumbrar qué vendría después de volver a casa.

### Estructura de una partida

#### Inicio

- eliges arma
- equipamiento
- consumibles

#### Zona 1

- enemigos básicos
- primeros objetos
- primer santuario

#### Zona 2

- enemigos especializados
- eventos
- reliquias

#### Zona 3

- élites
- corrupción intensa
- jefe

#### Final

derrotar jefe
encontrar santuario
decidir regresar o continuar (en el futuro)

Para el MVP, incluso podemos hacer que el jefe sea el final.

### Progresion

1. Equipo
   - Armas.
   - Reliquias.
   - Consumibles.

2. Conocimiento
   - Nuevos eventos.
   - Nuevas regiones.
   - Nuevos NPCs.
   - Nuevas investigaciones.

### Alcance inicial

Yo propondría tener al menos:

1. 1 mapa (1 region con 3 zonas conectadas)
2. 1 personaje jugable
3. 3 armas
4. 15 mejoras/objetos
5. 8 enemigos normales
6. 2 élites
7. 1 jefe
8. Iglesias (puntos de control)
9. Logros básicos o iniciales
10. Configuracion
11. Guardado
12. Soporte para gamepad/joystick

## Diseno

Arte 2D ya sea pixel art o estilo personal 2D en formato top-down

### Personaje

### Enemigos

### Armas

### Mejoras

### Jefe

### Mundo

### Narrativa

### UI

## Arquitectura

### Sistemas principales

### Estructura de escenas

### Resources

### Autoloads

### Comunicacion entre sistemas

### Guardado

### Datos

### Limites de responsabilidad

## Produccion

### Milestones

### Stories

### Backlog

### Definition of Done

### Git workflow

### Documentation

### Estrategia de playtesting

## Cierre de preproduccion

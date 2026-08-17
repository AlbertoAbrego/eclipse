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

Estuve mirando los incrementales y creo que podría ser un incremental, roguelite de accion, con algo de roguelike, exploracion.

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
   - Cada incursión debe generar una historia.
   - No una repetición.

2. Horror religioso y descubrimiento
   - El mundo debe ser inquietante.
   - El jugador debe querer encontrar la siguiente nota, reliquia o santuario.

3. Builds expresivas
   - Las decisiones de objetos y mejoras cambian radicalmente la forma de jugar.

4. Riesgo con consecuencias
   - Quedarse más tiempo aumenta la recompensa y el peligro.

5. Mundo coherente
   - Cada enemigo, objeto, lugar y reliquia debe sentirse parte del mismo universo.

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

> Creo que ya es hora de escribir el Lore de este juego, hagamoslo en **/lore.md**

### Personaje

Personaje jugable 1:

- Nombre: Adam
- Edad: 35 años
- Profesion: Herrero

Personaje jugable 2:

- Nombre: Alice
- Edad: 30 años
- Profesion: Clériga

### Enemigos

GPT propone:

- Corrompido: humano, lento melee.
- Devorador: criatura deformada, rapido, salta.
- Vigia: entidad religiosa, a distancia.
- Penitente: enemigo resistente, escudo.
- Heraldo del renacer: elite, invoca corrupcion.
- Malakor: boss.
  Propone que los enemigos cuenten historia y estoy algo de acuerdo.
  En lugar de usar números, usar categorías. Bajo, Medio, Alto

1. Demonio menor:
   - Vida: 50
   - Daño: 8
   - Velocidad: 30?

2. Demonio superior:
   - Vida: 100
   - Daño: 18
   - Velocidad: 45?

3. Demonio Arcano:
   - Vida: 230
   - Daño: 45
   - Velocidad: 60?

4. Malakor (boss):
   - Vida: 500
   - Daño: 100
   - Velocidad: 80?

5. Espiritu menor:
   - Vida: 30
   - Daño: 3
   - Velocidad: 45?

6. Espiritu superior:
   - Vida: 45
   - Daño: 10
   - Velocidad: 60?

7. Espiritu arcano:
   - Vida: 60
   - Daño: 15
   - Velocidad: 80?

8. Vesper (boss):
   - Vida: 400
   - Daño 85
   - Velocidad: 110?

### Armas

| Nombre   | Damage | Velocidad Ataque | Tipo      |
| :------- | :----- | :--------------- | :-------- |
| Martillo | alto   | lento            | mele      |
| Espada   | medio  | rapido           | mele      |
| Ballesta | alto   | lento            | distancia |

1. Martillo
   Lento, mucho daño.
   - Daño: 6
2. Espada
   Rapido, daño medio.
3. Ballesta
   A distancia, daño alto, recarga lenta.

### Mejoras

1. Vida: +100
2. Daño: +5%
3. Velocidad de movimiento: +15

Debería ponerles nombres y más variantes?
Pensaba en objetos en específico, como collares, medallones, anillos, etc.

Propuestas de GPT:

- Anillo del Herrero: Los golpes pesados tienen probabilidad de aturdir.
- Medallón del Mártir: Pierdes vida máxima. Aumenta mucho el daño.
- Rosario Agrietado: Los enemigos cercanos reciben daño periódico.
- Fragmento del Renacer: Las muertes aumentan temporalmente tu poder. Pero también la corrupción.
- Linterna Consagrada: Revela secretos y reduce efectos de oscuridad.

Los cuales creo que puedo tomar cosas

Se requieren categorias:

- Reliquias
- Consumibles
- Materiales
- Objetos de mision

### Jefe

Puede ser entre Vesper y Malakor
Se me ocurre investigar nombres de los Papa de la historia, alguno de esos nombres podría ser bueno para algún boss

### Mundo

Imagino que es el diseño del mapa?

- Ciudad Gilead
- Bosque
- Cementerio
- Rio
- Campos de cultivo

### Narrativa

Una breve descripción al elegir el personaje, por ahora sólo de Adam.

Adam: Es un adulto de la ciudad Gilead, aprendió el oficio de Herrero por su padre, desde pequeño aprendió a ganarse la vida, por su trabajo tiene un físico destacado y es resistente, después del evento del Renacer, la ciudad ha tenido problemas para tener un comercio próspero, Adam ha sido afectado y ha tenido que buscar otras fuentes de ingreso, por lo que al ir a rezar a la iglesia, un obispo le ofreció una recompensa en oro si le ayudaba a recuperar un collar que fue robado, dicho objeto parece ser muy importante y sagrado, por lo que la recompensa es bastante tentadora, Adam acepta y se adentra a investigar qué pasó con el collar perdido, lo han mandado a investigar con uno de los campesinos que han sido testigos del hurto antes de llegar a casa de Cedric se encuentra emboscado por criaturas extrañas (Demonios menores) y debe pelear para salir con vida, una vez Adam le pregunta al campesino Cedric por información, después al salir del hogar de Cedric, se topa con criaturas extrañas nuevamente (Demonios menores y superiores). Podríamos empezar el juego directamente saliendo de la iglesia y marcar un rumbo a la casa del campesino Cedric.

### UI

- Barra de vida
- Barra de experiencia
- Nivel
- Foto de perfil del jugador?
- Objetos equipados o logos de buffos

No encuentro más cosas para mostrar de momento

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

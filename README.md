# The-Resident-Forest-3-The-Forest-x-Resident-Evil-3-Remake-RE3R
A mashup of The Forest and Resident Evil 3 Remake

<img width="1152" height="799" alt="Captura de pantalla 2026-10-12 001724 - copia - copia" src="https://github.com/user-attachments/assets/2e49024d-fba3-457e-8258-c45985eb6cd3" />

<img width="966" height="647" alt="Captura de pantalla 2026-10-12 001757" src="https://github.com/user-attachments/assets/a905b33a-7e98-4844-b7e9-b8a29aea541f" />

<img width="1631" height="786" alt="Captura de pantalla 2026-10-12 001838" src="https://github.com/user-attachments/assets/18b6f65d-de18-406f-a382-cfdd1e013155" />

<img width="1526" height="889" alt="Captura de pantalla 2026-10-12 001918" src="https://github.com/user-attachments/assets/d207c24d-c4e2-4364-9c87-99f914062e54" />

<img width="1349" height="865" alt="Captura de pantalla 2026-10-12 002011" src="https://github.com/user-attachments/assets/eb2d0421-7d00-491f-aeef-b4f2e79fabcd" />

<img width="1592" height="843" alt="Captura de pantalla 2026-10-12 002115" src="https://github.com/user-attachments/assets/3541be52-14cf-4821-9995-6be1982188a4" />

<img width="1601" height="835" alt="Captura de pantalla 2026-10-12 002041" src="https://github.com/user-attachments/assets/9d2f1ee8-dbaa-4ee1-a40b-18b0cb9432e7" />

<img width="479" height="695" alt="Captura de pantalla 2026-10-12 002133" src="https://github.com/user-attachments/assets/3509168b-74d0-46a6-a0f2-968a5f6a60d2" />

<img width="495" height="642" alt="Captura de pantalla 2026-10-12 002146" src="https://github.com/user-attachments/assets/c7dea37d-6ee1-43e1-8c56-cdb98a7d7b62" />







# The Resident Forest 3 — 0.8.9.1

**Resident Evil 3 Remake inside The Forest.** A mashup that brings Jill Valentine and Carlos Oliveira, their voices, animations, weapons and inventory into The Forest's survival world, with single-player and cooperative multiplayer support.

**Current mod language: Spanish only.** This description is available in English, but the mod's interface and text have not been translated yet.

## Characters and animations

- Playable first-person Jill and Carlos, with their RE3R models and voices.
- The plane sequence and wake-up always use Jill. Gameplay starts with a 50/50 chance of playing as Jill or Carlos.
- Body, arm, hand and finger adaptation for The Forest's actions, alongside RE3R weapon and dodge animations.
- RE3R firing and reload sounds, inventory interface, icons and an ammunition display matching its visual style.
- Weapons yield the character's hands to native actions such as skinning animals or carrying logs.

## Reactive dodge

Press **F just before taking a hit** to perform a roll away from the attack. The camera follows the character's eyes through the animation, with approximately one second of damage immunity and an effort grunt. Dodging is reactive: it cannot be activated freely outside an incoming damage situation.

## Inventory and item boxes

- A separate **20-slot inventory** exclusively for RE3R items, opened with **TAB**.
- Compact, translucent interface. Drag items to move them, swap positions or merge compatible stacks. Some weapons occupy two slots.
- **5, 6, 7 and 8** equip items from the first four slots.
- Five RE3R item boxes: the katana cave, the bottom of the central sinkhole, the shore facing the yacht, the ending computer room and the far northwestern coast.
- Each box has **4 independent slots**. In co-op, contents are personal: taking a weapon does not consume your teammate's copy.
- Per-save persistence and RE3R inventory recovery through the native backpack after death.

## Available weapons

### G19

A hitscan pistol dealing **18 damage**, with a **×5 headshot multiplier** against cannibals and a light stagger. **15-round magazine**, unlimited reserve ammunition and mandatory reloading. Found in the item box facing the yacht. Large mutants do not receive this headshot multiplier.

### M3 shotgun

**4-shell capacity**, unlimited reserve ammunition and mandatory reloading. Fires **10 pellets**: one straight central pellet dealing 23 damage, plus nine dealing 8 each, for **95 base damage**. Spread and the dynamic reticle respond to aiming, standing still, walking and running.

Landing all ten pellets on the same enemy applies a **×1.5 damage multiplier**; cannibals also suffer a strong knockdown and knockback. Landing all ten on a cannibal's head kills it and triggers head dismemberment. Found in the katana item box.

### Infinite rocket launcher

A physical projectile with its RE3R model, infinite ammunition and an explosion on solid-surface impact. Bushes and similar vegetation do not detonate the rocket. Explosions use The Forest's dynamite system with **330 damage**; dynamite has also been adjusted to that value. Explosions can destroy trees; the G19 and M3 cannot fell them.

- **Normal and Hard:** ending computer room item boxes.
- **Hard Survival:** katana item box, alongside the M3.

The G19 and M3 also affect animals, suitcases and supported destructible objects. Weapons include RE3R aiming, firing and sounds; the G19 and M3 include their reloads.

## Enemy balance

| Enemy | Normal | Hard | Hard Survival |
| --- | ---: | ---: | ---: |
| Skinny / starving cannibal | 60 | 90 | 120 |
| Leader / torch cannibal | 120 | 180 | 240 |
| Pale cave cannibal | 160 | 240 | 320 |
| Strong blue pale cannibal | 220 | 330 | 440 |
| Armsy | 850 | 1300 | 1800 |
| Virginia | 750 | 1150 | 1600 |
| Cowman | 1000 | 1500 | 2000 |
| Megan Cross | 4500 | 6500 | 9000 |

Values are health points. The blue category refers to the stronger blue pale cannibal, not the masked cannibal.

## Cooperative multiplayer

Characters, voices, dodges, weapons and effects include cooperative synchronization. The host validates damage and inventory operations. Item boxes are personal, and the host's death is designed to preserve teammates' inventories.

The host can enable or disable **RE3R friendly fire** through the pause options. Native PvP settings are also respected. All players must install **the same mod version**.

## Launcher and host tools

The release includes **The Resident Forest 3.exe**, featuring the TR3 logo, a black background, yellow text and installation backups. **Options** contains game-path selection, Browse, Open Folder, original-backup selection, restoration and the developer-tools toggle.

Tools are **disabled by default** and work only in single-player or for the host. Clients cannot use them even with their local checkbox enabled. Tools allow cannibal and preview-character spawning, animation freezing, Jill/Carlos switching, test item-box/item spawning and teleportation to box locations.

| Key | Action |
| --- | --- |
| TAB | RE3R inventory |
| E | Open nearby item box / recover backpack |
| 5–8 | Equip the first four slots |
| Right / left mouse button | Aim / fire |
| R | Reload G19 / M3 |
| F | Reactive dodge |
| F5 | Item-box, item and teleport laboratory* |
| F6 | Spawn cannibal* |
| F8 | Switch Jill / Carlos* |
| F9 / F10 / F11 | Spawn preview character / freeze / change variant* |

\* Requires tools enabled and single-player or host authority.

## Installation and status

For **Windows and The Forest 1.11b**. Close the game, extract **The Resident Forest 3.zip**, open the EXE and press **JUGAR** (Play). Set the game folder in Opciones (Options) if needed; if the launcher requests original files, select your original ModAPI backup.

**0.8.9.1: accepted release, published on GitHub and Melty.** Fixes a 0.8.9 packaging regression that prevented characters and developer tools from working. Development continues: 0.x and 1.x focus on the mashup and co-op; 2.x focuses on consolidating publication and resolving major user-reported bugs; 3.x is reserved for extra content.


---

# The Resident Forest 3 — 0.8.9.1

**Resident Evil 3 Remake dentro de The Forest.** Un mashup que incorpora a Jill Valentine y Carlos Oliveira, sus voces, animaciones, armas e inventario al mundo de supervivencia de The Forest, con soporte para un jugador y cooperativo.

**Idioma actual: únicamente español.** Esta descripción tiene una traducción al inglés, pero la interfaz y los textos del mod todavía no están traducidos.

## Personajes y animaciones

- Jill y Carlos jugables en primera persona, con modelos y voces propios de RE3R.
- La secuencia del avión y el despertar siempre utilizan a Jill. Al comenzar la partida se elige a Jill o Carlos con una probabilidad del 50 % para cada uno.
- Adaptación de cuerpo, brazos, manos y dedos a las acciones de The Forest, junto con animaciones de RE3R para las armas y la esquiva.
- Sonidos de disparo y recarga procedentes de RE3R, interfaz de inventario, iconos y contador de munición con su estética.
- Las armas ceden las manos durante acciones nativas como despellejar animales o cargar troncos.

## Esquiva reactiva

Pulsa **F justo antes de recibir un golpe** para ejecutar una voltereta que te desplaza en dirección contraria al ataque. La cámara sigue los ojos del personaje durante la animación, con aproximadamente un segundo de inmunidad y un quejido de esfuerzo. La esquiva es reactiva: no se activa libremente fuera de una situación de daño.

## Inventario y baúles

- Inventario exclusivo para objetos RE3R de **20 espacios**, separado del inventario nativo; se abre con **TAB**.
- Interfaz compacta y translúcida. Arrastra objetos para moverlos, intercambiarlos o apilar los compatibles. Algunas armas ocupan dos espacios.
- Las teclas **5, 6, 7 y 8** equipan los objetos de los primeros cuatro espacios.
- Cinco baúles de RE3R: cueva de la katana, fondo del agujero central, costa frente al yate, sala de la computadora del final y costa del extremo noroeste.
- Cada baúl tiene **4 espacios independientes**. En cooperativo, cada jugador tiene su propio contenido: tomar un arma no consume la del compañero.
- Guardado por partida y recuperación del inventario RE3R mediante la mochila nativa después de morir.

## Armas disponibles

### G19

Pistola hitscan con **18 de daño**, multiplicador de **×5 a la cabeza** para caníbales y ligero aturdimiento. Cargador de **15 balas** y reserva infinita; hay que recargar. Se encuentra en el baúl frente al yate. Los mutantes grandes no reciben este multiplicador de cabeza.

### Escopeta M3

Capacidad de **4 cartuchos** y reserva infinita, con recarga obligatoria. Dispara **10 perdigones**: uno central recto de 23 de daño y otros nueve de 8, para **95 de daño base**. La dispersión y la retícula cambian al apuntar, quedarse quieto, caminar o correr.

Si los diez perdigones impactan en el mismo enemigo, se aplica **×1.5 al daño**; contra caníbales también produce un fuerte derribo y retroceso. Si los diez alcanzan la cabeza de un caníbal, lo mata y activa el desmembramiento de la cabeza. Está en el baúl de la katana.

### Lanzacohetes infinito

Proyectil físico con modelo de RE3R, munición infinita y explosión al impactar superficies sólidas. Los arbustos y vegetación similar no detonan el misil. La explosión utiliza el sistema de dinamita de The Forest, con **330 de daño**; también se ajustó la dinamita a ese valor. Puede destruir árboles mediante la explosión; G19 y M3 no los talan.

- **Normal y Difícil:** baúles de la computadora del final.
- **Supervivencia Difícil:** baúl de la katana, junto a la M3.

G19 y M3 también afectan animales, maletas y objetos destruibles compatibles. Las armas incluyen apuntado, disparo y sonidos de RE3R; G19 y M3 incluyen sus recargas.

## Balance de enemigos

| Enemigo | Normal | Difícil | Supervivencia Difícil |
| --- | ---: | ---: | ---: |
| Caníbal delgado / hambriento | 60 | 90 | 120 |
| Líder / con antorcha | 120 | 180 | 240 |
| Pálido de cueva | 160 | 240 | 320 |
| Pálido azul resistente | 220 | 330 | 440 |
| Armsy | 850 | 1300 | 1800 |
| Virginia | 750 | 1150 | 1600 |
| Cowman | 1000 | 1500 | 2000 |
| Megan Cross | 4500 | 6500 | 9000 |

Los valores son puntos de vida. La categoría azul corresponde al pálido azul resistente, no al caníbal enmascarado.

## Cooperativo

Personajes, voces, esquivas, armas y efectos cuentan con sincronización cooperativa. El host valida el daño y las operaciones de inventario. Los baúles son personales y la muerte del host no debe reiniciar el inventario de sus compañeros.

El host puede activar o desactivar el **fuego amigo RE3R** desde las opciones de pausa. Se respeta además la configuración PvP nativa. Todos los jugadores deben instalar **la misma versión del mod**.

## Iniciador y herramientas del host

La entrega incluye **The Resident Forest 3.exe**, con logo TR3, fondo negro, texto amarillo e instalación con respaldo. **Opciones** reúne la ruta del juego, Examinar, Abrir carpeta, respaldo original, restauración y activación de herramientas de prueba.

Las herramientas están **desactivadas por defecto** y sólo funcionan en un jugador o para el anfitrión. Un cliente no puede utilizarlas aunque active su casilla local. Permiten invocar caníbales y figuras, congelar animaciones, cambiar entre Jill y Carlos, generar baúles/objetos de prueba y teletransportarse a sus ubicaciones.

| Tecla | Acción |
| --- | --- |
| TAB | Inventario RE3R |
| E | Abrir baúl / recuperar mochila cercana |
| 5–8 | Equipar los primeros cuatro espacios |
| Botón derecho / izquierdo | Apuntar / disparar |
| R | Recargar G19 / M3 |
| F | Esquiva reactiva |
| F5 | Laboratorio de baúles, objetos y teletransportes* |
| F6 | Invocar caníbal* |
| F8 | Cambiar Jill / Carlos* |
| F9 / F10 / F11 | Invocar figura / congelar / cambiar variante* |

\* Requiere herramientas activadas y ser host o jugar en solitario.

## Instalación y estado

Para **Windows y The Forest 1.11b**. Cierra el juego, extrae **The Resident Forest 3.zip**, abre el EXE y pulsa **JUGAR**. Configura la carpeta del juego en Opciones si hace falta; si el iniciador solicita los archivos originales, selecciona el respaldo original de ModAPI.

**0.8.9.1: versión aceptada y publicada en GitHub y Melty.** Corrige una regresión de empaquetado de la 0.8.9 que impedía funcionar a los personajes y a las herramientas. El proyecto continúa en desarrollo: 0.x y 1.x se centran en el mashup y el cooperativo; 2.x, en consolidar la publicación y resolver fallos importantes reportados por usuarios; 3.x, en contenido extra. Disfruta del mod papu, cualquier cosa de bug mencionala pa poder corregirla en futuras actualizaciones de esta madre, un gusto y disfruta

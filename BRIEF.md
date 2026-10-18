**Autor:** Alejandro Espinosa Leal  
**Módulo:** Diseño de Interfaces Web · Órbita 1 (Diseñar para que funcione)  

---
## 1. El problema (De la hipótesis inicial a los datos reales)  

* **Hipótesis del primer día:**  
"Creo que las personas que juegan de forma competitiva a shooters como Valorant o Fortnite necesitan encontrar compañeros de equipo fiables de su mismo nivel y horario, pero dependen del emparejamiento aleatorio (randoms) donde pierden partidas y pasan un mal rato."  
  
* **Problema validado con la investigación:**
  Tras pasarle el formulario a mis amigos que juegan de forma competitiva comprobe que el 100% son jovenes de 18 - 25 años y que juegan entre 5 y 10 horas semanales a juegos competitivos
  y habian intentado  buscar personas fijas con las que jugar en discord pero estos metodos no les habia funcionado

El problema que intenta resolver mi aplicacion se mira en tres datos de mi encuesta:
  * La diferencia de nivel que habian entre algunos jugadores y ellos el 75% de las personas que icieron la encuesta dieron la misma respuesta de diferencia de nivel
  * Toxicidad y falta de comunicacion : Sufren con frecuencia insultos y falta de comunicacion o por que no tenian micro o no querian hablar
  * La falta de poder coordinarse en un mismo horario


## 2. El alcance (Qué entra en mi MVP y qué se queda fuera)
### Funciones que SÍ entran en esta primera versión (MVP)
He decidido meter solo las funciones necesarias para que una persona pueda entrar, buscar un compañero de su nivel y jugar sin malos ratos:
* **Inicio de sesión, registro y test inicial en 3 pasos:** nada más registrarte eliges a qué juegas (Valorant o Fortnite), cuál es tu rango/rol y en qué horario sueles jugar.
* **Buscador de compañeros con filtros:** una pantalla para filtrar directamente por juego, nivel y horario.
* **Lista de jugadores compatibles e invitación:** te sale la lista de personas que encajan contigo y un botón para enviarles invitación.
* **Sala de chat:** un chat sencillo para hablar con el compañero que ha aceptado, pasarse el ID del juego y entrar a la partida.
* **Valorar al compañero (de 1 a 5 estrellas) y reportar:** al terminar la partida puedes puntuar qué tal ha jugado y su actitud, o reportarlo si ha sido tóxico.

### Funciones que SE QUEDAN FUERA de esta versión (y por qué)
* **Chat de voz dentro de la web:** lo dejo fuera porque, una vez se pasan el ID por el chat de texto, ya hablan por el chat de voz del propio juego o por Discord.
* **Torneos y ligas:** lo dejo fuera porque mis amigos lo que quieren es encontrar compañero rápido para echar unas partidas por la tarde o por la noche, no apuntarse a un torneo largo.
* **Subir vídeos de jugadas o foros generales:** lo dejo fuera porque no ayuda a encontrar equipo rápido y además haría que la web pesara mucho más.


* **Mis compañeros y Mi perfil:** un apartado para guardar a la gente con la que has jugado bien para volver a invitarla otro día, y tu perfil para cambiar tu rango o tu horario.

## 3. Criterios de éxito (Cómo sabré si funciona)
Para comprobar que mi diseño se entiende y funciona bien, me fijo en tres cosas:
* **Que sea rápido empezar:** que un usuario nuevo pueda registrarse, rellenar los 3 pasos de su juego, nivel y horario, y mandar su primera invitación a un compañero en **menos de 2 minutos** sin que yo le tenga que explicar nada.
* **Que nadie se pierda por los menús:** que desde la pantalla de `Home / Inicio` se pueda llegar hasta la `Sala de chat y valorar` en **3 pasos como máximo** sin meterse en pantallas equivocadas.
* **Que se entienda cómo valorar o reportar:** que al acabar la partida cualquier persona encuentre a la primera dónde ponerle las estrellas al compañero o dónde darle a reportar si ha sido tóxico.
---


## 5. Restricciones del proyecto   
* Creo que el proyecto en movil no va a ser igual de funcional que een el ordenador ya que al jugar va a ser mas facil abrir la web en el navegador que abrirla en el movil
* Otro problema que creo que si no hay mucha perosnas en la app no se va a poder utizar bien ya que necesita que haya gente para poder buscar y si no hay no puedes busar
  
## Enlaces de mi entrega
* **Tablero de FigJam:** [tablero figma](https://www.figma.com/board/TjHeSYfXUaEaJ17Wym6KMY/Ideas-proyecto-dise%C3%B1o-interfaz--Copia-?node-id=0-1&t=eV4dnkCPQYOPwlcp-1)
* **Wireframes en Figma Design:** [Wireframe](https://www.figma.com/design/7znxZgshnL7yaQuGA1OGbH/Untitled?node-id=0-1&t=eV4dnkCPQYOPwlcp-1)
* **Prototipo navegable:** [Ver prototipo navegable](https://www.figma.com/proto/7znxZgshnL7yaQuGA1OGbH/Untitled?node-id=6-87&starting-point-node-id=6%3A87&t=TijpbDHh5wrv5JjW-1)
* **Registro de uso de IA:** [Ver CHANGELOG.md](./CHANGELOG.md)

# Resources
Game development resources

---
# Day 3 - build your game!
# USEFUL

[Sandbox](https://phaser.io/sandbox/edit/1)
[Phaser CE documentation](https://photonstorm.github.io/phaser-ce/index.html#toc-2)
[Docs search](https://phaser.io/learn/chains)


# GAMEPLAY

## Camera
[Follow](https://phaser.io/examples/v2/camera/basic-follow)
[Other examples (cull, fade, lerp, ...)](https://phaser.io/examples/v2/category/camera)

## GUI
[Image](https://phaser.io/examples/v2/basics/01-load-an-image)
[Label](https://phaser.io/examples/v2/basics/06-render-text)
[Buttons](https://phaser.io/examples/v2/category/buttons)
[Button spritesheet example](http://examples.phaser.io/assets/buttons/button_sprite_sheet.png)

## Movement mechanics
[Start-stop](phaser.io/sandbox/upPqKhTW)
[Acceleration](phaser.io/sandbox/ZKpVCuzC)
[Drag and velocity cap](phaser.io/sandbox/jRkVFWvZ)
[Flapping](phaser.io/sandbox/BFQktsMK)
[Jumping](phaser.io/sandbox/AVpfQZIJ)
[Gravity and events](phaser.io/sandbox/FxbSZrxg)

## More mechanics

[Game mechanic explorer](https://gamemechanicexplorer.com/#platformer-3)

## AI, architecture, optimization, ornaments
[Spawing, steering (hooming), OOP, object pooling, sprite animation](phaser.io/sandbox/vwSYxOTZ)

## Events
[Signals](https://photonstorm.github.io/phaser-ce/Phaser.Signal.html)

# ARCHITECTURE

## Game states
[Simple example](http://www.emanueleferonato.com/2014/08/28/phaser-tutorial-understanding-phaser-states/)

[Richer example](https://mmcfarland.itch.io/phaser-menu-system)

## Full projects
[Full game: infinite jumper](https://github.com/shohan4556/jolly-jumper)

[Phaser project template using typescript and visual studio code](https://github.com/mujina93/template_typescript_phaser)

# BONUS

[Phaser examples](https://phaser.io/examples/v2/search?search=event)

[Phaser games examples](https://phaser.io/examples/v2/category/games)

[List of video games with code on github](https://github.com/leereilly/games/)

[Turn based system](https://phaser.io/news/2018/02/turn-based-battle-system-tutorial)

[Tutorial on steering and finite state machines A.I.](https://www.raywenderlich.com/24824/introduction-to-ai-programming-for-games)

[Procedurally Generated Content wiki](http://pcg.wikidot.com/)

[Assets](http://examples.phaser.io/assets/)

---
# Day 2 - design your game!
Recap degli argomenti trattati: 

Chi è il **game designer**? 
* NON è il capo del team, né il leader né altro.
* Fa le cose che vedremo di seguito.

È necessario in un team?
* No, ma si!
* Anche se tutti giochiamo e siamo in grado di creare giochi, avere una persona specializzata che (tendenzialmente) ha studiato per questo ruolo e che quindi ha degli strumenti in più, è molto utile.
* E poi fa cose che tendenzialmente nessun altro ha voglia e sbatta di fare! Quindi bene!

Che cosa fa in un gioco:
1. Stabilisce gli obiettivi. Un obiettivo deve essere:
	* Chiaro.
	* Semplice.
	* Proporzionato alle capacità del giocatore in quel momento.
	* Può essere esplicito, facoltativo o implicito.

2. Pone le regole. Una regola...
	* Non deve essere equivoca.
	* Deve essere semplice.
	* Precisa.
	* Verosimile.

3. Crea la sfida. La sfida...
	* Serve a far restare il giocatore nel sistema!
	* Può essere individuale, cooperativa o competitiva, o tutte e tre contemporaneamente!

4. Interazioni
	* Devono esserci, altrimenti è un film!
	* Può essere diretta (interagisco con un sistema) o mediana (interagisco con un sistema che agisce su un altro sistema).

5. GDD (Game Design Document)
	* È un documento scritto dove c’è tutto quello che si deve sapere sul gioco, la bibbia!
	* Come si scrive un GDD? Sta a voi!

6. Prototipazione
	* Dà la prima impressione sul gioco
	* Può essere fatta su un engine (Prototype) o su carta (Paper-prototype).

7. Testing
	* Per verificare che il gioco prosegua sulla retta via.
	* Utile per il sistema MDA, continua a leggere per saperne di più!

Qualità di un game designer:
1. Dialogo
	* È importantissimo! È stupido dirlo ma è bene ripeterlo. Si basa su: ascoltare, pensare e parlare.
	* È fondamentale per la scrittura dei GDD e dei regolamenti.
	* Come si può migliorare? Tramite Interazioni sociali, leggendo e giocando ai giochi da tavolo e leggendo e studiando i loro regolamenti.

2. Problem solving
	* L’uomo è pagato per risolvere problemi, e lo sono anche i game designer (di solito).
	* Come lo posso rendere interessante? Come lo posso rendere divertente? Come lo posso rendere emozionante?
	* Come si può migliorare? Osservando e studiando, estensione della propria conoscenza verticale (game design), orizzontale (programmazione, 2D, 3D, etc) e dell’inutile (giochi, musica, film, libri, fumetti, anime, serie tv, attualità, etc)

3. Creatività
	* È fondamentale ma è complicato!
	* Un’idea "mai pensata" è già stata pensata miliardi di volte :(
	* Come si può migliorare? Tramite il Brain storming, il pitching e la cultura dell’inutile.

Strumenti di un game designer
* MDA: 
	* **Meccaniche**: le meccaniche sono le regole del sistema gioco! 
	* **Dinamiche**: sono le interazioni tra le varie regole! Più dinamiche ci sono, più cresce il gameplay emergente.
	* **Estetiche**: è l’esperienza che prova il giocatore quando gioca! Tutte le esperienze sono state categorizzate da Hunicke, LeBlanc e Zubek in 9 categorie: 
		1. challenge
		1. fellowship
		1. dominance
		1. submission
		1. discovery
		1. fantasy
		1. narrative
		1. expression
		1. sensation.
---

# Day 1 - the kickoff!

## Workshop

[Sandbox](https://phaser.io/sandbox/edit/1)

[Shortcuts](https://phaser.io/sandbox/keyboard-shortcuts)

Simple game, step by step:

1. [BASICS](https://phaser.io/sandbox/LPRbKAxR)
2. [WORLD](https://phaser.io/sandbox/tWlwmbcG)
3. [PHYSICS](https://phaser.io/sandbox/SfCmCazQ)
4. [PURPOSE](https://phaser.io/sandbox/CixMilse)
5. [FEEDBACK](https://phaser.io/sandbox/jCwLGDAa)
6. [TENSION](https://phaser.io/sandbox/diJSlkmc)



## Phaser 2

[Home](https://phaser.io/)

[Sandbox info](https://phaser.io/sandbox)

[Download](https://phaser.io/download/release/2.10.5)

[Examples](https://phaser.io/examples)

[Assets](http://examples.phaser.io/assets/)

[Documentation](https://phaser.io/learn/chains)



## Bonus material

[Phaser 3 download](https://phaser.io/download/stable)

[Game Mechanic Explorer](https://gamemechanicexplorer.com/#platformer-1)

[Chiptune Radio](https://www.youtube.com/Krelez/live)

---

# Jams / Contests

[1GAM](http://www.onegameamonth.com/)

[Ludum Dare](http://ldjam.com/)

[itch.io](https://itch.io/jams)

[Indie game jams](http://www.indiegamejams.com/)

---

# Learning Material

## Hubs (lists of other resources, mixed types)

[Game design and Digital art](https://gameanalytics.com/blog/21-free-learning-resources-for-game-developers.html)

[Game development for beginners and Gamification](https://www.springboard.com/blog/free-online-courses-game-development-gamification/)



## Everything

[Gamasutra](https://www.gamasutra.com/)

[Gamedev.net](https://www.gamedev.net/)

[Gamedev forums](https://www.gamedev.net/forums/)



## Game development

[Programming and Game development](https://eliasdaler.github.io/programming-and-gamedev-resources/)

[GameDev Resources](https://github.com/Kavex/GameDev-Resources)

[Game programming patterns](http://gameprogrammingpatterns.com/)

[Red Blob Games - Maths and Computer Science concepts](https://www.redblobgames.com/)

["Big" game engines](https://blog.instabug.com/2017/12/game-engines/)

[Game engines list](https://en.wikipedia.org/wiki/List_of_game_engines)

[Free game engines](https://en.wikipedia.org/wiki/Category:Free_game_engines)

[AI resources](https://www.quora.com/What-are-some-good-resources-to-learn-AI-game-programming)



## Game design

[Extra Credits](https://www.youtube.com/user/ExtraCreditz)

[Game Design Workshop](https://www.amazon.com/Game-Design-Workshop-Playcentric-Innovative/dp/0240809742)



## Digital art

[Digital art sites](https://www.creativebloq.com/digital-art/10-top-digital-art-resources-5131223)

[Pixel art tools](https://v-play.net/game-resources/make-pixel-art-online)

[Concept Art Empire](https://conceptartempire.com/)



## Animation

[6 Animation resources](https://www.milessebesta.com/animation/best-animation-resources-learning-animation/)



## Audio

[Websites offering free game sounds](https://v-play.net/game-resources/16-sites-featuring-free-game-sounds)



## Motivational

[How to succeed at making 1GAM](https://gamedevelopment.tutsplus.com/articles/1gam-how-to-succeed-at-making-one-game-a-month--gamedev-3695)

[Just do it](https://www.youtube.com/watch?v=ZXsQAXx_ao0)



## Documentaries

[Double Fine Adventure (Broken Age)](https://www.youtube.com/watch?v=AdXvZgIV1Q0&list=PLIhLvue17Sd7F6pU2ByRRb0igiI-WKk3D)

[Hellblade Development Diary](https://www.youtube.com/watch?v=42wG9WEl_9o&list=PLbpkF8TRYizaT6GfMcKBG-RoUOQ6BJRXp)

---

## Conferences and Awards

[GDC](http://www.gdconf.com/)

[E3](https://www.e3expo.com/)

[Academy of Interactive Arts and Sciences](http://www.interactive.org/)

[Game Developers Choice Awards](http://www.gamechoiceawards.com/)

---










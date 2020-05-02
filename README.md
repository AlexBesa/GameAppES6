# GameApp-with-Classes-Objects

1. Identificati obiectele care apar in aplicatia voastra

2. Facem clase pentru fiecare obiecte iar dupa se vor creea obiecte cu ajutor clasesi - 

Recomandare impartire de clase: ( sunt doar sugesti, idee este ca fiecare clasa sa aiba un scop clar. Daca ne gandim la FetchApi , stim ca doar acolo se fac apeluri catre server )

- Game: aici puneti avea metode care creaza reprezentarea in DOM a unui game plus informatile lui

- FetchApi: aici aveam doar call-uri catre api nostru, fiecare va fi o metoda separata. De exemplu: getGameById, updateGame, deleteGame etc

- App ( acesta clasa App este optionala, scopul ei este sa gestioneze Game Si FetchApi. In loc de o clasa App, puteti avea functie simple )

3. Impartim in mai multe fisiere. Fiecare clasa cu fisierul ei.


Rewrite Games App with ES6
Cerinta: Tot codul se va converti cu ES6

1. Pentru clase se va folosi 'class Game  { }', nu se vor mai pune metodele pe prototype

2. Peste tot unde a-ti folosit var, sa va inlocui cu let/const

3. Unde sa folosit 'const self = this', ca sa puteti accesa this in interiorul unui callback => va deveni un arrow function

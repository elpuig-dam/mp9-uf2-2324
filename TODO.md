<hr>

### Setmana del 02/10-06/10
- Exercicis Callable, Runnable i Executors

TODO
### a1 (Executors, Callablles & Runnables)
- [X] Transformar la implementació del exercici [Callable Multiplicació](src/a1/Multiplicacio.java) en una implementació sense fer servir processos. (Sense Callable ni Executor)
- [X] Transformar la implementació [Alumne](src/a1/Alumne.java) i [Notes](src/a1/Notes.java) en una execució concurrent.
- [x] Cursa dde cargols
  > Entendre l'exercici der la cursa de cargols amb ScheduledThreadPool.
  > Fitxers: [Cargol](src/a1/Cargol.java), [Monitor Cargols](src/a1/MonitorCargols.java) i [Cursa de Cargols](src/a1/CursaCargols.java)
- [x] Exercici Donar punts i llegir punts a un Jugador
  > Fitxers: [Jugador](src/a1/Jugador.java), [Donar Punts](src/a1/pDonarPuntsJugador.java), [Llegir Punts](src/a1/pLlegirPuntsJugadors.java) i [Jugar](src/a1/Jugar.java)  
- [ ] Exercici Paletes i FerParet
  > Tenim uns paletes que tenen la tasca de construir una paret a base de posar maons.
  > Podeu veure el codi als fitxers [Paleta.java](src/a1/Paleta.java) i [FerParet.java](src/a1/FerParet.java).
  > Volem adaptar aquest codi perquè els paletes treballin alhora (concurrentment) i no com ara, 
  > que fins que un paleta no ha posat els seus maons no continua l'altre.  
  > *_Atenció: fer servir Runnable en comptes de Callable i un ThreadPoolExecutor (NO un ScheduledThreadPool)_ Això implica que el mètode invokeAll no serveix per executar concurrentment la llista de paletes(Runnables). Trobeu la manera de fer-ho!

<hr>

### a2  (Fork-Join Pool)  
- [x] Exercici dels apunts [Maxim](src/a2/Maxim.java)  i [MaximTask](src/a2/MaximTask.java) 
- [x] [Càlcul del Factorial](src/a2/FactorialTask.java)  


### a3 (Semàfors, Monitors i Sincronització)
- [x] Threads
- [x] Exercici CompteEstalvi (synchronized)
  >Crear una classe CompteEstalvi amb els mètodes dels apunts, ingressar i treure diners, després en un programa main
    crear 10 fils que facin 1000 operacions de cada tipus. Comprovar que el resultat és el correcte.
- [x] [Comandament i família](src/a3/comandament)
- [x] [Pot de galetes](src/a3/galetes)  
  > 1. Els MembresFamilia que volen agafar el pot (Threads) són: el pares posen galetes al pot, els fills agafen 1 galetes del pot  
  > 2. Pot de galetes (monitor) : mètodes-> agafarGaleta, deixarPot, omplirpot(omplir fins al maxim de capacitat)  
  > 3. Condicions: Els pares no poden agafar el pot si no està buit i els fills no poden agafar el pot si està buit   
- [ ] [Filòsofs](src/a3/filosofs)  


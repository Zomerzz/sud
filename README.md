<h1>🧙‍♂️ SUD - Gioco di Avventura Testuale</h1>

  <p><strong>SUD</strong> è un gioco di avventura testuale minimalista sviluppato in Java. Esplora un mondo interattivo dove le tue scelte influenzano il corso della storia.</p>

  <h2>🚀 Caratteristiche</h2>
  <ul>
    <li><strong>Gameplay interattivo</strong>: Muoviti tra stanze, interagisci con entità e lancia incantesimi.</li>
    <li><strong>Design modulare</strong>: Codice organizzato con una chiara separazione delle responsabilità.</li>
    <li><strong>Meccaniche di dadi personalizzate</strong>: Sistema di dadi unico per determinare gli esiti.</li>
    <li><strong>Gestione delle eccezioni</strong>: Terminazione del gioco gestita in modo elegante con eccezioni personalizzate.</li>
  </ul>

  <h2>🛠️ Come iniziare</h2>

  <h3>Prerequisiti</h3>
  <ul>
    <li>Java Development Kit (JDK) 8 o superiore</li>
    <li>Un IDE come IntelliJ IDEA o Eclipse</li>
  </ul>

  <h3>Installazione</h3>
  <pre><code>git clone https://github.com/Zomerzz/sud.git
cd sud
javac *.java
java Start</code></pre>

  <h2>🗂️ Struttura del progetto</h2>
  <ul>
    <li><code>Game.java</code>: Ciclo di gioco principale e logica di gioco.</li>
    <li><code>Start.java</code>: Punto di ingresso dell'applicazione.</li>
    <li><code>Spell.java</code>: Meccaniche relative agli incantesimi.</li>
    <li><code>dices.java</code>: Implementazione del sistema di dadi.</li>
    <li><code>GameClosingException.java</code>: Gestione della chiusura del gioco tramite eccezioni.</li>
    <li><code>entity/</code>, <code>items/</code>, <code>rooms/</code>: Pacchetti per entità, oggetti e definizioni delle stanze.</li>
  </ul>

  <h2>🤝 Contribuire</h2>
  <p>Contributi e suggerimenti sono benvenuti! Sentiti libero di fare un fork del repository e inviare una pull request.</p>

  <h2>📄 Licenza</h2>
  <p>Questo progetto è open-source e disponibile sotto licenza <a href="LICENSE">MIT</a>.</p>

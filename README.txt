Questo progetto consiste un giochino in Realtà Aumentata.
Lo scopo del giochino è quello di evitare che le colonne tocchino la macchina.
La macchina si può muovere solo a destra e sinistra, e per farlo si possono usare o i due bottoni presenti nell'interfaccia, o le frecce direzionali sulla tastiera del PC.
L'idea originale era di caricare i file su un sito online e di fare le prove con il telefono, ma ci sono stati dei problemi nell'utilizzare la telecamera.
Ho usato un programma, chiamato Camo Studio, che mi ha permesso di collegare la fotocamera posteriore del mio iphone con il Mac, potendo così utilizzare la camera del telefono come webcam del PC.
Sono presenti due file .html nella cartella:
-index.html: versione finale dove il giochino è giocabile in AR.
-prova3d.html: versione utilizzata in fase di prova, che mi ha permesso di creare/modificare la scena del gioco.
Per strutturare la parte CSS della pagina ho usato un programma online (link: https://cssgrid-generator.netlify.app), che mi ha facilitato la strutturazione dell'interfaccia.
Per rilevare se la macchina ha avuto un contatto con una delle due colonne, e per limitare il movimento della macchina solo dentro la strada, si sono utilizzati dei bounding box.
Quando una colonna riappare, la sua velocità è aumentata di +0.1.
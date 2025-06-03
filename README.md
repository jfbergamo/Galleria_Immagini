> Anno scolastico 2024-2025
> Bergamasco Jacopo, Classe 5AIA, ITST J.F. Kennedy, Pordenone
# GALLERIA IMMAGINI

Web application scritta in [PHP](https://www.php.net/) che presenta una galleria di immagini caricabili dagli utenti.
L'applicazione è fornita di un sistema di autenticazione per permettere agli utenti di creare dei propri account, con cui si potrà caricare le proprie immagini e interagire con quelle degli altri utenti.
## Pagina principale
- La pagina è formata da una schermata che mostra tutte le immagini caricate nell'app.

![Pagina principale vuota](https://media.discordapp.net/attachments/855422280125251636/1379035957193478256/image.png?ex=683ec6d1&is=683d7551&hm=17a08ec6de742c0eaa9caceb659666662c94552d9081f855412025c546092d0e&=&format=webp&quality=lossless&width=1091&height=614)

- L'utente non loggato può visualizzare tutte le immagini inserite il loro conteggio dei like, ma non può né caricare, né mettere like alle immagini.

![Pagina principale con immagini](https://media.discordapp.net/attachments/855422280125251636/1379038451856576542/image.png?ex=683ec924&is=683d77a4&hm=abf97ef9ecdeb3da728c9d4d6c873073842843149d8c93d18170b36528242e7a&=&format=webp&quality=lossless&width=1091&height=614)

- Nella pagina è presente una navbar in cui è possibile recarsi alla schermata di login o di registrazione. L'utente loggato vedrà nella stessa navbar un bottone per eseguire il logout e uno per caricare un'immagine.

![Navbar](https://media.discordapp.net/attachments/855422280125251636/1379039162921128046/image.png?ex=683ec9cd&is=683d784d&hm=ce4b5a42f4ee4d48ee4d33199038e093a514c33b8ee6eac09e44c4dc0e30c36d&=&format=webp&quality=lossless&width=427&height=137)

- Il form di caricamento dell'immagine compare attraverso una finestra modale dinamica creata col framework Bootstrap5.

![Modale caricamento](https://media.discordapp.net/attachments/855422280125251636/1379040168975274035/image.png?ex=683ecabd&is=683d793d&hm=ec27fc9189c9369c6af332f27f3964d86568fd459a9b9ca1045a5db771251a4d&=&format=webp&quality=lossless&width=702&height=385)

- L'utente loggato può caricare immagini, mettere e rimuovere like dalle immagini e rimuovere le immagini caricate da lui

![Pagina principale loggata](https://media.discordapp.net/attachments/855422280125251636/1379040643069775963/image.png?ex=683ecb2e&is=683d79ae&hm=cfda2dfdfdcd46a02ff98129940441bc82943c48965c6597b7c9773271b8f4dd&=&format=webp&quality=lossless&width=1091&height=614)
## Pagine di accesso

![Pagine di accesso](https://media.discordapp.net/attachments/855422280125251636/1379042021368660069/image.png?ex=683ecc77&is=683d7af7&hm=ffedca483f50de24591bd59f53017e29affc551089fc83de3c17f867500f104b&=&format=webp&quality=lossless&width=1091&height=477)

## Schema concettuale del database

![Schema concettuale](https://media.discordapp.net/attachments/855422280125251636/1379461482185494600/scheme.png?ex=6840531e&is=683f019e&hm=a43a89e75438da7322455dbf0f04cd8ecdd9ea5a45082943c8d73b897308fe73&=&format=webp&quality=lossless&width=1091&height=536)

## Installazione
Per hostare il sito è necessario inizializzare il database. Il DBMS utilizzato nell'applicazione è [MySQL](https://www.mysql.com/), tutte le definizioni delle strutture dati sono contenute nel file `init.sql`, eseguendo quel file si inizializzerà il database.
# JuPSQL_notebook
Interaktív PSQL lekérdezés futtatása és eredmény megjelenítése.

A Colab Secrets segítségével kezeli a PostgreSQL jelszót.
Szabályos PostgreSQL lekérdezéseket fogad szöveges formában.
Opcionálisan megadható tábla nevét használ, de alapértelmezettként a "teleprompter_hashed" táblát célozza. A lekérdezés eredményeit pandas DataFrame-ként adja vissza. (SQLAlchemy) connection pool-lal és timeouttal (1 perc = 60 másodperc)

Interaktív PSQL lekérdezés futtatása és eredmény megjelenítése.
A függvény egy szövegmezőt és egy futtatás gombot jelenít meg, amelyek segítségével a felhasználó PostgreSQL lekérdezéseket futtathat. Az eredményeket pandas DataFrame-ként jeleníti meg, és méri a lekérdezés végrehajtási idejét.

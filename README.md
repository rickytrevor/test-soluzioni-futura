# test-soluzioni-futura

per far partire il progetto molto semplicemente eseguite il git clone ed eseguire il comando


```
docker-compose up 
```

fatto questo aprire il browser web e andare su localhost:8080 per il frontend, il backend è in ascolto sulla porta 3000
gli endpoint dell'API sono 
```
POST /importDataFromFile con parametro soluzioni che contiene il file
```

```
GET /pendingData
```

```
GET /data?from=&limit=
```


nel progetto è presente anche uno script di utility che genera un file di esempio come da specifiche, per lanciarlo recarsi nella directory backend e lanciare 

```
npm run generate
```

La modalità di sviluppo del server si attiva con 
```
npm run develop
```

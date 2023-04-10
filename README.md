# pi-docker

Questo repo contiene un docker compose yml che avvia dei servizi

## Servizi

- bitcoind: un nodo bitcoin
- electrum: un server electrum

Tra i vari servizi viene avviato anche onionize, serve ad esporre i vari servizi ad un endpoint .onion, in modo da rendere l'accesso possibile da remoto senza acquistare un dominio e, sopratutto, accedere sotto rete tor.

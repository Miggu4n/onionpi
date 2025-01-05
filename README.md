## Simple docker compose to expose services on TOR

### Why using this?
Because instead of using one different url for each service, you can expose many services using only one url.
In this example we are hosting an openspeedtest istance on http://openspeedtest.[...].onion

1. Add services to the docker compose
2. Edit nginx.conf to proxy your services
3. run docker exec onionize cat /var/lib/tor/onion_services/nginx/hostname
4. share your services through one unique url and exposing only port 80

# Rasberry Pi 5 Homelab Nerv
Mein Rasberrypi 5 Homelab Projekt. Das Projekt beinhaltet Dienste wie Monitoring, eine Reverse Proxy Struktur und eine private Cloud.

## Hardware:

### Server: 
        Rasberry Pi 5
          4GB RAM
           Running Rasberry Pi OS

## Software :

### Services auf dem Docker: 
        Nextcloud (Cloud)
          Pi-hole (Adblock DNS)
            Prometheus (Monitoring)
              Grafana (Monitoring Dashboard)
                Protainer (Docker Management)
                  Nginx Proxy Manager (Reverse Proxy)

### Domain: 
       nervhome.com
         nextcloud.nervhome.com

## Architektur: 
      Cloudflare Tunnel -> Nginx Reverse Proxy -> Docker Containers

             

## Ziele von dem Projekt:

                       Optimierung der Collabra etc. für bessere Auslastung des Rasberry Pi 
                       Automatische Backups der Cloud
                       Passwort manager
                       API Gateway
                  

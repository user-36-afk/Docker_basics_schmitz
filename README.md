# Docker_basics_schmitz


## Pi-hole

Pi-hole ist ein DNS-basierter Werbe- und Trackingblocker. Er filtert DNS-Anfragen und verhindert dadurch das Laden von Werbung und Tracking-Diensten bereits auf Netzwerkebene.

### Starten

```bash
docker compose -f pihole.yml up -d
```

---

## Portainer

Portainer stellt eine grafische Verwaltungsoberfläche für Docker bereit. Container, Images, Volumes und Netzwerke können komfortabel über den Browser verwaltet werden.

### Starten

```bash
docker compose -f portainer.yml up -d
```

---

## Watchtower

Watchtower überwacht bestehende Container und aktualisiert diese automatisch, sobald neue Images verfügbar sind.

### Starten

```bash
docker compose -f watchtower.yml up -d
```

---

## Nginx

Nginx ist ein leistungsfähiger Webserver und Reverse Proxy. In diesem Beispiel wird ein einfacher Webserver-Container bereitgestellt.

### Starten

```bash
docker compose -f nginx.yml up -d
```

---


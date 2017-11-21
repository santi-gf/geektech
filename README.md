## Probando GitHub Pages

1. <http://google.com/search?q=gatitos+monos>
2. Más cosas


---

ISC desde la terminal

- Comprobar el estado: `service isc-dhcp-server status`
- Iniciar el servicio: `service isc-dhcp-server status`
- Detener el servicio: `service isc-dhcp-server stop`
- Reiniciar el servicio: `service isc-dhcp-server restart`

Pedir una IP por DHCP:
```bash
$ dhclient -v eth0
```

Borrar la configuración DHCP:
```bash
dhclient -r -v eth0
```


------

Made with :heart:

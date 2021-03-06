##Bienvenidos al proyecto [Gateproxy] (http://www.gateproxy.com)

<a target="_blank" href=""><img src="https://img.shields.io/badge/Development-ALPHA-blue.svg"></a>

[Gateproxy] (http://www.gateproxy.com) es un servidor para administrar pequeñas y medianas redes [LAN] (https://es.wikipedia.org/wiki/Red_de_%C3%A1rea_local), lo más intuitivo y desatendido posible, apto para el manejo del usuario, sin importar si tiene o no un alto grado de conocimientos en GNU/Linux, generando así una mejor experiencia.

El script de instalación y configuración es totalmente automatizado y personalizable, de acuerdo a las necesidades del administrador u organización, con una interacción mínima durante proceso, reduciendo así la curva de aprendizaje. Puede ser implementado tanto en un servidor "físico", como en una VM, para mayor flexibilidad y portabilidad.

**Descripción**

- HowTO:        [Gateproxy.pdf] (https://goo.gl/ZT4LTi)
- Version:      1.0 Alpha

**Requisitos Mínimos**

- GNU/Linux:    [Ubuntu 16.04.x LTS x64] (http://www.ubuntu.com/download)
- Procesador:   Intel compatible 1x GHz
- RAM:          4GB
- DD:           200 GB
- Internet:     Alta velocidad (recomendado)
- Bash:         4.3x (verifique con echo $BASH_VERSION)
- Desktop:      [Mate] (http://mate-desktop.org/) (Opcional)

**Instalación:**

Abra el terminal y ejecute (no-root):
```
$ git clone https://github.com/maravento/gateproxy
$ chmod +x gateproxy/gateproxy.sh && gateproxy/gateproxy.sh
```
![Gateproxy Script](https://1.bp.blogspot.com/-8WxgAY93gmg/V9AQCT2MUZI/AAAAAAAACwQ/9j6hfFc8ot8CD-vcailpFhGd1ChudwB6QCLcB/s1600/gateproxy.jpg)

**Dependencias:**
```
sudo apt-get -y install git apt dpkg
```

Si tiene una versión anterior a [Ubuntu 16.04.x LTS x64] (http://www.ubuntu.com/download), actualice con:
```
sudo do-release-upgrade -d
```

**Proyectos Incluidos:**

[Blackweb] (https://github.com/maravento/blackweb)

[Blackip] (https://github.com/maravento/blackip)

[Blackstring] (https://github.com/maravento/blackstring)

**Exención de Responsabilidad**

Este script puede dañar su sistema si se usa incorrectamente. Úselo bajo su propio riesgo. Lea [HowTO Gateproxy] (https://goo.gl/ZT4LTi)

**Agradecimientos**

Agradecemos a todos aquellos que han contribuido a este proyecto, en especial [novatoz.com] (http://www.novatoz.com)

**Legal**

This Project is educational purposes. Este proyecto es con fines educativos

© 2016 [Gateproxy] (http://www.gateproxy.com) por [maravento] (http://www.maravento.com) se distribuye bajo una [Licencia Creative Commons Atribución-NoComercial-CompartirIgual 4.0 Internacional] (http://creativecommons.org/licenses/by-nc-sa/4.0/). Basada en una obra en maravento. Permisos que vayan más allá de lo cubierto por esta licencia pueden encontrarse en maravento

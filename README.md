##Bienvenidos al proyecto [Gateproxy] (http://www.gateproxy.com)

<a target="_blank" href=""><img src="https://img.shields.io/badge/Development-ALPHA-blue.svg"></a>

[Gateproxy] (http://www.gateproxy.com) es un servidor para administrar pequeñas y medianas redes [LAN] (https://es.wikipedia.org/wiki/Red_de_%C3%A1rea_local), lo más intuitivo y desatendido posible, apto para el manejo del usuario, sin importar si tiene o no un alto grado de conocimientos en GNU/Linux, generando así una mejor experiencia.

El script de instalación y configuración es totalmente automatizado y personalizable, de acuerdo a las necesidades del administrador u organización, con una interacción mínima durante proceso, reduciendo así la curva de aprendizaje. Puede ser implementado tanto en un servidor "físico", como en una VM, para mayor flexibilidad y portabilidad.

**This Project is non-commercial. Only educational purposes**

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
![Gateproxy Script](https://camo.githubusercontent.com/6630b94909b393dbed2a5c354191f75ebbd3e4d0/68747470733a2f2f366633616662313131343361626133616534653431363336656563303433626561383461393039662e676f6f676c6564726976652e636f6d2f686f73742f304230494f43322d476859385051324e3163315a7751566c6a623363)

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

Este script alpha y puede dañar su sistema si se usa incorrectamente. Úselo bajo su propio riesgo. Lea el [HowTO Gateproxy] (https://goo.gl/ZT4LTi)

**Agradecimientos**

Agradecemos a todos aquellos que han contribuido a este proyecto, en especial [novatoz.com] (http://www.novatoz.com)

© 2016 [Gateproxy] (http://www.gateproxy.com) por [maravento] (http://www.maravento.com) se distribuye bajo una [Licencia Creative Commons Atribución-NoComercial-CompartirIgual 4.0 Internacional] (http://creativecommons.org/licenses/by-nc-sa/4.0/). Basada en una obra en maravento. Permisos que vayan más allá de lo cubierto por esta licencia pueden encontrarse en maravento

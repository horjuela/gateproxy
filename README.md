##Bienvenidos al proyecto [Gateproxy] (http://www.gateproxy.com)

[Gateproxy] (http://www.gateproxy.com) es un servidor, orientado a la administración de redes Home & Business, lo más intuitivo y desatendido posible, apto para el manejo del usuario, sin importar si tiene o no un alto grado de conocimientos en servidores GNU/Linux, generando así una mejor experiencia.

El script de instalación y configuración es totalmente automatizado con una interacción mínima durante proceso.
Puede ser personalizado de acuerdo a las necesidades del administrador u organización, sin que esto implique una excesiva intervención, reduciendo así la curva de aprendizaje.

También puede ser implementado tanto en un servidor "físico", como en una VM, para mayor flexibilidad y portabilidad.
Entre sus múltiples herramientas, se pueden mencionar un Proxy Cache, un Firewall, y muchas otras aplicaciones, en su mayoría libres, las cuales le brindan a su hogar u organización un alto nivel de seguridad, estabilidad, escalabilidad y administración de su entorno Home & Bussiness.

**Descripción**

- HowTO:        [gateproxy.pdf] (https://goo.gl/ZT4LTi)
- Update:       Jun 13/2016 10:09 UTC-05:00
- Version:      1.0 Alpha

**Requisitos Mínimos**

- GNU/Linux:    [Ubuntu 16.04.x (Xenial Xerus) LTS x64] (http://www.ubuntu.com/download)
- Procesador:   Intel compatible 1x GHz
- RAM:          4GB
- DD:           200 GB
- Display:      1024 x 768 128Mb Video
- Internet:     Alta velocidad (recomendado)
- Bash:         4.3x (verifique con echo $BASH_VERSION)
- Desktop:      [Mate] (http://mate-desktop.org/) (Opcional)
- Git:          sudo apt -y install git

**Instalación:**

Abra el terminal y ejecute:
```
$ git clone https://github.com/maravento/gateproxy.git
$ chmod +x gateproxy/gateproxy.sh && gateproxy/gateproxy.sh
```

**Importante:**

El soporte para Debian y Ubuntu (anteriores a 16.04 LTS) ha concluido. Haga upgrade con:
```
sudo apt-get -y install apt dpkg && sudo do-release-upgrade -d
```

**Proyectos Vinculados:**

Los proyectos [Blacklistweb] (http://www.blacklistweb.com) y [Blackstring] (http://www.maravento.com/p/blackstring.html) son componentes de Gateproxy.

**Exención de Responsabilidad**

Este script puede dañar su sistema si se usa incorrectamente. Úselo bajo su propio riesgo.

**Agradecimientos**

Agradecemos a todos aquellos que han contribuido a este proyecto, en especial [novatoz.com] (http://www.novatoz.com)

© 2016 [Gateproxy] (http://www.gateproxy.com) por [maravento] (http://www.maravento.com) se distribuye bajo una [Licencia Creative Commons Atribución-NoComercial-CompartirIgual 4.0 Internacional] (http://creativecommons.org/licenses/by-nc-sa/4.0/). Basada en una obra en maravento. Permisos que vayan más allá de lo cubierto por esta licencia pueden encontrarse en maravento

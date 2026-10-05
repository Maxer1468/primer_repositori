# Fitxa tècnica: Instal·lació i configuració bàsica d'Ubuntu Server

## Objectiu
Desplegar i configurar una màquina virtual amb Ubuntu Server aplicant directrius de xarxa estàtica, gestió de paquets i edició de documentació tècnica.

## Materials
* Ordinador amfitrió amb Windows.
* Gestor de virtualització (VirtualBox).
* Imatge ISO d'Ubuntu Server.
* Terminal SSH i editor Visual Studio Code.

## Procediment
1. Crear i arrencar la màquina virtual amb la instal·lació mínima d'Ubuntu Server.
2. Configurar la xarxa local mitjançant l'arxiu de Netplan.
3. Actualitzar els repositoris del sistema i instal·lar eines addicionals.
4. Gestionar el control de versions local amb Git.

![Esquema de connexió SSH i VirtualBox](imatges/virtualbox-ubuntu-schema.png)

## Comprovacions
- [ ] Verificar la connexió de xarxa amb ping.
- [ ] Comprovar l'estat dels serveis del sistema.
- [ ] Validar l'historial de canvis amb `git log`.

## Incidències i solucions

| Incidència | Solució |
| --- | --- |
| Pèrdua de connexió SSH per Netplan | Revisar la indentació amb espais i utilitzar `sudo netplan try`. |
| Ordre de `sudo` no disponible | Comprovar l'usuari o connectar directament a la consola de la VM. |

## Recursos
* [Documentació oficial de Git](https://git-scm.com/doc)
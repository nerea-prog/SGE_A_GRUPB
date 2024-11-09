# Restaurant THE BEAR

1. VENTES


Les vendes son on gestionem les demandes onlines.

En vendes tenim l’apartat de comandes de venda i pressupostos, on posarem el client, direcció de factura, direcció de entrega y la data de venciment, si tenim alguna llista de preus la podem posar, també les condicions de pagament en les que definim per exemple si volem un pagament immediat, o de un límit de dies. Seguidament posem els productes per fer el pressupost

![Descripción de la imagen](Imagenes/Ventes1.png)

Agregarem un mètode d’enviament on definirem el mètode i el pes de la ordre

![Descripción de la imagen](Imagenes/Ventes2.png)

Una vegada fet el pressupost ho podem confirmar y també enviar-li per correu electrònic

![alt text](image-2.png)

Ara seguidament d’això, crearem una factura d’aquest pressupost. Podem escollir si volem una factura regular, una anticipada per percentatge o bé una anticipada per import fix. 

![alt text](image-3.png)

## Punt de Venda

En aquest mòdul es troben els aplicatius necessaris per a la gestió econòmica dels diferents punts de venda, des de la taula de productes i preus fins a la gestió de comandes de les taules i el cobrament posterior.

### Taulell Principal

El taulell principal ofereix el control d’obertura de la caixa registradora, incloent dades sobre el total de diners en data de tancament.

![Pantalla Inicial](image.png)

### Comandes

Permet dur a terme un control de les diverses comandes fetes in situ i del total d’aquestes, a més de gestionar els tipus de pagament emprats i la finestra de preparació per a la cuina. Això permet una Integració i sincronització amb altres mòduls:
- **Comptabilitat:** Sincronització automàtica de les vendes amb la comptabilitat.
- **Comandes en línia:** Si el negoci té un canal de venda en línia, les vendes es poden integrar amb el punt de venda físic per gestionar l’inventari conjuntament.

![Pantalla comandes](image-1.png)
![Pantalla preparació cuina](image-2.png)

### Productes

A l’apartat de productes es troba el llistat actual de productes que ofereix el restaurant, amb la taula de preus i les diverses combinacions disponibles. Des d'aquesta opció es
pot modificar també els preus dels productes i afegir-ne un de nous.


#### Funcions Principals
- **Gestió de Productes:** Permet crear categories, definir preus, assignar codis de barres i establir variants de producte (com mida o color).
- **Actualització d’inventari en temps real:** Cada venda es reflecteix directament en el sistema d’inventari, facilitant el control d’estoc.

![Pantalles productes i preus](image-3.png)

### Informes de Venda

Aquest mòdul permet visualitzar informes de venda per conèixer quins productes tenen més o menys demanda, optimitzant així la compra de productes.

- **Tipus d’informes:** El sistema genera informes diaris, setmanals o mensuals amb dades detallades sobre productes venuts, ingressos i rendiment per punt de venda o caixer.

![Gràfiques de vendes](image-4.png)

### Configuració del Punt de Venda (POS) a Odoo

La configuració del sistema de vendes d’Odoo és fàcil d’usar i ideal per a comerços, hostaleria i negocis minoristes. Permet diverses opcions per adaptar-se a les necessitats específiques de cada negoci:

![Configuració](image-5.png)

- **Pagaments:** Configura diferents formes de pagament (efectiu, targetes de crèdit, moneders electrònics, etc.), així com les condicions de crèdit.

![Pagaments](image-6.png)

- **Sessions de venda:** Cada punt de venda té una sessió que es tanca al final del dia per fer el balanç. Odoo gestiona de manera automàtica la conciliació.

![Sessions de venda](image-7.png)

- **Disseny del restaurant i les taules:** Personalització del disseny del restaurant per facilitar la gestió de les comandes.

![Disseny de taules i restaurant](image-8.png)

## Planificació

El mòdul de planificació d’Odoo és una eina dins de l'ERP que ajuda les empreses a gestionar i planificar les tasques i els recursos de manera eficient. És especialment útil per organitzar l'assignació de treball en equips, optimitzant la disponibilitat dels recursos i facilitant una planificació precisa de projectes, activitats i esdeveniments.

### Funcions Clau

- **Planificació i assignació de recursos:** Permet assignar recursos (com persones, equips o materials) a projectes o tasques específiques, facilitant la visualització de la càrrega de treball i assegurant que cada membre de l’equip sàpiga què ha de fer i quan.

- **Calendari i Vista de Gantt:** Inclou una vista de calendari i una vista de Gantt, que són molt útils per visualitzar fàcilment el calendari de tasques i la progressió de projectes en el temps. La vista de Gantt és ideal per a projectes més complexos, ja que mostra la durada, les dependències i els terminis.

- **Gestió de permisos i disponibilitat:** La planificació permet que els usuaris indiquin la seva disponibilitat, els permisos i altres horaris específics. Això ajuda els administradors a planificar les tasques en funció de les disponibilitats de l’equip, evitant conflictes i sobrecàrregues de treball.

- **Sincronització amb altres mòduls (RRHH):** Permet integrar el mòdul de planificació amb el de Recursos Humans per gestionar millor les assignacions de personal.

- **Automatització i notificacions:** Configuració de notificacions automàtiques per informar els equips de noves tasques, canvis o recordatoris, així com alertes per a terminis. Això assegura una comunicació fluida i que els membres de l’equip estiguin sempre informats.

- **Anàlisi i informes:** El mòdul de Planificació d’Odoo inclou funcionalitats d’informes que permeten analitzar l'ús de recursos, la càrrega de treball i l’acompliment del personal en diferents projectes. Aquesta anàlisi ajuda a prendre decisions basades en dades i millora la planificació de futurs projectes.


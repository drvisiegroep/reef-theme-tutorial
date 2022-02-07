# reef-theme-tutorial

Disclaimers:
(Ik ga er van uit dat je al eens in de wordpress editor bent bezig geweest om gütenberg blokjes in mekaar te klikken.)
(Deze tutorial gaat ervan uit dat je het thema al klaar hebt staan en je er zo in kan duiken.)
(Aangezien het thema vol in de ontwikkelfase zit kan het zijn dat hier en daar dingen wat afwijken, maar de basis blijft ongeveer hetzelfde)
(Ook al ben ik geboren en getogen in Nederland, ik ben geen begenadigd schrijver. Dus assik so wil sgrijven dan doe 'k dat guwoon.)

Hoi! Leuk dat je het thema uitprobeert. We gaan samen in kleine stapjes proberen het thema iets aan te passen zodat je een beetje inzicht krijgt hoe een wordpress thema een beetje werkt. Het reef-theme bestaat uit een parent en een child. Er is genoeg informatie te vinden over hoe je zelf een child thema aanmaakt en aangezien er al een voor je is geïnstalleerd behandelen we dat op het moment niet.

Allemaal bestandjes en onbekende dingen. Het kan in het begin allemaal wat overweldigend overkomen maar daar gaan we langzaam proberen wat verandering in te brengen. Klein beginnen en 'hènig an dan breekt het lijntje niet' zei mijn opa altijd. Hènig an betekent rustig aan in het Twents. Zie, eerste dingetje al geleerd. Oh, dat wist je al? Nou dan gaan we kijken hoe ons thema er van binnen uitziet.

Ik zou persoonlijk aanraden een editor te gebruiken om je CSS en code aan te passen (Zoiets als VS Code) maar om het allemaal wat eenduidiger te houden ga ik je laten zien hoe je aanpassingen maakt in de Thema Editor van Wordpress zelf.


Voor we beginnen, wil ik graag eerst dat we even zeker weten dat we naar ons child-theme zitten te koekeloeren. Dat kan je controleren als je ingelogd bent op je wordpress site en dan naar Weergave > Thema's gaat.

![image](https://user-images.githubusercontent.com/78969608/152843201-9d9a1acd-acb7-4710-a2fd-bec5eb874d54.png)

Als daar je Reef Theme Child actief is ben je klaar om te beginnen.

![image](https://user-images.githubusercontent.com/78969608/152843591-2ec94441-7e8d-45ae-82f9-1ea3259beec9.png)

# Les 1
## AAAAAAH! BESTANDEN!

Overal bestanden, en mappen en nog meer bestanden met allemaal rare bestandsextensies. Het is ook allemaal niet makkelijk. Je kan er redelijk zeker van zijn dat ze allemaal hun nut hebben. We gaan even rustig door ons child thema heen kijken. Je hoeft niet te weten wat de bestanden allemaal doen. Kijk er gewoon rustig doorheen, raak gewend aan het zien van mappen en bestanden waarvan je nog geen idee hebt wat ze allemaal doen. Als je nieuwsgierig bent klik je een bestandje aan en kijk je wat er in staat. Ben je er klaar voor?

Dan ga je naar Weergave > Thema bestand editor en ga je daar even door de mapjes en bestandjes heen kijken.

![image](https://user-images.githubusercontent.com/78969608/152844017-ca1d8c92-3aa3-4546-b277-13dbb5672a28.png)

![image](https://user-images.githubusercontent.com/78969608/152844306-45c9e500-ffdb-48db-9e19-162f42f9cc58.png)

css, js, custom, inc, php, svg, assets, themafuncties er vliegen je nogal wat termen om de oren. Maar hoe een thema onder de motorkap nou eigenlijk werkt is van latere zorg. We gaan eerst eens kijken naar onze css. In tegenstelling tot wat je misschien zou denken zit de css niet verstopt in style.css. Dat komt omdat we er voor hebben gekozen om onze css op een vaste plek te houden, samen met onze javascript, plaatjes en ander spul. De style.css wordt in een child thema gebruikt om onder andere aan te geven hoe je thema heet. Dan weet Wordpress ook waar 'ie aan toe is.

![image](https://user-images.githubusercontent.com/78969608/152845414-40c2ee24-73e5-4746-8b5b-04f3e215a92c.png)






